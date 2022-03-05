
# Analysis-of-Google-Playstore-Apps-for-App-Development
This is an analysis of 2.3 million apps on Google Playstore. The analysis results are essential for an app developer looking to develop a potentially successful app. 
It looks into the various features of a successful app ( more than 1 million installs and rating 4.0 to 5.0) and explore the 
optimal business model of an app based on user behaviour through ratings and install numbers. This allows an app developer to understand the google playstore market and 
set the nature and direction of the app that he/she might want to build.  

The dataset used in this analysis is obtained through Kaggle , contributed by author Gautham Prakash. (https://www.kaggle.com/gauthamp10/google-playstore-apps) The raw dataset consists of 24 columns and 2.3 million rows, obtained through web-scraping and accurate as of June 2021.

There are many interesting columns that we can explore in the dataset, such as the App Size, Installs, Privacy Policy and App Price. However, for the purpose of this analysis, we will refer to mainly two columns as the metrics to measure an application's success - Rating and Installs/Minimum Installs. In this analysis, a successful application is defined to have high ratings (4.0 - 5.0) and high installation numbers( > 1 million installs).

**The goals to be addressed are:**

**1. How do the features of an application affect its success?**

a) What are the top app categories in the market?

b) How do the ratings and install numbers differ between the application categories? 

c) How does the application price influence the application rating and installation numbers? 

d) How does the application size influence the application rating and installation numbers?

e) What is the optimal minimal android system supported for an application to achieve high ratings and high installation numbers?

f) Would a well-maintained application achieve higher ratings and installation numbers?

g) What is the most popular content rating for successful applications? 

h) Does having a privacy policy enhances the success of an application? 

i) How does being listed as an Editor's Choice affect the success of an applications? 

j) Are there applications with high installs and yet low ratings , translating to possible user disappointment?

**2. What is an optimal business model of a successful application?**

 a) Are successful applications usually free or paid ? 

 b) How do ad-supported applications and applications with in-app purchases differ in terms of ratings and installation numbers?
 
 
**The flow of this analysis is as follow:**

1. Basic data exploration and preparation
2. Data cleaning and data wrangling
3. Univariate exploration
4. Bi-variate and multi-variate exploration to address our goals
5. Recommendation for App Development
 
## Recommendation for App Development
From this analysis, we can gather some insights for the initial stage of an app development process. This will help to set the direction for the nature of the app that we would like to develop. To achieve the goal of an app having high installs (More than 1 million) and good rating performance ( 4.0 to 5.0), the app should ideally be:

1. Free
2. Standard app size <16
3. Content rating for the general population (Everyone/Everyone 10+)
4. Runs on minimal android system of 4.4 /5.0
5. Well-maintained and updated at least once every 5 months
6. Be an Editor's Choice
7. Includes a privacy policy especially for categories like Tools, Entertainment, Education and Music where collection of personal and financial information is common


**App categories worth looking into:**

1. Education
2. Music
3. Books & Reference
4. Lifestyle
5. Productivity
6. Business

These app categories tend to garner better rating performances.

Although Tool apps are heavily used daily and tend to have high installs and rating counts, users are more critical and likely to give poor ratings when a slight lag or bug disrupt user experience. As observed from the analysis, Tool and Entertainment apps are more inclined to cause user disappointment. Therefore, Tool and Entertainment apps can be avoided unless large amount of resources can be set aside for app maintenance and app performance.

**Lastly, the optimal business model for monetization can be:**

1. Free apps
2. Includes in-app purchases
3. Includes in-app ads
Having in-app ads is not a deal-breaker for users and they are more likely to download free apps with in-app ads and more willing to spend on in-app purchases than paid apps.
 
 
 

Link to Plotly boxplot for slide 20 
https://drive.google.com/file/d/1Xk_HrzTgfBxu5URfnT2XaODJdWTBpm6e/view?usp=sharing



## Acknowledgements

 - [Source of Dataset](https://www.kaggle.com/gauthamp10/google-playstore-apps)
 
## Authors

- [@siewpingyeo](https://github.com/SiewPingYeo)


## Built With

    1. Numpy
    2. Pandas 
    3. Seaborn
    4. Matplotlib
    5. Plotly 






## Documentation

[Documentation](https://linktodocumentation)


## Feedback

If you have any feedback, please reach out to us at yeosiewping@gmail.com


# Hi, I'm Siew Ping! 👋


## 🚀 About Me
I'm a an aspiring data analyst, looking forward to tell more stories of the past, present and future.


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siew-ping-yeo-453b8368/)



👩‍💻 I'm currently working on...

🧠 I'm currently learning Python, SQL, R and Machine Learning

💬 Ask me about...

📫 How to reach me
yeosiewping@gmail.com

## 🛠 Skills
Python, R, SQL 


## Lessons Learned

I have learned a lot about data cleaning, wrangling and data visualisation from this project. It has exposed me to the rigour of critical thinking during the EDA needed for the analysis. 
These skills will be useful in future EDA and machine learning projects which I am looking forward to embark on. 
