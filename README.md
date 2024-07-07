# IoT Network Intrusion Detection with Ensemble Learners

## The paper

S. A. Abdulkareem, C. H. Foh, H. Lee, F. Carrez, K. Moessner, "IoT Network Intrusion Detection with Ensemble Learners, " in ICTC 2022. [![Get PDF](https://img.shields.io/badge/Get-PDF-red)](https://ieeexplore.ieee.org/document/9952376)

## The Dataset

We are using Bot-IoT dataset created by Koroniotis *et al*. The information about the dataset is given at https://ieee-dataport.org/documents/bot-iot-dataset. We copied the four csv files over to this repository, they are zipped as their original size is too large and exceeds the file size limit for uploading.

In our program, we use a concatenated csv file instead of original individual csv files. We concatenate the csv files into a single csv file and apply some data cleaning. The script to concatenate the csv files is given here as [CombineData.ipynb](https://github.com/cfoh/IoT-Network-Intrusion-Detection-with-Ensemble-Learners/blob/main/CombineData.ipynb). The concatenated csv file exceeds the file size limit even after compression, thus it is not provided here. Please use the script to generate the concatenated csv file.

### The Machine Learning (ML) Models

In our paper, we applied the following 5 ML models. You can also find the source code in this repository.
- Adaboost
- LightGBM
- Random Forest
- CatBoost
- XGBoost
