 # :dart: K-Means Clustering on Online retail dataset 
 
 ### Project Description 
 This project is created for applying unsupervised clustering algrithm ***K-Means*** in the day to day life and form cluster out of dataset. A cluster is the collection of data that share a similar attribute. Being one of the simplest algorithm, this is the best to work on while beginning in Machine Learning.

 ###  Dataset
 * The dataset has been extracted from kaggle. The purpose of this dataset is to do an Exploratory data analysis, Pre-process the data and then perform clustering.
 * I am attaching the link to the dataset <a href = https://www.kaggle.com/datasets/ersany/online-retail-dataset>here</a>
 * This dataset contains transactions occuring between ***01/12/2020 and 09/11/2021*** for a UK based and registerd non-store online client.The company mainly sells unique all occasion gifts.Many customers of the company are wholesaler. 
 
 ### Metadata
 
Feature | Description | Datatype
| :---: | :---: | :---:
InvoiceNo  | 6-digit unique integer assigned to each transaction | Nominal
StockCode| 5-digit integer assigned for each product |Nominal
Description |Product name| Nominal
Quantity | Quantities of product | ***Numeric***
UnitPrice | Product price per unit | ***Numeric***
CustomerID | Customer number | Nominal
Country | Country name | Nominal

### Pre-Processing the Dataset
* *Checking and treating the missing values*
* *Treating the column **CustomerID** to integer datatype*
* *Exploring the numeric feature(using BoxPlot) and removing outliers*


### K-Means Clustering
- [x] Scatterplot for ***UnitPrice*** and ***Quantity***
![image](https://user-images.githubusercontent.com/74041244/162004356-61f08163-bed0-4690-9a6b-c4d9b7f605b4.png)
- [x] Applying KMeans method to determine ***WSS(Within Sum of Squares)***
- [x] Plotting WSS against differnt values for ***k***(Elbow Method)
![image](https://user-images.githubusercontent.com/74041244/162006527-9b738299-fac1-42be-97f1-2082307f9de6.png)
- [x] Fitting the K-Mean model with the optimal value for ***k***
![image](https://user-images.githubusercontent.com/74041244/162005849-b9fdd185-e77f-4718-954b-9b78758a21f0.png)
- [x] Plotting the clusters and highlighting the centroids
![image](https://user-images.githubusercontent.com/74041244/162005098-784578fa-d8cf-40ba-a1fb-5eb7a0449333.png)
- [x] Calculating Silhoutte Score

### Note
It is important to do EDA before performing clustering on the dataset. Also, please ensure you treat the dataset and remove any outliers that can bias the result.

***I hope you enjoyed the job I created. Feel free to reach out to me at pbhaliyan73@gmail.com*** <br>
### See you around learning !!
