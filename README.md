# Municipality Boundaries and Election Data Processing

This Jupyter Notebook automates the process of downloading, extracting, and visualizing German municipality boundaries along with processing and merging election data.

### Features
- **Download Municipality Boundaries**: Fetches administrative boundaries from the [Bundesamt für Kartographie und Geodäsie (BKG)](https://gdz.bkg.bund.de/).
- **Extract and Process Shapefiles**: Extracts the required shapefile and saves it as GPKG.
- **Process Election Data**: Cleans and restructures election results from an Excel file.
- **Merge Boundaries with Election Data**: Joins the processed election data with the municipality shapefile and exports the results as a GeoPackage.

### Requirements
Ensure you have the following Python libraries installed:
```bash
pip install geopandas pandas matplotlib tqdm contextily requests
```

### Output Files
- `gemeinde_raw.gpkg`: Raw administrative boundaries.
- `bb_election_results.gpkg`: Processed election data merged with municipality boundaries.

### Next steps
- automating the paths
- wraping it into functions

