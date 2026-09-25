# Dataset

This repository does **not** commit the raw dataset. Download it and place it here.
The original dataset documentation is preserved alongside this file as `dataset_readme.md`
(it contains the full data dictionary and attribution).

| | |
|---|---|
| **Name** | 30,000 Spotify Songs |
| **File expected here** | `data/spotify_songs.csv` |
| **Rows** | ~32,000 tracks |
| **Target** | `track_popularity` (0-100) |
| **Source** | TidyTuesday 2020-01-21, via the `spotifyr` R package |

## Attribution

The data was collected via the [`spotifyr` package](https://www.rcharlie.com/spotifyr/)
(Charlie Thompson, Josiah Parry, Donal Phipps, Tom Wolff) from the Spotify API, and popularised
through [TidyTuesday](https://github.com/rfordatascience/tidytuesday). It is also distributed on
Kaggle as *"30000 Spotify Songs"* (Joakim Arvidsson). See `dataset_readme.md` for the full
credits and per-column data dictionary.

## How to obtain

1. Download `spotify_songs.csv` from the TidyTuesday 2020-01-21 dataset or the Kaggle
   *"30000 Spotify Songs"* mirror. Direct TidyTuesday CSV:
   `https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-01-21/spotify_songs.csv`
2. Place the file in this `data/` directory so the path is:
   `data/spotify_songs.csv`
3. Open `notebook/spotify-popularity-prediction.ipynb` and run all cells.
