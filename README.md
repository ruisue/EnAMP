# EnAMP
## surui 

## Table of contents
* [Install](#Install)
	* [Install using `pip`](#Install)
	* [package](#Package)
* [Usage](#Usage)
  	* [data](#data)
	* [Classifier](#Classifier)
	* [Example](#Example)
## Install
### Install using `pip`

Firstly, we suggest to build a new virtual environment through `Anaconda`:
```
conda create -n    python=3.6
```
Create and activate the virtual environment environment `    `:
```
conda activate  
```
### Package
| package | version |
| :----: | :----: |
| keras  | 2.2.4 |
| tensorFlow | 1.14.0 |
| scikit-learn | 0.24.1 |
| genism | 3.8.3 |
## Usage
### data:
  * data:training data and test data for peptide sequences
### Classifier:
  * train.py is the implemention of our model.The statistical features of the training set peptide sequence are respectively input into RF and SVM, and the two kinds of word embedding features are respectively input into the deep learning framework for training
  * predict.py is used to predict new samples.The statistical features of the test set peptide sequence are respectively input into RF and SVM, and the two kinds of word embedding features are respectively input into the deep learning framework for testing
### Example:
  * Example:Examples contain 9 types of statistical features as well as complementary example protein sequences
