#CODTECH DATA ANALYSIS INTERNSHIP#-
All 4 internship tasks submission

*COMPANY*: CODTECH IT SOLUTION

*NAME*: ASMIT ARVIND SHAH

*INTERN ID*: CTIS7975

*DOMAIN*: DATA ANALYTICS

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH
_______________________________________________________________________________________________________________________________________________________________
1) TASK1- BIG DATA ANALYSIS:

##DESCRIPTION OF THE TASK-

In this task, I performed big data analysis using PySpark, which is a powerful tool used for processing large datasets efficiently. The main objective of this task was to understand how big data tools work and how they can be used to analyze data at scale. For this purpose, I used Google Colab as my working environment and installed PySpark to create a Spark session. This session allowed me to handle data in a distributed manner, which is one of the key advantages of using PySpark over traditional data processing tools. I worked on a dataset related to restaurant tips, which includes details such as total bill, tip amount, gender, day, and other attributes. Initially, I faced an issue while directly loading the dataset using a URL, but I resolved it by first loading the data using Pandas and then converting it into a format readable by PySpark. This helped me understand practical challenges and how to solve them during real-world data analysis tasks.

After successfully loading the dataset into a PySpark DataFrame, I started by exploring its structure using the printSchema() function. This step was important because it helped me understand the data types of each column, such as numerical and categorical variables. Then, I performed basic analysis by counting the total number of records in the dataset, which gave me an idea about the size of the data. I also calculated the average value of the total bill using aggregation functions, which is a common operation in data analysis. These initial steps helped me build a foundation for further analysis. I made sure to follow proper syntax and functions in PySpark, and I learned how similar operations are performed differently compared to normal Python libraries like Pandas.

Further, I performed grouping operations to extract meaningful insights from the dataset. I grouped the data based on gender to analyze differences in spending behavior, and also grouped it by the day of the week to understand how customer spending varies across different days. From the results, I observed that weekends like Sunday and Saturday have higher average total bills compared to weekdays, indicating higher customer activity. I also performed tip analysis to see how tipping behavior changes based on the day. These insights are useful in real-world scenarios, especially for businesses to make decisions based on customer patterns. Overall, this task helped me understand the practical implementation of big data analysis using PySpark and improved my skills in handling datasets efficiently while extracting meaningful information.

#OUTPUT-

<img width="494" height="554" alt="Image" src="https://github.com/user-attachments/assets/13f7838a-9bad-4aba-a8c0-bbdbc0d7d9a6" />

____________________________________________________________________________________________________________________________________________________________________
2) TASK2-PREDICTIVE ANALYSIS USING MACHINE LEARNING:

##DESCRIPTION OF THE TASK-

In this task, I performed predictive analysis using machine learning techniques with the help of PySpark in a Google Colab environment. The primary objective was to build a regression model that could predict the tip amount based on the total bill using a real-world dataset. To begin with, I set up the environment by installing PySpark and initializing a Spark session, which is essential for handling large-scale data processing. The dataset used for this task was the popular “tips” dataset, which contains information about restaurant bills, including attributes such as total bill amount, tip, gender, smoking status, day, time, and size of the group. Since PySpark does not directly support loading data from an online URL, I first downloaded the dataset using the Pandas library and then saved it locally as a CSV file. After that, I loaded the dataset into a PySpark DataFrame with schema inference enabled, allowing the system to automatically detect the correct data types of each column.

After successfully loading the dataset, I moved on to preparing the data for machine learning. In PySpark, machine learning models require input features to be in vector format, so I used the VectorAssembler tool to convert the selected feature into the required format. In this case, I selected the “total_bill” column as the input feature and the “tip” column as the target variable. The assembler transformed the dataset by creating a new column called “features,” which contained the input values in vector form. This step is crucial because machine learning models in PySpark cannot directly work with raw columns. Once the data preparation was completed, I implemented a Linear Regression model, which is a widely used algorithm for predicting continuous numerical values. The model was configured by specifying the feature column and label column, and then it was trained using the prepared dataset. During this process, the model learned the relationship between the total bill and the tip amount.

Finally, I evaluated the performance of the model by generating predictions and analyzing the results. Using the trained model, I applied the transform() function to produce a new DataFrame that included a “prediction” column along with the original values. This allowed me to compare the actual tip values with the predicted ones, giving a clear understanding of how well the model performs. The results showed that the predicted values were quite close to the actual values, indicating that the model was able to capture the relationship between the variables effectively. Additionally, I examined the model’s coefficients and intercept, which provided further insight into how the model makes predictions. The coefficient indicated a positive relationship between the total bill and the tip, meaning that as the bill increases, the tip also tends to increase. Overall, this task helped me understand the complete workflow of building a machine learning model using PySpark, including data loading, feature engineering, model training, prediction, and evaluation, and demonstrated how predictive analysis can be used to derive meaningful insights from data.

#OUTPUT-

<img width="397" height="556" alt="Image" src="https://github.com/user-attachments/assets/8e944ce3-783b-4239-87ea-c26ef25e1aa6" />

_______________________________________________________________________________________________________________________________________________________________
3) TASK3-

