# 📊 LinkedIn Job Trend Analysis (Web Scraping)

## 📌 Overview  
This project scrapes LinkedIn job postings to analyze **skill demand trends** across cities and roles. Using Python, BeautifulSoup, Pandas, and Seaborn, we extract job-related data (titles, skills, locations), clean it, and generate insights through heatmaps and skill–role matrices.  
The goal is to help **job seekers, recruiters, and training providers** identify where certain skills are in demand and how they align with different job roles.  

---

## 🛠 Tools & Libraries  
- **Python** – Programming language  
- **BeautifulSoup (bs4)** – Web scraping  
- **Pandas** – Data cleaning & analysis  
- **Matplotlib / Seaborn** – Data visualization  
- **Excel (Optional)** – Exporting processed data  

---

## 🚀 Steps Involved  
1. **Scraping Job Postings**  
   - Extract job titles, locations, and skills using BeautifulSoup.  
   - Handle pagination if needed.  

2. **Data Cleaning**  
   - Remove duplicates and missing values.  
   - Parse and standardize skill tags.  

3. **Data Analysis**  
   - Count frequency of skills across cities.  
   - Build a **pivot table** to identify top 10 skills by city.  
   - Create a **skill vs role matrix** to see demand distribution.  

4. **Visualization**  
   - Heatmap of **Top 10 Skills by City**  
   - Heatmap of **Skill vs Role Matrix**  

---

## 📊 Key Deliverables  
- **Trend Analysis Visuals**  
  - `Skills by City.png` → Top 10 Skills by City  
  - `Skills by Role.png` → Skills vs Roles  

- **Insights**  
  - Cities with highest demand for specific skills  
  - Skills most associated with popular job roles  
  - Recommendations on emerging skills to learn  

---

## 🔮Conclusion
This project highlights how **web scraping + data visualization** can be used to track **real-world job market trends.**
The insights can help in:
- Career planning (job seekers)
- Hiring strategies (recruiters)
- Course design (training providers)  
