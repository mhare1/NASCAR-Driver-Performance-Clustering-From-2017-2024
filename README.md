# NASCAR Driver Performance Clustering

This project analyzes NASCAR Cup Series race data from 2017–2024 to measure driver performance using statistics like average finish, win rate, and consistency. Using these statistics, I identify natural clusters of performance profiles — such as elite contenders, mid-pack competitors, and backmarkers.

Data Source: NASCAR Cup Series race results (2017–2024) by joeah99 downloaded from Kaggle

Tech Stack: Python, Pandas, NumPy, Scikit-learn, Matplotlib
Techniques Used:
- Cleaned and aggregated race-level data for 200+ drivers
- Feature engineering for win rates, laps led, and points
- K-Means clustering to group drivers into 4 tiers
- PCA visualization of clusters
- Boxplots explaining what defines each tier

Based on K-Means clustering of driver-level performance metrics (2017–2024):
Tier 1 – Elite Contenders: Consistent race winners with top finishes and high lap leadership.
Tier 2 – Competitive Drivers: Frequent top-10 finishes, competitive but less dominant.
Tier 3 – Consistent Mid-Pack: Reliable finishers who score points but rarely lead races.
Tier 4 – Developing/Backmarkers: Limited success or small-sample drivers with low point totals.
