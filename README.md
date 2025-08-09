
# 📊 Netflix Movies and TV Shows Analysis

## **📌 Aim**

The aim of this project is to analyze the Netflix dataset to uncover **content trends, patterns, and insights** using Excel's **Pivot Tables, Charts, and Dashboard features**.
The project focuses on answering key business questions such as:

* What is the distribution of Movies vs TV Shows on Netflix?
* Which countries contribute the most titles?
* What are the most popular genres and ratings?
* How has content addition changed over time?
* Are there seasonal trends in content releases?

---

## **📂 Dataset**

* **Source:** [Netflix Titles Dataset (Kaggle)](https://www.kaggle.com/shivamb/netflix-shows)
* **Total Rows:** 8,780
* **Columns:**

  * show\_id
  * type (Movie / TV Show)
  * title
  * director
  * cast
  * country
  * date\_added
  * release\_year
  * rating
  * duration
  * listed\_in (Genres)
  * description

---

## **⚙️ Process**

### **1. Data Cleaning**

Performed in **Excel** using Power Query and manual edits:

* Removed duplicate rows.
* Deleted irrelevant or corrupted entries (e.g., numbers in the "title" column).
* Handled missing values:

  * Filled blanks with “Unknown” for `country` and `director`.
  * Removed blank rows for critical analysis columns.
* Split and trimmed text (e.g., cast column).
* Standardized date formats and extracted month/year from `date_added`.

### **2. Data Transformation**

* Converted `duration` into **two categories**: minutes (movies) and seasons (TV shows).
* Extracted **month** for seasonal trend analysis.
* Grouped genres from the `listed_in` column.

### **3. Pivot Table Analysis**

Created Pivot Tables to analyze:

1. Movies vs TV Show distribution
2. Titles added over time (Yearly Trend)
3. Top 4 countries by number of titles
4. Top 5 actors by number of titles
5. Top 5 genres on Netflix
6. Distribution of ratings
7. Average duration of Movies vs TV Shows
8. Monthly content additions

### **4. Visualization & Dashboard**

* Combined all pivot tables with relevant charts:

  * Pie chart (Movies vs TV Shows, Ratings distribution)
  * Bar chart (Top genres, Top countries)
  * Line chart (Titles over time, Monthly additions)
  * Card visuals (Total Titles, Movies, TV Shows, Unique Countries)
* Designed a **clean, professional dashboard** in Excel.

---

## **📈 Key Insights**

1. **Content Mix**

   * **Movies:** 70% (6,110 titles)
   * **TV Shows:** 30% (2,670 titles)

2. **Top Countries**

   * 🇺🇸 United States: 3,202 titles
   * 🇮🇳 India: 1,004 titles
   * 🇬🇧 UK: 628 titles
   * Unknown origins: 830 titles

3. **Genres**

   * Top 3: Dramas, Comedies, Action & Adventure.
   * Dramas dominate with 1,592 titles.

4. **Ratings**

   * TV-MA (Mature Audience) dominates at 46% of all titles.

5. **Duration**

   * Average Movie length: \~100 mins
   * Average TV Show length: \~2 seasons

6. **Trends**

   * Peak content additions in 2018–2020.
   * Decline in new content after 2020.

7. **Seasonality**

   * December has slightly higher content additions, suggesting holiday release strategies.

---

## **💡 Recommendations**

1. **Fill Missing Data**

   * Reduce “Unknown” values for better decision-making.

2. **Balanced Content Portfolio**

   * Introduce more family-friendly content to diversify audience reach.

3. **Leverage Seasonal Peaks**

   * Use December’s higher engagement for blockbuster releases.

4. **Expand Genre Diversity**

   * Add more niche genres to attract specific audiences.

5. **Country Focus**

   * Explore opportunities in emerging content-producing countries.

---

## **🛠 Tools Used**

* Microsoft Excel (Pivot Tables, Pivot Charts, Power Query, Dashboard)

---

## **📎 Files in This Repository**

* `netflix_titles_cleaned.xlsx` → Cleaned dataset
* `netflix_dashboard.xlsx` → Interactive Excel dashboard
* `README.md` → This documentation


---

## **📌 Conclusion**

This analysis shows that **Netflix heavily invests in movies over TV shows**, with a strong emphasis on mature content and dominant contributions from the United States and India. Seasonal and yearly patterns provide opportunities for better release planning.

