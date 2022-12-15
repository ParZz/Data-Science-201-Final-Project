# Data-Science-201-Final-Project

## Authors: Yan Tian, Nicholas Chiappinelli, Haojie Ge, Johnny Luis, Shuran Wang



### Link to the tutorial video: 

### Link to the professional presentation video: 

### Link to the Colab file which contains all steps of data science process: https://colab.research.google.com/drive/1T45u4wlltSvrkunCWOOIauEWC6GdgwGY?usp=sharing

### Link to the project page: 



#### A brief introduction to the project:

In this project, we are trying to use knowledges we learned in class to  briefly analysis the German credit risk dataset and make a machine learning model to evaluate the risk level of clients. We include a tutorial that will walk users through the entire data science process: Business Understanding>Data Understanding> Data Preparation> Modeling+ Evaluating (EDA+ Machine Learning Model Training)>Deployment. The objective is to gain actionable insights about what factors can impact the evaluation of credit risk level of certain clients, and use this knowledge to prototype reliable machine learning algorism in classifying the risk standing of those who are going to open a loan.





#### Important Findings from EDA and ML:
<img width="1031" alt="Screen Shot 2022-12-15 at 16 46 40" src="https://user-images.githubusercontent.com/119345143/207974154-02ab214f-df43-4031-b2b4-588c1af47f15.png">
The strongest correlations exist between credit amount and duration in month, as well as between credit history and the number of existing credits at this bank, which makes sense because bank accounts and number of credits generally accrue in value over time. We can also see that not a lot of the variables have very high correlations. Still, we can find some relationships have approximately r= ~ .25, and we investigated those in hopes of finding insightful patterns among different attributes which might contribute to good or bad credit evaluation.

<img width="1009" alt="Screen Shot 2022-12-15 at 16 48 29" src="https://user-images.githubusercontent.com/119345143/207974408-5c5ca192-ac2b-4a1b-ba4b-8efe3bdf93a5.png">

<img width="525" alt="Screen Shot 2022-12-15 at 16 49 01" src="https://user-images.githubusercontent.com/119345143/207974476-31202b76-4447-4f7e-94ad-a88a9af365e7.png">
<img width="293" alt="Screen Shot 2022-12-15 at 16 49 16" src="https://user-images.githubusercontent.com/119345143/207974518-8bdbecff-d4b3-46d7-9b46-de23ecaf716d.png">
From the graph we can see that the dataset has a larger proportion of cases that are foreign workers. And according to the table we got, foreign workers have a higher possibility to be evaluated as a bad risk.

<img width="516" alt="Screen Shot 2022-12-15 at 16 50 36" src="https://user-images.githubusercontent.com/119345143/207974694-a9ffdcd6-6b06-4955-994f-377cdcd577bd.png">
<img width="242" alt="Screen Shot 2022-12-15 at 16 50 49" src="https://user-images.githubusercontent.com/119345143/207974713-7c2a5f18-2064-404b-987f-d5f4694e1c39.png">
From the graph we can see that a majority of cases in the dataset are single male, with some divorced/separated/married female, and a smaller proportion are composed of divorced/separated male and married/widowed male. And there is no single female in our dataset. From the table we can see that, compared to those of divorced/separated/married female and divorced/separated male groups, a larger proportion of cases in single male and married male groups are considered to be in the good risk group (vs. the bad risk group). This suggests that divorced/separated/married females and divorced/separated males are more likely to hold good credit risk compared to the other two groups.

<img width="518" alt="Screen Shot 2022-12-15 at 16 51 37" src="https://user-images.githubusercontent.com/119345143/207974834-2f2b7cac-aea9-4101-adcb-8f596ce20bf3.png">
<img width="1035" alt="Screen Shot 2022-12-15 at 16 51 51" src="https://user-images.githubusercontent.com/119345143/207974867-89caa0ed-a35b-40ba-914b-f51293d93f9e.png">

<img width="1018" alt="Screen Shot 2022-12-15 at 16 52 04" src="https://user-images.githubusercontent.com/119345143/207974905-2aaa7845-22d3-470f-a436-8bc59ccb0a77.png">
<img width="996" alt="Screen Shot 2022-12-15 at 16 52 16" src="https://user-images.githubusercontent.com/119345143/207974929-7be33ee5-0680-4fac-8e24-21bebb8f9b3e.png">

<img width="1027" alt="Screen Shot 2022-12-15 at 16 52 29" src="https://user-images.githubusercontent.com/119345143/207974970-a679d821-ad64-40f1-9bab-731ff9a090ac.png">

<img width="1032" alt="Screen Shot 2022-12-15 at 16 52 42" src="https://user-images.githubusercontent.com/119345143/207974992-65978f8f-b29c-4808-857e-c9be727d0d87.png">

<img width="1016" alt="Screen Shot 2022-12-15 at 16 52 54" src="https://user-images.githubusercontent.com/119345143/207975028-80dcf49d-3621-4ae5-a52a-eeb8b2c07df7.png">

<img width="943" alt="Screen Shot 2022-12-15 at 16 53 40" src="https://user-images.githubusercontent.com/119345143/207975190-107f3049-c7ea-435a-a286-96adfa12170f.png">
