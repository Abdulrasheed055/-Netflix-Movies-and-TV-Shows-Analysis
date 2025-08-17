
#  Netflix Movies and TV Shows Analysis

##  Aim 

The aim of this project is to analyze the Netflix dataset to uncover **content trends, patterns, and insights** using Excel's **Pivot Tables, Charts, and Dashboard features**.
The project focuses on answering key business questions such as:

* What is the distribution of Movies vs TV Shows on Netflix?
* Which countries contribute the most titles?
* What are the most popular genres and ratings?
* How has content addition changed over time?
* Are there seasonal trends in content releases?


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

##  Process 

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

Overall Content Overview
* Total Titles: 8,780

* Movies: 6,110 (70%)

* TV Shows: 2,670 (30%)

* Netflix offers more than twice as many movies as TV shows.

 * Content Growth Trends
Titles Added Over Time show a growth peak around 2019–2020, followed by a decline post-2020.

This suggests a possible shift in Netflix’s content strategy or reduced licensing/new productions after COVID-19 pandemic peaks.

##  Top Contributing Countries 
United States: 3,202 titles (largest contributor)

India: 1,004 titles

UK & Unknown origins make up the rest of the top four.

This indicates strong dominance of US-based content, but also growing representation from India.

## Popular Genres 
Top genres include Dramas, Comedies, Action & Adventure, Documentaries, and International TV Shows.

Dramas lead with 1,592 titles, suggesting strong viewer demand.

##  Ratings Distribution 
TV-MA (Mature Audience) content forms 46% of titles, followed by TV-14 (31%).
This indicates Netflix leans heavily toward adult and teenage audience content.

Actors with Most Titles
Shah Rukh Khan tops with 26 titles, followed by Akshay Kumar (23).

Strong presence of Bollywood actors aligns with India’s growing role in Netflix’s library.

Monthly Additions
The recent months show a slight downward trend in Monthly Content Additions, which may indicate slower expansion.

Average Duration
Movies: ~100 minutes

TV Shows: Average ~1–2 seasons

This reflects standard streaming content norms.

## Recommendations
 Balance Content Mix

Increase TV show production/acquisition to balance the current 70% movies vs. 30% TV shows split. TV shows often drive longer subscription retention.

Global Content Strategy

Continue expanding Indian and international content to appeal to diverse audiences.

Explore more African, Middle Eastern, and Latin American productions to tap into emerging markets.

Genre Expansion

Documentaries and International TV Shows are growing niches—invest more here to capture loyal, niche audiences.

## Target Younger Demographics

With 46% content being TV-MA, there’s room to produce more family-friendly and kids’ content to broaden audience base.

## Monitor Release Trends

Investigate why title additions dropped after 2020—this could be due to licensing costs, competition, or market saturation. Adjust release calendar to maintain engagement.

Leverage Star Power

Promote content with high-appearance actors (e.g., Shah Rukh Khan, Akshay Kumar) in marketing campaigns for regions with large fan bases.
## **🛠 Tools Used**

* Microsoft Excel (Pivot Tables, Pivot Charts, Power Query, Dashboard)

---

## ** Files in This Repository**

* `netflix_titles_cleaned.xlsx` → Cleaned dataset
* `netflix_dashboard.xlsx` → Interactive Excel dashboard
* `README.md` → This documentation


---

## ** Conclusion**

This analysis shows that **Netflix heavily invests in movies over TV shows**, with a strong emphasis on mature content and dominant contributions from the United States and India. Seasonal and yearly patterns provide opportunities for better release planning.

