# Dataset Information

## File Included
The dataset used in this project is available in this repository:

data/spotify-top50-data.csv


---

## Description

This dataset contains Spotify song-level metadata used to analyze trends in music popularity, artist performance, and content characteristics.

---

## Key Columns

- song → Name of the track  
- artist → Artist name  
- popularity → Popularity score (0–100)  
- duration_ms → Track duration in milliseconds  
- album_type → Type (single / album)  
- release_year → Year of release  
- is_explicit → Boolean flag for explicit content  
- position → Chart ranking  

---

## Notes

- Duration is converted from milliseconds to minutes in the dashboard  
- Explicit vs Non-explicit classification is used for content analysis  
- Data is modeled under table name:
  'Top-50-world' in Power BI  

---

## Usage

To use this dataset:

1. Open Power BI Desktop  
2. Click **Get Data → Text/CSV**  
3. Load the dataset  
4. Apply transformations using Power Query  
5. Use DAX measures from `dax/dax-measures.md`