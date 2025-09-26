[![Open in Jupyter](https://img.shields.io/badge/Open%20in-Jupyter-orange?logo=jupyter)](notebooks/code.ipynb)
&nbsp;
[![Open in PowerPoint](https://img.shields.io/badge/Open%20in-PowerPoint-red?logo=microsoftpowerpoint)](slides/Presentation%20Slides.pptx)

# Iowa Liquor Sales Analysis
This project analyzes over 3 million liquor transactions in Iowa from 2012 to 2025 to uncover key insights about alcohol consumption patterns, product profitability, and location-based performance.

## Project Structure
- `notebooks/code.ipynb` - Full exploratory analysis, modeling, and visualizations.
- `slides/Presentation Slides.pptx` - Final presentation summary with business recommendations.
- `requirements.txt` - Python environment setup.

## Key Insights
- **Black Velvet** is the most purchased product, but **Tito’s Vodka** yields more profit.
- **Canadian Whiskey** offers higher returns than American Vodka in top 3 cities.
- The Iowa government could optimize excise taxes and inventory logistics.

## Tools & Technologies
- SQL
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebooks
- PowerPoint
- Dimensional Modeling (Facts & Dimensions)
- AWS (Amazon Web Services):
    - Used for cloud storage and retrieval of large datasets (via S3)
    - Enabled scalable access and download of 600MB+ transactional data

## How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook: `notebooks/code.ipynb`

## Data Source
- Provided by the **Iowa Government**
- [Official dataset link](https://istm-4212.s3.us-east-1.amazonaws.com/Iowa_Liquor_Sales_20250416.zip)

## Contributors
- Jonathan Beck, Henrique Cassol, Matthew Wolf
