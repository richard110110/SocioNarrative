# SocioNarrative: Geo-based Social Media Event Analyzer

SocioNarrative is an interactive, Jupyter Notebook-based application designed to empower researchers in the humanities and social sciences to analyze large-scale social media text data with minimal coding. The system integrates natural language processing (NLP) with geospatial visualization to enable intuitive event and sentiment exploration on a map.

## 🌍 Key Features

- Upload and analyze social media posts (CSV/JSON) with optional geolocation
- Perform:
  - Named Entity Recognition (NER)
  - Sentiment Analysis
  - Topic Modeling
- Visualize tweet-level data interactively on maps with:
  - Marker clustering
  - Sentiment color-coding
  - Keyword tooltips
- Interactive filters:
  - By date, location, keyword, or sentiment polarity
- Export structured data and visualizations to CSV, PNG, and PDF

## 🛠️ Tech Stack

- **Frontend / GUI**: `Jupyter Notebook`, `ipywidgets`, `ipyleaflet`
- **Text Analysis**: `spaCy`, `transformers`, `NLTK`, `gensim`
- **Geospatial Mapping**: `ipyleaflet`, `geopy`, `pandas`
- **Visualization**: `matplotlib`, `plotly`, `wordcloud`

## 👤 Target Users

This tool is tailored for non-technical users such as:
- Sociologists
- Media researchers
- Policy analysts
- Digital humanities scholars

## 🚀 Getting Started

1. Clone the repo:


## 🚀 How to Run

1. Make sure you have Python 3.8+ installed
2. Install dependencies:
## 📁 Data Format

Your input CSV must contain the following columns:
- `timestamp`
- `text`
- `location`
- `sentiment`
- `country`
- `latitude`
- `longitude`

### 🔗 Run on Binder
[Click here to launch in Voila (Binder)](https://hub.gesis.mybinder.org/user/richard110110-socionarrative-54kbiuh4/voila/render/notebook/visualization_map.ipynb)
