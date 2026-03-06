# experience-classifier-svm

Predicting employees experience levels using Support Vector Machines in Python.

## How to Run this Project

To run this notebook in Google Colab without errors, follow these steps:

### 1. Prepare the Data

* Download the Dataset salary 2024.csv from this repository.

* Upload that file to your Google Drive.

### 2. Configure the Notebook

* Open the notebook in Google Colab.

* Run the first cell to Mount Google Drive. You will need to click the link and grant permission.

* In the Colab sidebar on the left, click the Folder icon, find your CSV in the drive folder, right-click it, and select "Copy path". Then just paste that into the read_csv() function.

### IMPORTANT: 

In the second cell, locate the line:

```cpp
df = pd.read_csv("/content/drive/MyDrive/...")
```

Replace the `...` with your actual folder path.

### 3. Execution

* Once the path is updated, you can go to `Runtime` > `Run all`.

* The notebook will load the data, train the SVM model, and display the classification results.
