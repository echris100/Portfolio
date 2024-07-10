### <h1> My Data Analytics Portfolio Projects <br/></h1>

### [Project 1: SQL IMDB movie Analysis]
### Project Goal: The goal of this project is to analyze imdb movie database using pandas and sql queries. First the data was collected from kaggle, then loaded into the data warehouse. Then the data was loaded into pandas Dataframe, using Jupyter notebooks cleaning and processing and finally loaded into SQL server database for further analytics. The following questions were used to analyse this dataset:

#### Question 1:
![sql_1](https://github.com/sirskin01/try01/assets/144762826/99966dd4-787e-4456-b8f4-63a7a37d26ac)

#### Question 2a:
![sql_2a](https://github.com/sirskin01/try01/assets/144762826/42025e2f-d191-474b-8f7c-46450678c9e4)

#### Question 2b:
![sql_2b](https://github.com/sirskin01/try01/assets/144762826/4bcb7f59-a97a-4036-bb88-a98cbf24a59c)

#### Question 2c: 
![sql_2c](https://github.com/sirskin01/try01/assets/144762826/340fd7b1-2123-480c-a074-bf8df09c3c79)

#### Question 3a:
![sql_3a](https://github.com/sirskin01/try01/assets/144762826/1bbf26e2-3c40-49b4-a12f-a2d5cfcc2059)

#### Question 3b:
![sql_3b](https://github.com/sirskin01/try01/assets/144762826/7705561f-ba99-4365-b4f7-ce46b10fdb7a)

#### Question 4:
![sql_4](https://github.com/sirskin01/try01/assets/144762826/ddf6dad6-791d-4f26-b718-38c9642d44ab)

#### Question 5:
![sql_5](https://github.com/sirskin01/try01/assets/144762826/0164552a-df67-4bd0-992f-678879e799d2)

#### Question 6:
![sql_6](https://github.com/sirskin01/try01/assets/144762826/8ee98452-b820-4e3f-a4ce-a145b8b3e81f)

#### Main takeaways: 
##### In 2014, there were over 699 movies that were released, with Avatar having the highest revenue, while spatacus has the highest gross and Wild card receive zero in revenue.
##### The highest budget spent ever on any movie was on The warriors way. Jurassic world has the longest running time by popularity while Adam curtis, as a director, has directed at least 3 movies with an average score above 7.



### [Project 2: Titanic Machine Learning Prediction with Decision Tree]
#### In this project, titanic dataset was analyzed using Decision tree model to predict the survival rate of the passengers on board. From our analysis, it was discovered most men did not survive compared to the women on board. Also, the dependent variables such as Passenger ID, Age, fare were used to predict the independent variable 'survived' by using the decision tree model for the analysis.
[Predicting Survival Rate(Titanic).pdf](https://github.com/user-attachments/files/16121938/Predicting.Survival.Rate.Titanic.pdf)




### [Project 3: Power BI HR Attrition Dashboard] 

#### Project Goal: Is to analyze the HR Attrition currently taking place in the organization

##### I collected the data, stored, transformed, and retrieved it for analysis and reporting purposes. Using query editor, I was able to promote the headers as this was missing from the original dataset.  I also transformed the Age column to integer, changed salary type from monthly to yearly and added the salary column to the dataset. A conditional column called Attrition count was also included.
##### In the data model view, I computed the Age bins category to make our analysis much more efficient. I also calculated measures like Attrition rate, Average salary, Max salary, Min salary and Active employees.
##### I created reports using Card, column charts, clustered bar chart, donut chart, pie chart, line chart and slicers for comparison and analysis purposes. The reports were shared within user groups using power Bi apps and then published to power Bi services. By pinning the visuals from the reports, I created a dashboard. I implemented static and dynamic Row level security in the data model in power bi desktop and assigned roles to the users.
### Overview of the Dashboard 
![image](https://github.com/sirskin01/try01/assets/144762826/2d3bdf81-4560-43a0-b4e8-e7c3381de747)






### [Project 4: Tableau Sample SuperStore Dashboard] 

#### Project Goal: To analyze the company's sales and profit performances. The dashboard also shows the different kPI’s as well as the current year to date sales of all categories and subcategories. 
##### I imported the data from Kaggle, checked for null values. I created the different KPI’s, which include sales kpi, profit kpi and quantity kpi to show the amount of progress made towards the different measurable goals. The YTD vs PYTD chart of sub-categories shows that phone sub-categories are performing better than the labels sub-catgogries.
![image](https://github.com/sirskin01/try01/assets/144762826/2eea9331-85a1-4261-b54e-4ed490ed2485)

### Weekly Dashboard: 
#### This dashboard was created to track the weeekly performance of the store in terms of sales and profits
![image](https://github.com/sirskin01/try01/assets/144762826/c3339b6c-6060-4c7b-a05c-758fc93a48c8)
##### From the dashboard, Apple products has the highest sales with quantity ordered. The central region has the highest profit wheras central asia has the lowest profit in terms of profits by regions.







### [Project 5: Knime Markerting Analysis][Build models using Drag and Drop, No Code]
##### In this project, I analyzed Ebayauctionc dataset using Decision Tree model to predict if an Item placed on auction will be competitive or not. I loaded the dataset using the csv reader node, and then cleaned and prep the data for validation. The target variable here is 'Iscompetitive', hence I used the partitioning node to divide the dataset into 70% for the training data and 30% for validation. There are two part to this model, the training model was pruned to reduce overfitting and improve the complexity of the acuracy of the data.


#### Decision tree model: The Decision Tree for the training data is pruned for better accuracy 
![model_prun](https://github.com/sirskin01/try01/assets/144762826/fe99467b-c793-4640-8001-6255a2a4fa1f)

#### Decision tree diagram: 
![image](https://github.com/echris100/Portfolio/assets/163300581/a11bb379-7f74-458f-93ed-f3cead29f67c)
##### From the first tree model, a total of 1029 observations were made, 566 were competitive. The first split was Open Price, and it suggests that for any item to be competitive, it will depend on the first split (open price). If the open price is <= 2.4499 then that item is said to be competitive with an observe rate of 314 / 406. If open price > 2.4499 then that item will be less competitive with an observe rate of 371 / 623.

#### confusion matrix
![prun_conf](https://github.com/sirskin01/try01/assets/144762826/90a27939-de6d-442b-a37f-43d192a1dd86)

#### Checking the accuracy of the model:
![image](https://github.com/sirskin01/try01/assets/144762826/d684a942-48ca-4c38-bf50-8b97d856dee3)

![image](https://github.com/sirskin01/try01/assets/144762826/75a84b44-16b7-47a8-9733-69a7f8a7a47a)
##### The pie chart shows that from our decision tree predictor, 51% of items will be non-competitive on auctions while 49% will be competitive on auctions.

##### In conclusion, we can see that the scorer node compares two columns by their attirbutes and shows the confusion matrix. The accuracy of our model is 89.82%. From the confusion matrix above, out of 198 cases on non-competitiveness from items on auction, our model predicted 198. Also, out of 199 of items being competitive and our model predicted 199 as well. Our confusion matrix shows an accuracy of 89.82%, with an error rate of 10.18%, with wrongly classified values of 29+16 = 45 and correctly classified values of 198 + 199 = 397.





### [Project 6: SQL Sales Target Analytics]
#### Loading and querying the dataset
![orders ](https://github.com/sirskin01/try01/assets/144762826/409469e6-8da7-4aeb-8430-b34d549ec8bb)

![order_det](https://github.com/sirskin01/try01/assets/144762826/e62df1ee-55a3-4f34-94d8-d04dc42c4204)

![sales_tar](https://github.com/sirskin01/try01/assets/144762826/a3276993-c6d7-4cc0-9da0-88f689cb9d10)

#### Question 1:
![Q1](https://github.com/sirskin01/try01/assets/144762826/d71180fd-7071-4bf9-a0c1-2a4beca9fcfb)

#### Question 2:
![Q2](https://github.com/sirskin01/try01/assets/144762826/8978a04d-36fb-4327-8f5f-df8d7e337361)

#### Question 3:
![Q3](https://github.com/sirskin01/try01/assets/144762826/b7522a22-37a2-4845-ac68-c830043870d8)

#### Question 4:
![Q4](https://github.com/sirskin01/try01/assets/144762826/38bbe9b2-e142-4bd9-bae2-96c125b14118)

#### Question 5:
![Q5](https://github.com/sirskin01/try01/assets/144762826/0ef89d65-db2b-4636-8bcd-eb2d42ffa6dc)

#### Question 6:
![Q6](https://github.com/sirskin01/try01/assets/144762826/038c614f-66ec-4bce-891d-38927d1277db)

#### Question 7:
![Q7](https://github.com/sirskin01/try01/assets/144762826/0c2a20a7-cde5-4bf9-b06c-1dd288005acb)

##### In conclusion, Archer Hort is the customer with the highest order greater than $1000. In terms of profit, the southern region has the highest maximum profit and France has the highest total sales from all countries.

<h3> 🤳 Connect with me:</h3>
[LinkedIn]www.linkedin.com/in/chrisemezie

