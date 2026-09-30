# What Drives Movie Performance?

A Power BI dashboard built from **1M+ movie records** to analyze what drives box office performance across budget, genre and release timing.

## Business Question

**Which genres, budgets and release windows deliver the strongest returns for a film?**

## Dashboard at a Glance

The default view covers **343 movies** (original language: English, released 2020–2024).

| Metric | Value |
|---|---|
| Movies in view | 343 |
| Median budget | 40M |
| Median revenue | 51M |

**Interactive filters:** original language and release year range.

**Visuals:**
- Budget vs. revenue for individual movies (log scale, with trend line)
- Average budget vs. average ROI by genre
- Genre strategy matrix (average ROI and budget by genre)
- Average profit by genre
- Average monthly revenue trends

## Key Findings

1. **Science Fiction, Action and Adventure deliver the highest average ROI.** Sci-Fi leads at 319%, followed by Action (290%) and Adventure (225%). Fantasy sits well behind at 38%.
2. **Adventure leads on average profit.** At 9.9M it tops the list, followed by Science Fiction (5.6M), Fantasy (5.5M) and Action (5.1M).
3. **Comedy, Drama and Thriller had negative average ROI** in this view (-60%, -80% and -87%), so these genres lost money on average relative to their budgets.
4. **May and December are the strongest release windows.** Average revenue peaks in May (276M) and December (262M), with June (249M) and July (244M) also strong. January (60M), October (82M) and August (83M) are the weakest months.
5. **Higher budgets do not guarantee higher revenue.** Budget and revenue are positively related, but individual movies vary widely around the trend line.

## Limitations

- **Filtered sample.** The default view covers 343 movies (English, 2020–2024), a small slice of the full dataset, so results may change with different filters.
- **Averages can be skewed.** A few blockbusters or flops can pull genre ROI up or down, so medians or distributions would give a fuller picture.
- **ROI is an approximation.** Reported budget and revenue may not include marketing and distribution costs.
- **Associations, not causes.** The dashboard shows which patterns appear in the data, not why they occur.

## Suggested Next Steps

- Add ROI by release month to test whether the May and December revenue peaks also hold for returns.
- Group movies into budget bands to identify where returns are strongest.
- Add rating and popularity metrics alongside financial performance.
- Compare results across different year ranges and languages.

## Tools

- **Power BI Desktop** for data modeling, measures and visuals
- **Dataset:** [Full TMDB Movies Dataset 2024 (1M Movies) on Kaggle](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies)

## Repository Contents

```
├── README.md
└── images/
    └── dashboard.png
```

## Author

**Gourav Jagde**, Business Administration (Finance & Management Information Systems), Simon Fraser University
[LinkedIn](https://www.linkedin.com/in/gouravjagde)
