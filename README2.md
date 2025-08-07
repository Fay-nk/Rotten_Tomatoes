# Second project: 🎬 Genre Analysis Dashboard

📊 **Power BI Dashboard | Rotten Tomatoes Dataset | Data Analysis & Visualization Project**

## 📌 Overview
This interactive Power BI dashboard analyzes the relationship between movie genres and critical/audience reception using Rotten Tomatoes data. Designed for use by production studios, streaming platforms, and content strategists, the dashboard delivers deep genre-level insights across three core dimensions:
1. Audience vs. Critic Rating Alignment
2. Volume & Quality Distribution by Genre
3. Top-Performing Genres Based on Average Ratings

---

## 🎯 Problem the Dashboard Solves
In the film and streaming industry, understanding which genres consistently perform well and how audience preferences align (or misalign) with critic reviews is critical. Studios often produce content based on assumptions or trends, which can lead to misaligned investments.
This dashboard offers data-driven insight to:
- Identify genres with loyal audiences despite lower critic ratings.
- Detect genres prone to critical acclaim or failure.
- Support content investment and marketing decisions using real-world trends.

---

## 💼 Business Value
**✅ Strategic Content Investment**
Helps executives and production teams prioritize genres with high average tomatometer scores to improve ROI.
**✅ Audience-Centric Marketing**
Reveals genres with strong audience loyalty, even if critic scores are mediocre—perfect for fan-first marketing campaigns.
**✅ Portfolio Risk Management**
Identifies high-risk genres with a large number of poorly reviewed films, allowing studios to allocate budget more wisely.
**✅ Reputation Optimization**
Helps streaming platforms and content curators focus on genres that enhance perception of quality and retain subscribers.

---

## 🧠 Dashboard Breakdown

###🔹 1. Audience Rating vs. Tomatometer Rating by Genre (Line Chart)
**Purpose:**
To visualize how audience sentiment aligns or contrasts with critic ratings across various genres.
**Method:**
- Aggregated total audience and tomatometer scores by genre.
- Used a line chart to track audience approval across the tomatometer spectrum (0–100).
- Compared multiple genres on the same scale.
**Key Insights:**
- Genres like Action & Adventure and Drama dominate audience engagement, especially with critic ratings in the 70–95 range.
- Some genres like Anime maintain strong audience support despite low critic scores, signaling fan-driven appeal.
- Studios can safely invest in audience-favorite genres even without critical backing.

###🔹 2. Movie Volume by Genre & Tomatometer Status (Stacked Bar Chart)
**Purpose:**
To identify which genres consistently receive Certified Fresh, Fresh, or Rotten ratings.
**Method:**
- Grouped films by genre and rating status (Certified Fresh, Fresh, Rotten).
- Counted total movies per genre per category.
- Visualized using a horizontal stacked bar chart.
**Key Insights:**
- Drama is the most common genre but has a high volume of Rotten-rated movies, indicating oversaturation or variability in quality.
- Comedy and Action & Adventure also show significant Rotten portions.
- Niche genres like Documentary and Art House have higher success rates in critical reception.
- Romance consistently underperforms in critic ratings.

###🔹 3. Top Genres by Average Tomatometer Rating (Bubble Chart)
**Purpose:**
To highlight the genres that receive highest average critic scores, helping inform investment strategies.
**Method:**
- Cleaned and prepped Rotten Tomatoes dataset.
- Calculated average tomatometer rating per genre.
- Displayed in a bubble chart:
             - Size: Volume of critic ratings
             - Position: Average score
             - Color: Genre differentiation
**Key Insights:**
- Drama leads with high average critic score and large review volume (551.67K), proving both quality and impact.
- Comedy and Mystery follow, suggesting reliability and consistent critical performance.
- Action has lower average scores, suggesting critic skepticism despite likely popularity.

---

## 📊 Key Metrics Visualized
- 📈 Average Tomatometer Rating
- 👥 Total Audience Rating
- 🎞️ Number of Movies per Genre
- 🏆 Tomatometer Status Breakdown (Certified Fresh, Fresh, Rotten)
- 🔄 Genre Trends Across Rating Spectrum

---

## 📂 Tools Used
- Power BI (Dashboard design & visual analytic
- DAX (Data modeling, calculated columns, and KPIs)
- Excel/CSV (Raw data processing)
- Rotten Tomatoes Dataset (Publicly available)

---

##📌 How to Use This Dashboard
1. Filter by Genre to explore specific trends.
2. Hover on Line Graph to view how audience ratings shift with critic ratings.
3. Review Stacked Bar Chart for insight into quality consistency by genre.
4. Analyze Bubble Chart to prioritize high-ROI genres in content planning.

---

## 🚀 Conclusion
This dashboard delivers actionable insight into how genres perform both in terms of volume and quality, with a dual lens of critic and audience perception. It's a must-have tool for content teams, production houses, and platform curators in the age of streaming competition and media abundance.
