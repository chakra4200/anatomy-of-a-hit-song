# The Anatomy of a Hit Song

### Exploring the characteristics associated with popular songs using Spotify track data

## 📌 Project Overview

This project explores the audio characteristics associated with higher song popularity using Spotify track-level data.

The primary analytical question is:

> **What characteristics are associated with higher popularity among songs?**

The analysis focuses on identifying patterns between popularity and audio characteristics such as danceability, energy, acousticness, and valence.

This is an independent analysis of Spotify track data and does not imply that any particular audio characteristic causes a song to become popular.

---

## 🎯 Objectives

- Understand the overall distribution of song popularity.
- Compare audio characteristics across different popularity groups.
- Identify characteristics associated with higher-popularity tracks.
- Explore the relationship between popularity and danceability.
- Identify the most popular tracks in the dataset.
- Translate analytical findings into clear business-style insights.

---

## 📊 Popularity Segmentation

For analytical purposes, tracks were divided into three groups based on their popularity score:

| Popularity Score | Group |
|---|---|
| Below 50 | Low Popularity |
| 50–74 | Moderate Popularity |
| 75 and above | High Popularity |

> These thresholds are analytical groupings created for this project and are not official Spotify classifications.

---

## 🔍 Key Findings

### Audio Characteristics by Popularity Group

| Audio Characteristic | Low | Moderate | High |
|---|---:|---:|---:|
| Danceability | 0.5725 | 0.6368 | 0.7059 |
| Energy | 0.5634 | 0.6059 | 0.6330 |
| Acousticness | 0.3511 | 0.2884 | 0.2365 |
| Valence | 0.4372 | 0.4541 | 0.4796 |

### Key Observations

- **Danceability increases noticeably** across the popularity groups.
- **Energy also increases** as popularity moves from low to high.
- **Acousticness decreases** across the popularity groups.
- **Valence shows a smaller upward pattern** among higher-popularity tracks.
- The analysis indicates associations and patterns, rather than causal relationships.

---

## 📈 Dataset Overview

- **Distinct tracks:** 130,326
- **Average popularity:** 24.21
- **Average danceability:** 0.5815
- **Average energy:** 0.5692

### Popularity Distribution

| Popularity Group | Number of Tracks |
|---|---:|
| Low | 113,432 |
| Moderate | 15,922 |
| High | 972 |

---

## 📊 Tableau Analysis

The analysis was developed in **Tableau** using the track-level dataset.

The completed analysis sheets include:

- Average Popularity
- Total Tracks
- Average Danceability
- Average Energy
- Average Danceability by Popularity Group
- Average Energy by Popularity Group
- Audio Characteristics of Popularity Groups
- Popularity Distribution
- Top Popular Tracks
- High Popularity Track Profile
- Popularity vs Audio Characteristics

The Tableau workbook and analysis sheets are included in this repository.

### Dashboard

The final interactive Tableau dashboard is **currently under development** and will be added after the dashboard design and interactive elements are completed.

---

## 🛠️ Tools Used

- **Tableau** — Data visualization and analytical exploration
- **Excel** — Dataset preparation
- **CSV** — Track-level analysis dataset

---

## 📂 Project Structure

```text
The-Anatomy-of-a-Hit-Song/
│
├── Data/
│   └── Anatomy_of_a_Hit_Song_Analysis_Data.csv
│
├── Tableau/
│   └── Tableau Analysis Workbook
│
└── README.md
