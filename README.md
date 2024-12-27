# TMDB Movie Analysis Project

A comprehensive data analysis project that explores and visualizes trends in the movie industry using The Movie Database (TMDB) dataset. This project combines exploratory data analysis, statistical analysis, and machine learning to uncover insights about movie success factors, industry trends, and financial performance.

## Project Overview

This analysis examines multiple aspects of the film industry, including:
- Financial metrics (budget, revenue, and profit)
- Genre performance and trends over time
- Key industry players (actors and directors)
- Content analysis through text mining
- Predictive modeling for movie revenue

## Features

### Data Preprocessing
- Automated cleaning of missing values and duplicates
- Feature engineering including profit calculation and temporal decomposition
- Standardized handling of multi-value fields (e.g., genres, cast)

### Exploratory Data Analysis
- Genre-based profitability analysis with visualizations
- Historical revenue trends broken down by genre
- Correlation analysis between financial metrics
- Popular actors and directors identification
- Text analysis of movie overviews using word clouds

### Advanced Analytics
- Linear regression model for revenue prediction
- Interactive visualizations using Plotly
- Seasonal revenue analysis by release month
- Budget vs. revenue relationship analysis

## Requirements

```python
pandas>=1.0.0
numpy>=1.18.0
matplotlib>=3.2.0
seaborn>=0.10.0
wordcloud>=1.8.0
plotly>=4.14.0
scikit-learn>=0.24.0
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/tmdb-movie-analysis.git
cd tmdb-movie-analysis
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Ensure your TMDB dataset (`tmdb-movies.csv`) is in the project root directory.

2. Run the main analysis script:
```bash
python movie_analysis.py
```

3. The script will generate various visualizations and output:
   - Profitability analysis by genre
   - Revenue trends over time
   - Correlation matrices
   - Actor and director statistics
   - Word cloud of movie descriptions
   - Predictive model performance metrics

## Key Findings

The analysis reveals several interesting insights about the movie industry:

1. Financial Metrics
   - Strong correlation between budget and revenue
   - Identification of most profitable genres
   - Seasonal patterns in movie revenue

2. Industry Trends
   - Evolution of genre popularity over time
   - Changing patterns in movie budgets
   - Most influential actors and directors

3. Predictive Modeling
   - Key factors affecting movie revenue
   - Model performance metrics and limitations
   - Potential areas for prediction improvement

## Project Structure

```
tmdb-movie-analysis/
│
├── data/
│   └── tmdb-movies.csv
│
├── scripts/
│   └── movie_analysis.py
│
├── visualizations/
│   ├── genre_profits.png
│   ├── revenue_trends.png
│   ├── correlation_matrix.png
│   └── wordcloud.png
│
├── requirements.txt
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Future Enhancements

- Integration with live TMDB API data
- Advanced natural language processing for overview analysis
- Additional machine learning models (Random Forest, XGBoost)
- Interactive dashboard development
- Sentiment analysis of movie descriptions
- International market analysis

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The Movie Database (TMDB) for providing the dataset
- Contributors to the Python data science ecosystem
- The open-source community for their valuable tools and libraries

## Contact

For questions or feedback about this project, please open an issue or contact [your-email@example.com].
