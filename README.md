# 🎬 Netflix Content Analysis Dashboard

An interactive **Tableau dashboard** that analyzes Netflix's content library by genre, country, release year, runtime, cast size, and director.

<img width="1123" height="622" alt="Screenshot 2026-11-21 222234" src="https://github.com/user-attachments/assets/e7ac4bb2-5153-4601-bf8f-6f7904dbce02" />


---

## 📑 Table of Contents
- [Overview](#-overview)
- [Key Metrics](#-key-metrics)
- [Interactive Filters](#-interactive-filters)
- [Visualizations](#-visualizations)
- [Key Insights](#-key-insights)
- [Tools Used](#-tools-used)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)

---

## 📖 Overview
This dashboard provides a clear overview of Netflix's catalog. It combines headline KPIs, interactive filters, and six visualizations so users can explore trends in content type, geography, release timing, and production details.

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Titles | 6,169 |
| Total TV Shows | 1,958 |
| Total Movies | 4,240 |
| Countries Represented | 72 |

## 🎛️ Interactive Filters
- **Rating**: multiple selection
- **Release Year**: slider (1925 to 2020)
- **Primary Genre**: multiple selection
- **Primary Country**: multiple selection

## 📈 Visualizations

| # | Chart | Type | Description |
|---|---|---|---|
| 1 | Content Release Trends | Line chart | Titles released per year, with a sharp rise after 2010 and a peak around 2017–2018 (~700 titles). |
| 2 | Average Runtime by Genre | Lollipop chart | Average movie runtime by genre; most genres sit around 100 minutes. |
| 3 | Top 10 Directors by Number of Netflix Titles | Bubble chart | Directors with the most titles, sized by title count. |
| 4 | Average Cast Size by Genre | Horizontal bar chart | Genres ranked by average cast size (~17.4 down to ~9.1). |
| 5 | Genre & Year Analysis | Heatmap | Genre vs. release year (1940–2020), with density growing in recent years. |
| 6 | Movies vs TV Shows by Country | 100% stacked bar | Each country's split between movies and TV shows. |

## 💡 Key Insights
- 🎥 **Movies dominate:** about 69% of titles are movies and 31% are TV shows.
- 📅 **Growth is recent:** most content was released between 2010 and 2018.
- 🌍 **Global reach:** the library covers 72 countries.
- ⏱️ **Consistent runtimes:** most genres average around 100 minutes.

## 🛠️ Tools Used
- **Tableau** (dashboard design and visualization)
- **Netflix Titles dataset** (source data)

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-content-analysis.git
   ```
2. Open the `.twbx` file in **Tableau Desktop** or **Tableau Public**.
3. Use the filters at the top to explore the data.

## 📁 Project Structure
```
netflix-content-analysis/
├── images/
│   └── dashboard.png
├── data/
│   └── netflix_titles.csv
├── Netflix_Dashboard.twbx
└── README.md
```



---

⭐ If you found this project useful, consider giving it a star!
