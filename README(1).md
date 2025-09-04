# Crypto Clustering Challenge — Crypto Market Analysis  

This project applies unsupervised learning techniques to cryptocurrency market data.  
It uses clustering algorithms to identify patterns among cryptocurrencies and visualizes relationships in reduced dimensions.

## Repository Contents
- Crypto_Clustering.ipynb — Main notebook for preprocessing, clustering, and visualization
- Resources/crypto_market_data.csv — Dataset of crypto market prices
- LICENSE — GPL-3.0 License

## Project Overview
### Data Preparation
- Load cryptocurrency market dataset
- Normalize price data using StandardScaler
- Prepare data for clustering and dimensionality reduction

### K-Means Clustering
- Apply K-Means to identify groups of similar cryptocurrencies
- Determine optimal number of clusters using the Elbow method
- Visualize clusters in feature space

### PCA Dimensionality Reduction
- Reduce features using Principal Component Analysis (PCA)
- Compare clustering results between original scaled data and PCA-reduced data
- Visualize PCA-transformed clusters

### Analysis
- Compare cluster assignments from full feature space vs PCA
- Evaluate impact of dimensionality reduction on clustering accuracy
- Generate scatterplots for clear visualization of market groupings

## Tools & Libraries
- Pandas — data wrangling
- scikit-learn — clustering (K-Means) and PCA
- Matplotlib / hvPlot — visualization
- StandardScaler — feature normalization

## Quick Start
1. Clone the repo
   ```bash
   git clone https://github.com/Noah-Stevens/CryptoClustering-challenge.git
   cd CryptoClustering-challenge
   ```

2. Install dependencies
   ```bash
   pip install pandas scikit-learn matplotlib hvplot
   ```

3. Run notebook
   - Open `Crypto_Clustering.ipynb` in Jupyter Notebook or JupyterLab
   - Execute cells to reproduce analysis

## License
GPL-3.0 License. See LICENSE file.

## Author
Noah Stevens  
[LinkedIn](https://www.linkedin.com/in/noah-stevens-2a47a3331/)
