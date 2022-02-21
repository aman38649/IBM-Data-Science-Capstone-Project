# IBM-Data-Science-Capstone-Project
In this capstone, we had to predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.


Collected data from public SpaceX API and SpaceX Wikipedia page. Created labels  column ‘class’ which classifies successful landings. Explored data using SQL,  visualization, folium maps, and dashboards. Gathered relevant columns to be used as  features. Changed all categorical variables to binary using one hot encoding.  Standardized data and used GridSearchCV to find best parameters for machine learning  models. Visualize accuracy score of all models.


Four machine learning models were produced: Logistic Regression, Support Vector  Machine, Decision Tree Classifier, and K Nearest Neighbors. All produced similar results  with accuracy rate of about 83.33%. All models over predicted successful landings. More  data is needed for better model determination and accuracy.

![image](https://user-images.githubusercontent.com/41456447/154999630-825bc7c6-47b8-42eb-bfac-993dc558a73b.png)


Steps taken throughout this project
1. Data collection : Combined data from SpaceX public API and SpaceX Wikipedia page
2. Perform data wrangling
3. Perform exploratory data analysis (EDA) using visualization and SQL
4. Perform interactive visual analytics using Folium and Plotly Dash
5. Perform predictive analysis using classification models





