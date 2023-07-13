# Integrated-Analysis---K-means-Clustering-
Integrated Analysis - K-means Clustering using Tableau &amp; R
(R file and Tableau file are in the document)

# Objective
This Project aims to work with K-means clustering analysis using R and visualizing results through Tableau.
Below are the objectives of the exercise
   
1) Data pre-processing
 
2) K-mean clustering
  
4) Tableau- R integration by invoking Rserve ()


# Data Pre- Processing
This steps involves replacing the missing value of the ages with their mean, adding an age category column, and replacing the label with a meaningful name

Calculate the average age of the passengers 
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/25415707-e139-4ccd-a27c-506e04ce78b6)
Ans: 29.69912

to round off the age to their nearest integer
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/621d2a3d-487e-44b2-afac-68ed5bfde9f1)

Create a new variable (vector) called Age Category and assign a category to every passenger in the dataset.
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/179d13c5-a44e-4aaf-91a4-5e612ca910cd)

Replace the integer value of 0 and 1 in the survivor variable (vector) with meaningful labels.
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/16a8f6b2-2ff2-42a8-9492-8fab82fbace7)

Convert the integer and character vectors to factor variables as mentioned in the screenshot for the other variables
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/76ef4d4f-7a9e-4fa0-8697-7d93db6e582e)

Remove the other redundant variables such as Ticket and Cabin from the titanic data frame.
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/ffc37987-e701-4c96-b292-567c8a5b1986)

Crosscheck the processed values using the command as mentioned below.
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/807b0029-f92c-433f-9289-a2c1c42906d4)

![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/4c32a3f4-d769-4b8f-b72e-cc25493775e3)

# K-Means Clustering
Three important categorical variables in the titanic dataset are

1.	Survived 
2.	Sex
3.	Embarked

Convert the above 3 categorical variables into continuous. The below code would create 3 new variables of type continuous and save them in the new file “titanicUpdated.csv”.
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/abd2af5d-e088-4d94-a872-bff029409db8)
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/0403824d-1b45-48a8-bef1-c41fcd74a5fb)
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/08adb953-26b7-44bf-b14f-56ec7ab666f9)
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/afb9c7ee-9ad4-45e2-82d0-05f9d3012f15)
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/8ff3cdd1-abfd-4d79-8d60-966731e87537)

*****Before the cluster analysis one has to select the optimum number of clusters******

To find the total number of clusters the below code is necessary
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/8f553c49-eb56-40e1-a01d-a4aaf712c9e7)

To Plot the two graphs 
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/bce434fb-2eb6-4951-bc66-aeb4d27eff52)
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/e4046465-874f-4268-b45e-b841782aada7)
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/9a90bcd0-d36c-4e09-8a31-58b129deed32)
![image](https://github.com/Jeswin21/Integrated-Analysis---K-means-Clustering-/assets/85884215/f4153b5a-b4a2-4991-8a15-af68b6266f62)


Desired number of Clusters: 5

# TABLEAU / R INTEGRATION
# Please refer the tableau workbook uploaded in the file










