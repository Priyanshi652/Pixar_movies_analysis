# Pixar_movies_analysis

# 🎬 Pixar Movie Ratings Dashboard – Power BI Project

## 📌 Overview  
This project was built as part of the **Pixar Movie Ratings Challenge** by **Maven Analytics**. The objective was to analyze audience reviews, critic scores, sentiment trends, and financial performance across Pixar’s iconic filmography — and turn those insights into compelling, interactive visual stories using **Power BI**.

With three uniquely themed dashboards, this project uncovers what truly drives Pixar’s success — from emotional storytelling to box office timing and audience perception.

---

## 🎯 Project Goals (Expanded)

✅ **Centralize Disparate Data Sources**: Consolidate rating platforms, critic scores, box office data, and sentiment analysis into a unified model.

✅ **Uncover Rating Patterns Across Platforms**: Compare IMDb, Rotten Tomatoes, Metacritic, and Letterboxd to find consistent audience/critic behavior.

✅ **Evaluate Sentiment Trends**: Identify how emotionally charged films perform compared to others using sentiment polarity scores.

✅ **Analyze Financial Performance**: Understand ROI, budget-to-profit dynamics, and revenue trends across years and countries.

✅ **Genre & MPAA Strategy Insights**: Break down performance by genres and ratings to see which categories deliver highest critical & commercial success.

✅ **Design for Storytelling**: Create 3 clean, visually intuitive dashboards that communicate insights in a business-ready format.

---

## 🧰 Tech Stack
**Power BI** – Main visualization and reporting tool
**DAX (Data Analysis Expressions)** – For calculated KPIs, measures, and interactivity
**Power Query** – Used for data shaping, cleaning, merging, and transformation

---

## 🔍 Dataset  
The dataset was provided by Maven Analytics, containing information on:  
- Title, release year, genre, runtime, box office metrics (domestic, worldwide, budget, profit)  
- Audience scores from IMDb, Rotten Tomatoes (audience), Letterboxd  
- Critic scores from Rotten Tomatoes (critics), Metacritic  
- Sentiment polarity from review text analysis  
- CinemaScore & MPAA ratings

  ---

## 📊 Project Structure & Steps

### 1. **Data Transformation**
- Removed nulls and inconsistent fields  
- Unified naming conventions and formats for all movie details  
- Parsed columns for MPAA rating, release year, and platform-based scores  

### 2. **Data Modeling**
- Built star schema with a central 'Movies' table and related dimensions  
- Created DAX measures for:
  - Avg Sentiment Score
  - Avg Ratings per Platform
  - ROI %
  - Score Distribution by Genre
  - Profit & Revenue Insights


### 3. **Dashboard Design**
Created **3 distinct Power BI layouts** with the following focus areas:

---

## 🧠 Dashboard 1: **Ratings & Sentiment Analysis**

**Focus Areas:**
- IMDb, Rotten Tomatoes, Metacritic, Letterboxd ratings  
- CinemaScore distribution  
- Sentiment polarity from review text

**Key Insights:**
- 🎯 **High IMDb Ratings = High Engagement**: Titles rated above 8.0 on IMDb saw 2–3x the user reviews  
- 🍿 **CinemaScore A+ titles average 93% on Rotten Tomatoes**, showing strong critic-audience alignment  
- 🧠 **Emotionally driven titles (e.g., *Inside Out*, *Up*) scored 0.9+ in sentiment polarity**

---

## 🎥 Dashboard 2: **Financial & Performance Analysis**

**Focus Areas:**
- Budget, profit, ROI, worldwide vs domestic performance  
- Film-wise revenue breakdown  
- High vs low performing titles  

**Key Insights:**
- 💰 **Average ROI across all movies was 291.69%**, peaking in years like 1995, 2004, 2023  
- 🌍 **Worldwide revenue hit $17B+**, with many films performing better globally than in the US/Canada  
- 💸 **The Good Dinosaur had high production costs but poor profit returns**, showing that budget doesn’t guarantee success


## 🎭 Dashboard 3: **Genres, Categories & Release Strategy**

**Focus Areas:**
- Genre analysis by sentiment and rating  
- Runtime and release month effect on scores

**Key Insights:**
- 🗓 **June releases saw Metacritic scores >78**, suggesting summer release timing improves critical reception  
- 🎬 **G & PG-rated films dominate Pixar’s catalog**, aligning with their family-first brand image  
- ⏱ **Runtime sweet spot lies between 90–120 minutes** for most engaging films

---

## ✅ Recommendations

🎯 **Prioritize Summer (June-July) Releases**
Leverage proven seasonal timing where reviews and performance peaked.

❤️ **Invest in Emotionally-Driven Storytelling**
Sentiment analysis shows a clear preference and higher engagement for character-led narratives.

🎞 **Improve Performance in Non-G/PG Categories**
Explore creative experimentation in PG-13 or hybrid genres to expand audience reach.

📣 **Use High-Performers for Marketing Campaigns**
IMDb traction and review volume suggest using top-rated films for cross-platform engagement strategies.

🧪 **Conduct Post-Release Sentiment Tracking**
Monitor viewer sentiment polarity week-by-week to understand perception shifts and plan sequels/merchandise.

💡 Analyze Underperforming Films in More Detail
Look beyond ROI: were there gaps in audience targeting, storytelling, or market saturation?

---

## 🎯 Final Takeaway  
Pixar's magic formula? A combination of **emotional storytelling, strategic release timing, and data-backed creative decisions**. This project showcases how analytics isn't just about numbers — it's about **revealing the soul behind stories**.

---

## 🧠 What I Learned  
- Gained strong hands-on experience with **DAX** for sentiment-driven KPIs and calculated insights  
- Understood the **value of layout consistency** across dashboards to tell a story in phases  
- Learned how to **balance visual design and analytical depth** for stakeholder-ready storytelling  
- Honed skills in **cleaning real-world, multi-dimensional datasets** for business analysis


## 🙌 Acknowledgments  
Big thanks to **Maven Analytics** for hosting this incredible challenge. Platforms like these help aspiring analysts turn raw data into meaningful impact — and inspire creativity with real-world business storytelling.
