# 100DaysOfMLCode
100 days of ML Code.

# Day 1 - Data Preprocessing

Step 1 : Import the required libraries
         There are two important libraries, Numpy and Pandas. Numpy for Mathematical functions and Pandas for importing and managing the            datasets.
         
Step 2 : Importing the Dataset
         Dataset are available in the CSV format. We use read_csv of pandas library to read the local CSV as a data frame and then seperate          matrix and vector of independent and dependent variables from the data frame.
        
Step 3: Handling the Missing data
        The performance of the machine learning model should not be reduced due to the missing data, So we have handle the missing data. We         can use the Imputer class from sklearn.preprocessing for handling the missing data.
       
Step 4: Encoding
        Sometime the categorical variables cannot be used in the mathematical functions. So, we have change the categorical variables into         a numerical ones, we can accomplish this task by using the LabelEncoder from the sklearn.preprocessing.
        
Step 5: Split the data
        To know the efficiency of the model we have to split the data into test set and the training set. The split is generally 80 percent         training set and 20 percent testing test. we can use train_test_split() method of sklearn.crossvalidation library.
        
Step 6: Feature scaling
        Most of the machine learning algorithms use the eucledian distance between the two data points and for their computations. This can         acheived by Z-score normalisation. StandardScalar of sklearn.preprocessing is used for it.


# Day 2 - Implementation of DataPreprocessing

Please check the dataset https://github.com/mohanbabu8393/100DaysOfMLCode/blob/master/Dataset/SampleData.csv and the implementation here 
https://github.com/mohanbabu8393/100DaysOfMLCode/blob/master/Implementation/Day1-Data%20Preprocessing.ipynb

Thanks :) 
