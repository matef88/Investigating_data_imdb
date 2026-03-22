# 🎬 Cinema Insights: The Data Director's Cut

> *Roll camera on 10,000+ movies. Actionable insights. Cut.*

---

## 🎥 The Pitch

Imagine having a backstage pass to Hollywood's vault—where every budget, every release date, every genre choice tells a story. **Cinema Insights** is your all-access credential to the hidden patterns behind cinematic success.

This isn't just data analysis. It's **forensic filmography**—a deep-dive exploratory investigation that transforms raw numbers into narrative gold. Born from the [Udacity Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002), this project takes a messy dataset riddled with missing budgets and ghost revenues, and turns it into a polished, query-ready masterpiece.

**Think of it as Moneyball meets Netflix—where data meets drama.**

---

## 🎭 The Story in Numbers

| 🎬 Question | 🎯 The Verdict |
|:------------|:---------------|
| Which quarter floods theaters? | **Q3 (Jul-Sep)** wins the release race |
| Peak production year? | **2014** with a staggering **700 films** |
| The crowd's favorite genre? | **Drama**—the timeless champion |
| Golden release window? | **September, October, December** |
| Most prolific director? | **Woody Allen**—quantity meets consistency |
| Box office king? | **Avatar** reigns supreme |
| Does popularity pay? | **Absolutely**—positive correlation confirmed |
| The sweet spot for runtime? | **100–150 minutes** of audience bliss |

---

## ⚙️ The Engine Room

This production runs on a lean, powerful stack:

| Component | Technology | Role |
|:----------|:-----------|:-----|
| 🐍 **Core** | Python 3 | The scripting language |
| 📊 **Data Wrangling** | pandas | Slicing, dicing, and transforming |
| 🔢 **Number Crunching** | NumPy | Statistical heavy lifting |
| 📈 **Visual Storytelling** | Matplotlib & Seaborn | Charts that speak volumes |
| 🌐 **Data Enrichment** | tmdbsimple | API bridge to TMDb's treasure trove |

---

## 🚀 Launch Sequence

### 🎟️ Prerequisites

- **Python 3.8+** installed on your machine
- A **TMDb API key** ([claim yours free](https://www.themoviedb.org/settings/api))

### 📋 Installation

```bash
# 1️⃣ Clone the production studio
git clone https://github.com/matef88/Investigating_data_imdb.git
cd Investigating_data_imdb

# 2️⃣ Install the crew (dependencies)
pip install -r requirements.txt

# 3️⃣ Set your backstage pass (API key)
export TMDB_API_KEY="your_api_key_here"     # 🐧 Linux / 🍎 macOS
set TMDB_API_KEY=your_api_key_here          # 🪟 Windows CMD
$env:TMDB_API_KEY="your_api_key_here"       # 💠 PowerShell

# 4️⃣ Roll the film (launch notebook)
jupyter notebook investigate-a-dataset.ipynb
```

> 💡 **Pro Tip:** The cleaned dataset (`finaltmdb.csv`) is already included—skip the API calls and jump straight to the analysis if you prefer!

---

## ✨ Features Showcase

### 🧹 Data Janitor
- **Smart Cleaning** — Handles missing values, removes duplicates, and standardizes formats
- **API Enrichment** — Supplements gaps with live TMDb data
- **Random Imputation** — Fills stubborn holes with statistically plausible values

### 📊 Visual Storyteller
- **Bar Charts** — Releases by quarter, month, top directors, actors, and studios
- **Line Charts** — Year-over-year production trends, director popularity arcs
- **Pie Charts** — Genre distribution snapshots for peak years
- **Regression Plots** — Popularity vs. revenue, popularity vs. runtime
- **Horizontal Bars** — Top movies by budget and revenue

### 🔍 Insight Generator
- **Trend Detection** — Identifies patterns across decades of cinema
- **Correlation Analysis** — Reveals relationships between variables
- **Comparative Studies** — Benchmarks genres, directors, and release windows

---

## 🗺️ Future Roadmap

| Coming Soon | Status |
|:------------|:-------|
| 🎥 Streaming-era analysis (post-2015) | Planned |
| 🤖 Machine learning predictions | Exploring |
| 🌍 International box office comparisons | Considering |
| 📱 Interactive dashboard | On the wishlist |

**Want to contribute?** Fork the repo, create a feature branch, and submit a pull request. All contributions welcome—from bug fixes to new visualizations!

---

## ⚠️ Known Limitations

- ~50% of budget/revenue data was missing—supplemented via TMDb API or random imputation
- Dataset covers films up to ~2015 (pre-streaming boom)
- API rate limits caused some enrichment failures (defaulted to zero)

---

## 🎬 Credits

**Created by** [**matef88**](https://github.com/matef88)  
*Part of the Udacity Data Analyst Nanodegree portfolio*

This project demonstrates practical mastery of:
- ✅ Data wrangling & cleaning
- ✅ Exploratory data analysis (EDA)
- ✅ Statistical visualization
- ✅ API integration

---

<p align="center">
  <i>🎬 Built with curiosity, powered by data. If this project entertained your brain, give it a ⭐!</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square" alt="Status">
</p>
