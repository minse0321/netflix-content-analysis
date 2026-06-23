# 🎬 Netflix Content Data Analysis
> Analyzing 9,827 Netflix titles to uncover what drives content quality and platform strategy.

## 📌 Project Overview
With the rapid growth of the OTT market, this project explores what makes content succeed on streaming platforms. By analyzing genre ratings, language trends, production volume, and popularity patterns, the analysis delivers data-driven strategic insights for OTT decision-makers.

## 📂 Dataset
| Item | Detail |
|------|--------|
| **Source** | Kaggle – Netflix Movies and TV Shows |
| **Size** | 9,827 rows |
| **Period** | Analysis conducted: June 2026 |
| **Key Variables** | `title`, `type`, `genres`, `original_language`, `release_year`, `imdb_score`, `imdb_votes`, `popularity` |

## 🛠 Tech Stack
| Tool | Usage |
|------|-------|
| **Python (Google Colab)** | Data loading, missing value handling, duplicate removal, dtype conversion |
| **Pandas** | Filtering, groupby aggregation, EDA |
| **Tableau** | 4-chart interactive dashboard — genre rating/count, language comparison, content trend, popularity scatter |

## 📊 Dashboard
![Netflix Content Analysis Dashboard](./dashboard.png)
> Genre Avg Rating vs Count · Content Trend by Year · Popularity vs Vote Average · Avg Rating by Language

## 🔍 Key Insights
### 1. High-Quality Niche Genres — Documentary & Music Lead in Ratings
- **Documentary** and **Music** ranked #1 and #2 in average IMDb rating (~7.0+)
- Despite lower production volume, these categories deliver consistently high viewer satisfaction
- **Drama** dominates in volume (3,200+ titles) but falls below the overall rating average — quantity does not equal quality

### 2. K-Content Outperforms All Languages
- **Korean-language content** achieved the **highest average rating (7.2/10)** across all original languages
- Ranked above Japanese, Hindi, Spanish, Chinese, French, and English
- Notably, English-language content — the most abundant on the platform — recorded the **lowest average rating**

### 3. Popularity ≠ Quality
- The **Popularity vs Vote Average** scatter plot shows no clear positive correlation
- High-popularity genres (Action, Animation, Crime) cluster around moderate ratings
- Niche genres (Documentary, Music, War, Mystery) maintain high ratings despite low popularity scores

### 4. Post-Pandemic Production Recovery
- Content production peaked around **2015–2016**, then declined sharply in **2020** due to COVID-19
- A clear **recovery trend began in 2022**, with volume rebounding toward pre-pandemic levels

## 💡 Strategic Recommendations
| Strategy | Rationale |
|----------|-----------|
| **Invest in niche, high-rating genres** | Documentary & Music punch above their weight in satisfaction despite low volume |
| **Double down on K-content** | Highest average rating across all languages; proven global IP with premium perception |
| **Decouple popularity from editorial strategy** | Trending content drives short-term buzz; high-rated niche content drives long-term retention |
| **Rebuild post-pandemic pipeline** | 2022+ recovery window is an opportunity to lock in catalog diversity before competition intensifies |

## 📁 Repository Structure
```
netflix-content-analysis/
├── README.md
├── dashboard.png
├── netflix_analysis.ipynb    # Data cleaning & EDA (Google Colab)
└── data/
    └── netflix_data.csv      # Source: Kaggle
```

## 👤 Author
**Minse** · [GitHub @minse0321](https://github.com/minse0321)
Business Administration, Gachon University
Aspiring Data Analyst | MSBA Candidate (Fall 2027)
