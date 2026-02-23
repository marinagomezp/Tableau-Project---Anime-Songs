# 🎵 Measuring Emotion & Popularity in Anime Songs  
---

## 📌 Project Overview

Music is an emotional experience — yet popularity is measurable.

This project explores how musical structure (**key, mode, danceability, duration**) relates to emotional classification (**happy vs sad**) and popularity within anime songs.

Using **Tableau**, I developed an interactive dashboard to uncover compositional patterns and examine whether emotional tone influences audience engagement.

🔗 **View the interactive dashboard on Tableau Public:**  
[Click here to explore](https://public.tableau.com/views/spotifytableau_17718507467350/Moodanimedashboard?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🎯 Objectives

This analysis aimed to answer:

- Do certain musical keys dominate anime songs?
- Is there a relationship between **Major/Minor mode** and emotional classification?
- Are sad or happy songs more prevalent?
- Do danceability and duration influence popularity?
- Is popularity associated with a specific emotional tone?

---

## 📊 Dataset Overview

The dataset contains anime songs with the following attributes:

- Track ID  
- Track Name  
- Artist Name  
- Genre  
- Musical Key  
- Mode (*Major / Minor*)  
- Mood Classification (*Happy / Sad*)  
- Danceability  
- Duration (minutes)  
- Popularity Score  

### 🎶 Mood Distribution

- **Sad songs:** 5,196 tracks (~58%)  
- **Happy songs:** 3,740 tracks (~42%)  

This suggests a higher representation of sad-classified tracks within the dataset.
---

## 📎 Dashboard Preview

![Dashboard Screenshot](https://github.com/marinagomezp/Tableau-Project---Anime-Songs/blob/main/dashboard.png) 

---

## 📈 Dashboard Breakdown

### 1️⃣ Track Distribution by Key

A stacked bar chart shows the count of tracks by musical key, split by **Major and Minor mode**.

**Insight:**  
Certain keys (such as **G, C, and D**) appear significantly more frequently, suggesting compositional preferences within anime music production.


### 2️⃣ Mood Analysis (Happy vs Sad)

A pie chart visualises the emotional breakdown of the dataset.

**Key Finding:**  
Sad songs dominate the dataset, accounting for nearly **60%** of all tracks, reflecting a strong presence of emotionally expressive or melancholic themes.


### 3️⃣ Top Anime Songs by Popularity

A filtered bar chart displays the **Top 10 songs based on total popularity**.

**Observation:**  
High popularity is not exclusive to one mood category — both happy and sad tracks appear among top-performing songs.

This suggests emotional tone alone does not determine engagement.


### 4️⃣ Danceability, Duration & Popularity Comparison

A comparative analysis across mood categories reveals:

- Sad songs show higher total duration aggregation.
- Danceability differs between emotional classifications.
- Popularity totals vary but do not overwhelmingly favor one mood.

This indicates that structural musical features interact with popularity in more complex ways than simple emotional labeling.


## 🔎 Key Insights

- Anime music shows a measurable bias toward *minor tonal structures* and sad classifications.
- Certain musical keys are disproportionately represented.
- Emotional classification alone does not determine popularity.
- Structural attributes such as duration and danceability vary across moods.
- Popularity appears influenced by multiple factors rather than emotional tone alone.

---

## 🎛 Interactive Features

The dashboard includes:

- Track Name filter  
- Genre filter  
- Top 10 popularity limiter  
- Major/Minor mode comparison  
- Mood-based segmentation  

Designed for exploratory analysis rather than static reporting.

---

## 💡 This project demonstrates:

- Multi-dimensional dashboard structuring  
- Integration of music theory with quantitative analysis  
- Clear comparative visual storytelling  
- Ability to extract insights beyond descriptive statistics  
