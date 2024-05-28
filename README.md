# Welcome to the Brown University Datathon 2024!

## Objectives and Tracks

The objective is to investigate the impact of the data issues that exist in electronic health records on downstream clinical prediction tasks. We shall investigate the effect of a faulty pulse oximeter reading, the effect of a missing serum lactate level, and the effect of the combination of the two on mortality prediction in the hospital. We will be creating 3 "altered" datasets in addition to the original WiDS dataset:

1. A dataset where the SpO2 of the Black patients will be increased by 3%

2. A dataset where we drop the serum lactate measurements of Black patients

3. A dataset where the SpO2 of the Black patients will be increased by 3% and their serum lactate is dropped


We exaggerate these data issues to get a sense of their impact on machine learning which surprisingly has not been sufficiently explored by the machine learning community.

[Notebook 0](https://github.com/joamats/mit-brown-datathon/blob/master/0_datasets.ipynb) executes these operations. Please run it before the Datathon, to make sure that your environment works!

## Schedule

* [Notebook 1](https://github.com/joamats/mit-brown-datathon/blob/master/1_eda.ipynb) - **First hour:** data visualization and table one of the WiDS dataset. 
  
* [Notebook 2](https://github.com/joamats/mit-brown-datathon/blob/master/2_baseline_models.ipynb) - **Second hour:** Build a mortality prediction model using the [WiDS dataset](https://physionet.org/content/widsdatathon2020/1.0.0/). Evaluate performance across race-ethnicities in the test set. 
  
* [Notebook 3](https://github.com/joamats/mit-brown-datathon/blob/master/3_biased_models.ipynb) - **Third hour:** Build a mortality prediction model using one of three altered datasets. Use the same test set as above, but with the new features. 

* **Fourth hour:** Compare the two models and prepare presentation for Day 2.


## Materials (online)

* [WiDS dataset](https://physionet.org/content/widsdatathon2020/1.0.0/) - please download the data from here, and run [Notebook 0](https://github.com/joamats/mit-brown-datathon/blob/master/0_datasets.ipynb) to create the train and test subsets with the modified features - **before the datathon!!**

* [Data Dictionary](https://physionet.org/content/widsdatathon2020/1.0.0/data/WiDS_Datathon_2020_Dictionary.csv) - to understand what the variables mean


## Happy coding!

