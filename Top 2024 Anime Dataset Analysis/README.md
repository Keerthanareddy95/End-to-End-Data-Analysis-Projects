# Top-2024-Anime-Dataset-Analysis 🍥
This project focuses on the anlaysis and exploration of the Top Anime relsead in 2024!

## About the Data Set 📑
Data set is taken from : [https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/](https://www.kaggle.com/datasets/bhavyadhingra00020/top-anime-dataset-2024)
- **Attributes :** 22 features
- **Size :** 1000 rows * 22 columns

### 🚀Project Stages

1. **Data Cleaning:** 🫧
   - Processed and cleaned the dataset to ensure consistency and remove any inconsistencies or missing values.
   - Total Number of missing values found in various columns ->
                                                               Demographic - 479, Broadcast - 431, Premiered - 431, Synonyms - 291, Genres - 229, English - 141
   - Handled all the columns with Null values appropriately, according to their data types.
   - Used various practices such as dropping the rows or unnecessary columns, imputation and much more.
   - Size of Dataset after cleaning - 435 rows * 19 columns

 2. **Exploratory Data Analysis (EDA):** 📈
   - Conducted thorough EDA to gain insights into the distribution of features, relationships, and patterns within the cleaned data.
   - Visualized the features to get some key insights and identify patterns within the data ->
   - **Plot Showing the top 10 anime based on their ranking -**
     
     ![1](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/98d6b7ae-602c-4142-92aa-dbb5a68488fa)
     
     Here are the top 10 animes displayed based on their ranking and score, with Frieren on the top..!

   - **This lineplot shows the number of animes released over the years -**
     
     ![2](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/07c7c1c8-7609-4c93-8c9a-e470a073e659)
     
     We can observe a sharp rise in the number after 2020 which signifies the current popularity of anime across all the age groups and genres.

   - **Bar Plot to show the top 10 anime producers -**
     
     ![3](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/22c6b524-ad3d-40f1-8754-e019dc0ba986)
     
     This graph clearly describes that the top producer is Shueisha calucalted based on the number of anime they released !

   - **Scatter plot of Members vs. Popularity -**
     
     ![4](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/9f34b9de-c5ba-436c-9edb-70aa9d69023e)

     This plot shows that the animes having more number of associated members have the most popularity and we can also observe a clear pattern among the relationship 
     between the number of associated memebers and popularity of the anime.

   - **Count Plot to show the distribution of Anime Types -**
     
     ![5](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/ab3b4655-b80f-4c1f-8f61-53335a6aba1b)

     This plot shows that most of the animes released, belong to the category of "TV" and least number of them belong to the "Special" category!

   - **Bar Plot to show the Top 10 Anime Genres -**
     
     ![6](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/6171c88e-3395-446a-8301-dddd3c8ae1f3)

     This plot clearly describes that the most commom genre based on the number of anime released is *Action* and the top 10 genres include Adventure, Fantasy, Drama, 
     Romance, Supernatural, Mystery, Sci-Fi and Suspense..!!

   - **Pie Chart to visualize the ratings -**
     
     ![7](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/880015ca-36e5-4b7e-9f3c-1f83168760fd)

     This pie chart Visulaizes and gives a summary that PG-13 - Teens or older category of animes have the highest ratings and thus, are most popular among the audience!

   - **Stacked Bar Chart to show the Status -**
     
     ![8](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/5f8e4200-cf5f-4f55-8908-6fa227c51a79)

     This stacked bar graph describes the status of the animes based, which are classified based on their type.

   - **Scatter plot of Score vs. Popularity -**
     
     ![9](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/71c0daa0-997a-4fc6-bd5e-a6bb399802a2)

     This plot shows that, the anime with lower score (rating) , tend to have lesser popularity as many data points are scattered towards larger ranking number.

   - **Histogram to display the frequency of scores -**
     
     ![10](https://github.com/Keerthanareddy95/End-to-End-Data-Science-Projects/assets/123613605/d222bbe5-2c4d-4296-9c3b-fa26c63b20bf)

     This distribution shows most of the animes released have an average rating between 7.8 and 8.2..!


## Tools and Libraries Used 🔎

- Google Colab 
- Pandas, NumPy, Matplotlib, Seaborn for data manipulation and visualization 📊










     

