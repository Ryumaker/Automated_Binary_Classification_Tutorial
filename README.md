# Automated_Binary_Classification_Tutorial
2022 INHA University OSS Project #2 - Automated Binary Classification

### :computer: Automated Machine Learning (AutoML)
AutoML is the process of **_automating the time-consuming, iterative tasks of machine learning_** model development

### :warning: In this tutorial, datasets must satisfy following requirements
:one: Binary classification  
:two: All values are numeric  
:three: No missing values  
:four: The name of the label column is **_“target”_**  

### :pencil2: Usage
```
python template.py DATA_CSV_PATH TEST_SIZE
```
**_TEST_SIZE in the form of ratio_**

### :bookmark_tabs: Function Descriptions
- **_load_dataset_**  
Load the csv file at the given path into the pandas DataFrame and return the DataFrame

- **_dataset_stat_**  
For the given DataFrame, return the following statistical analysis results in order  
: Number of features, Number of data for class 0 / 1

- **_split_dataset_**  
Splitting the given DataFrame using the given test size and return train data, test data, train label, and test label in order

- **_decision_tree_train_test_**  
Using the given train dataset, train the decision tree model.  
After the training, evaluate the performances of the model using the given test dataset

- **_random_forest_train_test_**  
Using the given train dataset, train the random forest model.  
After the training, evaluate the performances of the model using the given test dataset

- **_svm_train_test_**  
Using the given train dataset, train the pipeline consists of a standard scaler and SVM.  
After the training, evaluate the performances of the model using the given test dataset
