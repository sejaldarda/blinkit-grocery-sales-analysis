# Spotify Music Streaming Analysis | Power BI

An interactive Power BI dashboard exploring streaming performance across tracks, release dates, and audio characteristics. The report summarizes overall streaming metrics and compares high-performing songs in the dataset.

## Dashboard Preview

Add your screenshot to `images/spotify-dashboard.png`, then uncomment the line below:

<!-- ![Spotify Music Streaming Dashboard](images/spotify-dashboard.png) -->

## Project Objectives

- Summarize total and average streams across tracks in the report.
- Identify leading tracks by stream count.
- Compare the streaming performance of selected songs.
- Explore the release-date coverage of the dataset.
- Examine audio characteristics such as energy, danceability, speechiness, liveness, and instrumentalness.

## Tools and Skills

- **Power BI Desktop** — dashboard development and data visualization
- **Power Query** — data preparation and transformation, where used
- **DAX** — measures and calculated fields, where used
- **Exploratory data analysis** — track comparisons and audio-feature exploration

*Keep only the tools and techniques you actually used.*

## Dashboard Highlights

The dashboard currently displays these headline values:

| Metric | Value shown in dashboard |
|---|---:|
| Total streams | 489 billion |
| Tracks | 952 |
| Average streams per track | 514.14 million |
| Highest-streamed displayed track | Blinding Lights |
| Streams for Blinding Lights | 3,703,895,074 |
| Displayed date range | 1 January 1930 – 14 July 2023 |

These figures describe the current report view and should be rechecked if the dataset, cleaning steps, or filters change. The 1930 date may reflect a source-data or date-handling issue rather than a genuine release date, so it is worth validating.

## Business Insights

1. **Overall streaming scale:** The dashboard reports approximately **489 billion streams across 952 tracks**, averaging **514.14 million streams per track**. This provides a high-level view of the streaming activity represented in the report.
2. **Leading track:** **Blinding Lights** by The Weeknd is shown with **3,703,895,074 streams**. This makes it the leading displayed track in the current report view.
3. **Comparison among leading songs:** Dance Monkey, Shape of You, Someone You Loved, and Sunflower also appear among the leading tracks. Compare their exact stream counts in the visual before describing the size of the gap between them.
4. **Release-date coverage:** The report displays dates from **1 January 1930 to 14 July 2023**. Check the earliest records and date-construction logic before drawing conclusions about historical release patterns.
5. **Audio-feature exploration:** The report includes energy, danceability, speechiness, liveness, and instrumentalness. These fields can be compared across tracks to explore possible patterns, but the dashboard alone does not establish that an audio feature causes higher streaming counts.

## Dataset

- **Suggested dataset:** *Most Streamed Spotify Songs 2023*
- **Potential source:** [Kaggle — Most Streamed Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)
- **Dataset file:** Place the exact CSV/XLSX used by the report in the `data/` folder.
- **Suggested path:** `data/spotify_most_streamed_songs_2023.csv` (change to match your actual filename).

Make sure the dataset is the same one used to build the dashboard. The published dataset may contain a different number of rows than the cleaned report because rows can be removed or transformed during preparation. Credit the dataset creator and follow the dataset's license and terms.

## Repository Structure

```text
spotify-music-streaming-analysis/
├── README.md
├── dashboard/
│   └── Spotify Dashboard.pbix
├── data/
│   └── [original-dataset-file]
└── images/
    └── spotify-dashboard.png
```

## How to View the Dashboard

1. Download or clone this repository.
2. Open `dashboard/Spotify Dashboard.pbix` using Power BI Desktop.
3. If prompted, update the dataset source path to the file in `data/`.
4. Refresh the report if needed.
5. Explore the track rankings, summary metrics, and audio-feature visuals.

Power BI Desktop is required to open and interact with the `.pbix` file.

## Data Quality and Limitations

- Streaming totals reflect the dataset and its collection period; they should not be interpreted as live Spotify metrics.
- Validate date fields, missing values, and data types before drawing conclusions from release-date visuals.
- Audio-feature comparisons are exploratory and do not demonstrate causation.
- Dashboard metrics may differ from the raw dataset if rows were removed, transformed, or filtered.

## Author

**[Your Name]**

- GitHub: [Your GitHub profile URL]
- LinkedIn: [Your LinkedIn profile URL]

---

*This project is part of my Data Analytics portfolio.*
