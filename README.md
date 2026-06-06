# Netflix Content Strategy Analysis

## Project Overview

This project analyzes Netflix's content catalog to understand:

- Content growth over time
- Audience targeting strategy
- Movie vs TV Show distribution
- International expansion
- Genre preferences across markets

The analysis was performed using Python, Pandas, Matplotlib, and Seaborn.

---

## Dataset

Netflix Movies and TV Shows Dataset

Total Titles Analyzed: 8,807

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Data Preparation

The dataset was cleaned by:

- Handling missing values
- Converting date fields into datetime format
- Creating audience categories (Kids, Teen, Adult)
- Splitting multi-label genres into individual categories using feature engineering

---

## Key Findings

### 1. Netflix Experienced Rapid Growth After 2016

Netflix's catalog expanded dramatically between 2016 and 2019, reaching its highest annual content additions in 2019.

### 2. Teen and Adult Audiences Dominate Netflix

The majority of Netflix's catalog targets Teen and Adult audiences, while Kids content represents a significantly smaller share.

### 3. Movies Drive Catalog Expansion

Movies consistently outnumber TV Shows and contributed most of Netflix's content growth.

### 4. International Content Is Central To Netflix's Strategy

International Movies and International TV Shows are among the largest content categories on the platform.

### 5. India Is Netflix's Largest Non-US Content Market

India ranks second only to the United States in total content contributions.

### 6. Genre Differences Between India and the United States

After removing market-distribution labels such as International Movies and International TV Shows:

- Indian content is highly concentrated in Drama and Comedy.
- US content exhibits greater genre diversity, including Documentaries, Stand-Up Comedy, Children's Content, and TV Comedies.

---

## Business Insights

The analysis suggests that Netflix maintained a relatively consistent audience strategy during its expansion phase.

Growth appears to have been driven primarily by:

- Increased content acquisition
- Expansion into international markets
- Heavy emphasis on movie content

rather than a major shift in audience demographics.

---

## Limitations

This dataset reflects Netflix's catalog and not actual viewer watch-time, engagement, subscription behavior, or revenue.

Therefore, conclusions describe content strategy rather than user behavior.

---
# Visualizations

## Content Growth

![Content Growth](visuals/Content%20growth.png)

Netflix experienced rapid growth between 2016 and 2019, peaking at over 2000 content additions in 2019.

---

## Movies vs TV Shows

![Movies vs TV Shows](visuals/Movies%20vs%20TV%20shows.png)

Movies significantly outnumber TV Shows on Netflix, indicating a strong emphasis on film acquisition and distribution.

---

## Audience Distribution

![Audience Distribution](visuals/Audience%20Distribution.png)

Teen and Adult audiences dominate Netflix's catalog, while Kids content represents a smaller segment.

---

## Audience Trends Over Time

![Audience Trends](visuals/Audience%20Trends.png)

Netflix maintained a strong focus on Teen and Adult audiences throughout its expansion period.

---

## India vs United States Content Growth

![India vs US](visuals/India%20vs%20US%20content%20growth.png)

India emerged as Netflix's largest non-US market, demonstrating Netflix's investment in high-growth international regions.

---

## Top Netflix Genres

![Top Genres](visuals/Top%20Genres.png)

International Movies and Dramas are among the most common categories in Netflix's catalog.

---

## India Genre Distribution

![India Genres](visuals/India%20genre%20percentage.png)

Indian content is heavily concentrated around Drama and Comedy genres.

---

## US Genre Distribution

![US Genres](visuals/US%20genre%20percentage.png)

US content demonstrates greater genre diversity, with stronger representation in documentaries, stand-up comedy, and family-oriented content.
