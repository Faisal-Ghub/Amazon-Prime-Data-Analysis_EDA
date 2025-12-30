🔷 Project Title

Exploratory Data Analysis on Amazon Prime Movies & TV Shows
---
🔷 Business Problem (Crisp & Boardroom-Ready)

In a hypercompetitive OTT ecosystem, where content supply far exceeds demand, only a small fraction of titles achieve high ratings, popularity, and sustained audience engagement. Identifying the factors that differentiate high-performing content from low-performing content is critical for optimizing production decisions, maximizing ROI, and improving consumer satisfaction.
---
🔷 Business Objective

To identify data-driven patterns across genres, runtime, actors, countries, and release timelines that influence:

Audience engagement

IMDb & TMDB ratings

Content popularity

Commercial success

…and translate those insights into actionable recommendations for content strategy.
---
🔷 Dataset Overview

Source: Amazon Prime Movies & TV Shows

Rows: 125,354

Columns: 19

Content Types:

Movies: 8,418

Shows: 1,355

Key Features Used:

IMDb Score, IMDb Votes, TMDB Score, TMDB Popularity, Genres, Runtime, Actors, Countries, Release Year
---
🔷 Methodology

Data cleaning, transformation, and preprocessing using Pandas & NumPy

Handled missing values using median/mode strategies based on distribution

Normalized multi-value fields (genres, countries) using string cleaning + explode

Applied threshold-based filtering to isolate high-performing content

IMDb > 7

TMDB > 7.5

Conducted structured analysis using UBM Framework:

Univariate

Bivariate

Multivariate

Created 20+ business-driven visualizations using Matplotlib & Seaborn
---
🔷 Key Insights (This Is the Gold)
📌 Content Performance

Only 5–10% of total content achieves high IMDb & TMDB scores

Indicates strong underlying success patterns, not randomness

📌 Genre Intelligence

Documentary, History, and Music genres score highest on quality metrics

Animation, Sci-Fi, Fantasy dominate popularity but not necessarily ratings

High production volume ≠ high popularity (e.g., Drama)

📌 Runtime Optimization

90–120 minutes is the sweet spot:

Highest median IMDb & TMDB scores

Strongest popularity and voting metrics

Very long runtimes (>180 mins) underperform consistently

📌 Geography & Market Strategy

US leads in high-quality content volume

India shows strong growth in post-2000 high-rated movies

UK and Europe contribute niche, quality-focused content

📌 Actor Impact

Actors with repeated high-scoring appearances correlate strongly with popularity

Star power remains a measurable performance lever

📌 Ratings vs Popularity

IMDb & TMDB scores show moderate positive correlation

Popularity ≠ quality → both must be balanced for profitability
---
🔷 Business Impact & Recommendations

✔ Focus production on 90–120 min runtime
✔ Invest selectively in high-scoring genres, not just popular ones
✔ Combine rating metrics + popularity signals for green-lighting content
✔ Leverage regional strengths (US scale, India growth, Europe quality)
✔ Avoid over-producing low-ROI genres despite high volume
---
🔷 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Google Colab (Deployment-ready, single-run execution)
---
Open the notebook in Google Colab

Install required libraries (if not pre-installed)

Run cells sequentially to reproduce the analysis

Explore visualizations and insights section for conclusions
---
👤 About Me

Aspiring Data Analyst / Data Scientist transitioning into the corporate analytics domain.
Strong focus on problem-solving, data storytelling, and business impact, with hands-on experience in real-world datasets and analytical projects.
