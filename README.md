# Investigating TMDb Movie Data

> *What makes a movie successful? Dive into 10,000+ films to find out.*

---

## About the Project

This project is an exploratory data analysis (EDA) of **The Movie Database (TMDb)** dataset, originally developed as part of the [Udacity Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002). It investigates trends, patterns, and correlations across thousands of movies spanning decades of cinema history.

Starting from a raw dataset with significant gaps in budget and revenue data, this project demonstrates a full data analysis pipeline: **cleaning, enrichment, exploration, and visualization**.

## Key Questions Explored

| # | Question | Finding |
|---|----------|---------|
| 1 | Which quarter has the most releases? | **Q3** (Jul-Sep) dominates |
| 2 | What's the year-over-year production trend? | Production peaked at **700 films in 2014** |
| 3 | What's the most popular genre? | **Drama** leads consistently |
| 4 | Best month to release a movie? | **September**, October, and December |
| 5 | Most prolific director? | **Woody Allen** with the highest film count |
| 6 | Highest-grossing movie? | **Avatar** tops the revenue chart |
| 7 | Does popularity drive revenue? | Yes - **positive correlation** observed |
| 8 | What's the ideal runtime? | **100-150 minutes** for maximum popularity |

## Project Structure

```
Investigating_data_imdb/
├── investigate-a-dataset.ipynb   # Main analysis notebook (code + visualizations)
├── Project_Walkthrou.ipynb       # Visual walkthrough of the methodology
├── finaltmdb.csv                 # Cleaned & enriched dataset (~10,800 movies)
├── requirements.txt              # Python dependencies
├── .gitignore                    # Git ignore rules
└── README.md                    # You are here
```

## Tech Stack

- **Python 3** - Core language
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing and random imputation
- **Matplotlib & Seaborn** - Data visualization
- **tmdbsimple** - TMDb API wrapper for data enrichment

## Getting Started

### Prerequisites

- Python 3.8+
- A TMDb API key ([get one free here](https://www.themoviedb.org/settings/api))

### Installation

```bash
# Clone the repository
git clone https://github.com/matef88/Investigating_data_imdb.git
cd Investigating_data_imdb

# Install dependencies
pip install -r requirements.txt

# Set your TMDb API key
export TMDB_API_KEY="your_api_key_here"     # Linux/Mac
set TMDB_API_KEY=your_api_key_here          # Windows CMD
$env:TMDB_API_KEY="your_api_key_here"       # PowerShell

# Launch the notebook
jupyter notebook investigate-a-dataset.ipynb
```

> **Note:** The cleaned dataset (`finaltmdb.csv`) is already included, so you can skip the API data-fetching cells and jump straight to the analysis section if you prefer.

## Sample Visualizations

The notebook produces a variety of charts including:

- **Bar charts** - Movie releases by quarter, month, top directors, top actors, and production companies
- **Line charts** - Year-over-year production trends, director popularity over time
- **Pie charts** - Genre distribution for peak years
- **Regression plots** - Popularity vs. revenue, popularity vs. runtime
- **Horizontal bar charts** - Top movies by budget and revenue

## Known Limitations

- ~50% of budget/revenue values were missing and supplemented via the TMDb API or random imputation within plausible ranges
- The dataset covers movies up to ~2015 and may not reflect current streaming-era trends
- API rate limits caused some data enrichment failures, defaulting those entries to zero

## About the Author

This project was created by [**matef88**](https://github.com/matef88) as part of the Udacity Data Analyst Nanodegree program. It showcases practical skills in data wrangling, exploratory data analysis, and data visualization using Python's scientific computing ecosystem.

---

*Built with curiosity and data. If you found this useful, consider giving it a star!*
