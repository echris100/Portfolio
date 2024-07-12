### <h1> My Data Analytics Portfolio Projects <br/></h1>

### [Project 1: SQL IMDB movie Analysis]
### Project Goal: The goal of this project is to analyze imdb movie database using pandas and sql queries. First the data was collected from kaggle, then loaded into the data warehouse. Then the data was loaded into pandas Dataframe, using Jupyter notebooks cleaning and processing and finally loaded into SQL server database for further analytics. The following questions were used to analyse this dataset:

#### Question 1:
![sql_1](https://github.com/user-attachments/assets/a8fde989-8a18-420d-8308-76a85cb743a8)

#### Question 2a:
![sql_2a](https://github.com/user-attachments/assets/6107b034-b2b9-4203-ab42-bb0a8a3e7aa8)

#### Question 2b:
![sql_2b](https://github.com/user-attachments/assets/5c5da5ac-af4d-4e2b-b9cc-22ec739c554d)

#### Question 2c: 
![sql_2c](https://github.com/user-attachments/assets/f431a408-b394-46af-8059-cdb93b14affb)

#### Question 3a:
![sql_3a](https://github.com/user-attachments/assets/a2b5ccdb-2d76-4a67-97d1-acfa512ae333)

#### Question 3b:
![sql_3b](https://github.com/user-attachments/assets/53240648-6908-400d-9a74-7f74dca06883)

#### Question 4:
![sql_4](https://github.com/sirskin01/try01/assets/144762826/ddf6dad6-791d-4f26-b718-38c9642d44ab)

#### Question 5:
![sql_5](https://github.com/user-attachments/assets/6917c045-df9b-4d62-9341-f35e4c2fca77)

#### Question 6:
![sql_6](https://github.com/user-attachments/assets/c35b8914-ad81-4553-99aa-bf190028c504)

#### Main takeaways: 
##### In 2014, there were over 699 movies that were released, with Avatar having the highest revenue, while spatacus has the highest gross and Wild card receive zero in revenue.
##### The highest budget spent ever on any movie was on The warriors way. Jurassic world has the longest running time by popularity while Adam curtis, as a director, has directed at least 3 movies with an average score above 7.



### [Project 2: Titanic Machine Learning Prediction with Decision Tree]
#### In this project, titanic dataset was analyzed using Decision tree model to predict the survival rate of the passengers on board. From our analysis, it was discovered most men did not survive compared to the women on board. Also, the dependent variables such as Passenger ID, Age, fare were used to predict the independent variable 'survived' by using the decision tree model for the analysis.
[Predicting Survival Rate(Titanic).pdf](https://github.com/user-attachments/files/16195590/Predicting.Survival.Rate.Titanic.pdf)



### [Project 3: Power BI HR Attrition Dashboard] 

#### Project Goal: Is to analyze the HR Attrition currently taking place in the organization

##### I collected the data, stored, transformed, and retrieved it for analysis and reporting purposes. Using query editor, I was able to promote the headers as this was missing from the original dataset.  I also transformed the Age column to integer, changed salary type from monthly to yearly and added the salary column to the dataset. A conditional column called Attrition count was also included.
##### In the data model view, I computed the Age bins category to make our analysis much more efficient. I also calculated measures like Attrition rate, Average salary, Max salary, Min salary and Active employees.
##### I created reports using Card, column charts, clustered bar chart, donut chart, pie chart, line chart and slicers for comparison and analysis purposes. The reports were shared within user groups using power Bi apps and then published to power Bi services. By pinning the visuals from the reports, I created a dashboard. I implemented static and dynamic Row level security in the data model in power bi desktop and assigned roles to the users.
### Overview of the Dashboard 
![image](https://github.com/user-attachments/assets/fdaaf62c-bd36-4ac5-bc10-934117bc2009)



### [Project 4: Tableau Sample SuperStore Dashboard] 

#### Project Goal: To analyze the company's sales and profit performances. The dashboard also shows the different kPI’s as well as the current year to date sales of all categories and subcategories. 
##### I imported the data from Kaggle, checked for null values. I created the different KPI’s, which include sales kpi, profit kpi and quantity kpi to show the amount of progress made towards the different measurable goals. The YTD vs PYTD chart of sub-categories shows that phone sub-categories are performing better than the labels sub-catgogries.
![image](https://github.com/user-attachments/assets/77ff7d31-466d-4e6d-9200-f20cd44b9832)

### Weekly Dashboard: 
#### This dashboard was created to track the weeekly performance of the store in terms of sales and profits
![image](https://github.com/user-attachments/assets/fc7183d2-92a0-4358-b35d-be51bacc82b1)

##### From the dashboard, Apple products has the highest sales with quantity ordered. The central region has the highest profit wheras central asia has the lowest profit in terms of profits by regions.







### [Project 5: Knime Markerting Analysis][Build models using Drag and Drop, No Code]
##### In this project, I analyzed Ebayauctionc dataset using Decision Tree model to predict if an Item placed on auction will be competitive or not. I loaded the dataset using the csv reader node, and then cleaned and prep the data for validation. The target variable here is 'Iscompetitive', hence I used the partitioning node to divide the dataset into 70% for the training data and 30% for validation. There are two part to this model, the training model was pruned to reduce overfitting and improve the complexity of the acuracy of the data.


#### Decision tree model: The Decision Tree for the training data is pruned for better accuracy 
![model_prun](https://github.com/user-attachments/assets/a83de6e1-4401-465e-bc9c-04c648cb503b)

#### Decision tree diagram: 
![image](https://github.com/user-attachments/assets/05f15cb6-8bac-4a07-ac76-2c14f97b8ba6)

##### From the first tree model, a total of 1029 observations were made, 566 were competitive. The first split was Open Price, and it suggests that for any item to be competitive, it will depend on the first split (open price). If the open price is <= 2.4499 then that item is said to be competitive with an observe rate of 314 / 406. If open price > 2.4499 then that item will be less competitive with an observe rate of 371 / 623.

#### confusion matrix
![prun_conf](https://github.com/user-attachments/assets/32c62184-1c96-4219-b5fb-87da815b42e1)

#### Checking the accuracy of the model:
![image](https://github.com/user-attachments/assets/be9bd5f6-a16a-416f-9a61-fcf1f63b879c)

![image](https://github.com/user-attachments/assets/2263d4b7-38f8-4f57-95ed-a7e007a2d75f)

##### The pie chart shows that from our decision tree predictor, 51% of items will be non-competitive on auctions while 49% will be competitive on auctions.

##### In conclusion, we can see that the scorer node compares two columns by their attirbutes and shows the confusion matrix. The accuracy of our model is 89.82%. From the confusion matrix above, out of 198 cases on non-competitiveness from items on auction, our model predicted 198. Also, out of 199 of items being competitive and our model predicted 199 as well. Our confusion matrix shows an accuracy of 89.82%, with an error rate of 10.18%, with wrongly classified values of 29+16 = 45 and correctly classified values of 198 + 199 = 397.





### [Project 6: SQL Sales Analysis]
#### In this project, customer orders and sales were analyzed using Sql joins, CASE statements and subqueries. The data was collected from kaggle, loaded into the warehouse for further analytics.

#### Loading and querying the dataset
![orders ](https://github.com/user-attachments/assets/ef0ee670-2d50-4770-a359-f557805b00b4)

![order_det](https://github.com/user-attachments/assets/7f88e361-4d4d-44e3-a1a9-befe40f36df0)

![sales_tar](https://github.com/user-attachments/assets/60362be2-ec8d-42db-91ab-eed5c722eb75)


#### Question 1:
![Q1](https://github.com/user-attachments/assets/270cd645-a627-49f5-84e8-2627721cff9c)

#### Question 2:
![Q2](https://github.com/user-attachments/assets/b565a367-7529-416a-bdf2-585388d1096f)

#### Question 3:
![Q3](https://github.com/user-attachments/assets/6f56790e-235f-4427-932a-fb1a5f9bd569)

#### Question 4:
![Q4](https://github.com/user-attachments/assets/079c06fd-1ef9-45e9-ac56-c15d1a0922af)

#### Question 5:
![Q5](https://github.com/user-attachments/assets/0bb46dee-fd27-46c9-92f3-b6dc0c29eb4c)

#### Question 6:
![Q6](https://github.com/user-attachments/assets/2130d23c-c9f4-4804-93dd-0e481c48ad10)

#### Question 7:
![Q7](https://github.com/user-attachments/assets/243e5ee3-528c-4427-8408-1d117fb1bd29)

##### In conclusion, Archer Hort is the customer with the highest order greater than $1000. In terms of profit, the southern region has the highest maximum profit and France has the highest total sales from all countries. 

<h3> 🤳 Connect with me:</h3>
[Linkedin]www.linkedin.com/in/chrisemezie

