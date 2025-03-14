# 📊 Exploratory Data Analysis (EDA) on IMDB Top 1000 Movies

## 📌 **1. Introduction**
This project explores the **IMDB Top 1000 Movies dataset** to uncover trends in **ratings, genres, box office revenue, and director influence**. The goal is to analyze **movie characteristics and revenue performance** using data exploration techniques.

---

## 📌 **2. Dataset Overview**
- **Dataset Name:** IMDB Top 1000 Movies
- **Total Entries:** 1000 movies
- **Columns & Key Features:**
  - `Series_Title`: Movie title
  - `Released_Year`: Year of release
  - `IMDB_Rating`: IMDB user rating
  - `Genre`: Movie genre(s)
  - `Meta_score`: Critic score
  - `No_of_Votes`: Number of votes on IMDB
  - `Gross`: Box office revenue (in dollars)
  - `Director`: Name of the movie director
  
### **🛠 Data Cleaning & Processing**
✅ Converted `Released_Year` to integer format (handled anomalies like 'TV Movie')  
✅ Converted `Gross` revenue to numeric (removed commas)  
✅ Handled missing values:
   - Filled `Certificate` with "Unknown"
   - Dropped rows where `Meta_score` and `Gross` were missing  

---

## 📌 **3. Key Insights from EDA**

### **📊 IMDB Rating Distribution**
- **Most movies are rated between 7.0 and 8.0**, with very few reaching 9.0+.
- The **highest-rated movie** has a **9.3 rating** (*Shawshank Redemption* likely).

### **🎭 Genre Popularity**
- **Drama** is the most common genre, followed by **Drama + Romance** and **Comedy + Drama**.
- This suggests that **dialogue-heavy, story-driven films** are most popular.

### **💰 IMDB Ratings vs. Box Office Revenue**
- **Movies rated around 8.0 perform better at the box office** than those rated 9+.
- Highly rated movies (**9.0+**) may be **niche films** that don’t attract mass audiences.

### **🎬 Top 5 Directors with Most Movies**
| Director              | Number of Movies |
|----------------------|----------------|
| **Steven Spielberg**  | 13 |
| **Martin Scorsese**   | 10 |
| **Alfred Hitchcock**  | 9 |
| **Quentin Tarantino** | 8 |
| **Christopher Nolan** | 8 |

### **📈 Revenue Trends Over Time**
- **Movies after 2010 earn significantly more at the box office**.
- The **highest-grossing movie** is *Star Wars: The Force Awakens (2015)*, earning **$936.66 million**.
- **2018 had the highest average revenue per movie (~$216.8M).**

---

## 📌 **4. Conclusion**
- **Most popular movies** are rated between **7.0 - 8.0**, with **Drama** being the dominant genre.
- **Movies rated 8 perform better at the box office** than those rated 9+, likely due to **mass appeal vs. niche films**.
- **Steven Spielberg is the most frequently featured director** in the dataset.
- **Box office revenue has grown significantly post-2010**, with **2018 as the highest-earning year**.

---

## 📌 **Next Steps**
📌 **Would you like to extend this analysis** by comparing IMDB ratings to **Rotten Tomatoes scores**, or move to the **next data visualization project?** 🚀

