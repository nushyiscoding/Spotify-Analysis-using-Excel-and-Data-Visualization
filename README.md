# 🎵 Spotify Music Analysis (1998-2020)
*Overload Ware Labs AI Internship Project*

Dataset Link: https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019

## 📊 Project Overview
This data analytics project explores music trends and patterns using Spotify's extensive dataset spanning from 1998 to 2020. The analysis provides valuable insights into artist popularity, audio characteristics, and evolving listener preferences across different genres and time periods.

## 🎯 Key Insights

### 1. 🏆 Top 10 Artists with Their Dominant Genres
**Analysis**: Identified the most prominent artists in the dataset and their primary music genres by the Count of song.

**Key Findings**:
- **Rihanna** leads with 25 songs (Hip Hop/Pop/R&B)
- **Drake**: 23 songs (Hip Hop/Pop/R&B)
- **Eminem**: 21 songs (Hip hop)
- **Calvin Harris**: 20 songs (Hip Hop/Pop/Dance/Electronic)
- **Britney Spears**: 19 songs (Pop)
- **David Guetta**: 18 songs (Hip Hop/Pop/Dance/Electronic)
- **Chris Brown**: 17 songs (Hip Hop/Pop/R&B)
- **Kanye West**: 17 songs (Hip hop)
- **Katy Perry**: 16 songs (Pop)
- **Taylor Swift**: 16 songs (Pop)

### 2. ⭐ Top 3 Songs by Popularity
**Analysis**: Highest-rated songs based on Spotify's popularity metric.

**Key Findings**:
1. **"Sweater Weather" - The Neighbourhood** (Popularity: 89)
2. **"Another Love" - Tom Odell** (Popularity: 88)
3. **"Without Me" - Eminem** (Popularity: 87)

### 3. 💃 Danceability vs Energy Trends
**Analysis**: Explored the relationship between danceability and energy across different years and genres, identifying how these features correlate and evolve.

**Key Findings**:
- Danceability has held steady with a slight upward trend, while energy in top hits surged around 2000 and has powered the charts ever since.
- The 21st century truly turned up the tempo. 

### 4. ⚠️ Explicit vs Non-Explicit Songs by Year
**Analysis**: Tracked the prevalence of explicit content in music over the years.

**Key Findings**:
- **2018**: Peak years for explicit content (51 songs)

### 5. 📈 Average Danceability: Explicit vs Non-Explicit Songs
**Analysis**: Compared the danceability metrics between explicit and non-explicit songs to understand if content rating influences musical characteristics.

**Key Findings**:
- Explicit songs tend to have higher average danceability, suggesting they are crafted to be more dance-friendly!

### 6. 🎼 Genre-Based Audio Feature Analysis
**Analysis**: Comprehensive examination of audio features across different music genres, creating genre signatures and identifying unique characteristics.

**Key Features Analyzed**:
- Danceability, Energy, Valence, Acousticness, Speechiness

**Key Findings**:
- Rock is the most energetic genre, with a leading score of 0.81.
- Hip Hop is the most speech-heavy genre, with a dominant 0.20 in speechiness.
- Hip Hop also ranks highest in danceability at 0.72.
- Country music is the most acoustic, with a peak score of 0.22.
- Metal has the lowest valence at 0.43, indicating it is the least positive-sounding genre.

## 🛠 Technical Implementation

### Dataset
- **Time Period**: 1998-2020
- **Records**: 2000 songs
- **Features**: 18 audio and metadata attributes
- **Genres**: Pop, Rock, Hip Hop, R&B, Electronic, Metal, and more

### Tools & Technologies
- **Excel** : Data Organization, Pivot Tables for Statistical Analysis, Initial Calculations and Aggregations
- **Data Analysis**: Statistical analysis, trend identification
- **Power BI**: Interactive Dashboard for Data Visualization

### Methodology
1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Statistical Analysis & Hypothesis Testing**
4. **Data Visualization & Insight Generation**
5. **Trend Analysis & Pattern Recognition**

## 📈 Business Applications

- **Music Recommendation Systems**: Enhanced genre and feature-based recommendations
- **Artist Development**: Understanding successful audio characteristics
- **Content Strategy**: Insights for music platforms and labels
- **Market Analysis**: Tracking evolving listener preferences
- **A&R Decisions**: Data-driven artist signing and development

pip install -r requirements.txt

# Run the analysis
jupyter notebook spotify_analysis.ipynb
