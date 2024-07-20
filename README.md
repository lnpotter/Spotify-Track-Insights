# Spotify Track Insights

This project analyzes Spotify track data to derive insights into track popularity and characteristics. The dataset used is from Kaggle and includes information on the most streamed Spotify songs as of 2024.

## Dataset

The dataset is sourced from Kaggle:
- **Dataset Title**: Most Streamed Spotify Songs 2024
- **Dataset URL**: [Kaggle Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/data)

### Dataset Description

The dataset contains the following columns:
- `Artist`: Name of the artist
- `Track Name`: Name of the track
- `Track Score`: Score assigned to the track
- `Spotify Streams`: Number of Spotify streams
- `All Time Rank`: All-time ranking of the track
- `Spotify Playlist Count`: Number of playlists featuring the track
- `Explicit Track`: Whether the track is explicit
- `Release Date`: Release date of the track (if available)

## Analysis

The project includes the following analyses and visualizations:

1. **Univariate Analysis**
   - Distribution of Track Score
   - Count of Explicit Tracks

2. **Bivariate Analysis**
   - Relationship between Track Score and Spotify Streams
   - Relationship between Track Score and All Time Rank

3. **Correlation Analysis**
   - Heatmap showing correlation between numerical features

4. **Additional Analyses and Plots**
   - Count of Tracks by Artist
   - Distribution of Spotify Streams by Explicit Track
   - Trend Analysis Over Time
   - Artist Popularity by Streams
   - Track Score Distribution by Explicit Content
   - Spotify Streams Distribution by Track Score
   - Pairwise Relationships
   - Heatmap of Top 10 Artists' Streams by Month

## Installation

To run the analysis, you'll need Python and the following libraries:
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`

You can install these libraries using pip:

```bash
pip install pandas matplotlib seaborn numpy
```

## Usage
1. Clone the Repository:
```bash
git clone https://github.com/lnpotter/spotify-track-insights.git # or
git clone https://github.com/yourusername/spotify-track-insights.git #if you forked the repository
```
2. Navigate to the project directory:
```bash
cd spotify-track-insights
```
3. Update the path to the dataset in the Jupyter Notebook and run the analyses.
```bash
df = pd.read_csv('path/to/your/dataset.csv', encoding='ISO-8859-1')
```
4. Execute the Jupyter Notebook cells to view the visualizations and analyses.

## Contributing
Feel free to open an issue or submit a pull request if you have suggestions or improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/lnpotter/Spotify-Track-Insights/blob/main/LICENSE) file for details.

## Acknowledgements
- Kaggle for providing the dataset.
- Libraries used in this project: Pandas, Matplotlib, Seaborn, and Numpy.