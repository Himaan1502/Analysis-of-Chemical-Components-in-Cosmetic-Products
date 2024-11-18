# Analysis of Chemical Components in Cosmetic Products

## Project Overview

This project focuses on analyzing the chemical ingredients in cosmetic products to provide insights into their similarity, identify potentially suitable products, and help consumers make more informed choices. By utilizing machine learning techniques such as word embeddings and dimensionality reduction, we can predict which products might be best suited to an individual's needs, based on ingredient similarity.

In this project, we process the ingredient lists of 1472 cosmetic products available on Sephora using word embedding techniques. We then visualize ingredient similarity using t-SNE, a machine learning method for dimensionality reduction, and generate interactive plots with Bokeh.

## Project Goals

- **Ingredient Analysis:** Analyze and compare cosmetic ingredients to understand which products share similar chemical components.
- **Content-Based Recommendation System:** Develop a recommendation system that suggests cosmetic products based on the similarity of their ingredients.
- **Interactive Visualization:** Use t-SNE and Bokeh to create an interactive visualization that helps users explore ingredient relationships and similarities between products.

## Technologies Used

- **Python:** The core programming language for data analysis and visualization.
- **Word Embedding (Word2Vec):** A machine learning technique to convert ingredient names into vectors.
- **t-SNE (t-Distributed Stochastic Neighbor Embedding):** A dimensionality reduction technique used to visualize high-dimensional data.
- **Bokeh:** A Python visualization library used to create interactive, web-based plots and graphs.
- **pandas & numpy:** For data manipulation and handling large datasets.
- **matplotlib & seaborn:** For creating static visualizations and plots.

## Dataset

The dataset used in this project contains information about 1472 cosmetic products, including their ingredients. This data is sourced from Sephora, and contains product names, brands, and lists of ingredients.

The data is structured in the following columns:
- `Product Name`: The name of the cosmetic product.
- `Brand`: The brand of the product.
- `Ingredients`: A list of ingredients used in the product.

## Installation

To run this project, you'll need to install the following Python libraries:

1. Clone the repository:
   ```bash
   git clone https://github.com/Himaan1502/Analysis-of-Chemical-Components-in-Cosmetic-Products.git
   cd dataset
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

requirements.txt contains the necessary libraries such as:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- bokeh
- gensim

## How It Works
1. Data Collection
Collect cosmetic product data, including ingredient lists, from Sephora or other sources.
2. Data Preprocessing
Clean the data by removing any missing or incorrect entries.
Tokenize the ingredient names for further analysis.
3. Feature Extraction (Word Embedding)
Use word embedding techniques (like Word2Vec) to transform each ingredient into a numerical vector.
4. Dimensionality Reduction (t-SNE)
Apply t-SNE to reduce the high-dimensional word embeddings to 2D or 3D space for easier visualization.
5. Visualization (Bokeh)
Create interactive plots using Bokeh to visualize ingredient similarities and clusters.
6. Recommendation System
Build a content-based recommendation system based on ingredient similarity. By comparing ingredient vectors, the system recommends products with similar chemical components.
7. Reporting & Output
Generate visual reports or dashboards to help users interpret the results and make informed decisions about which cosmetic products to choose.
  
## Example Output
Once the analysis is complete, the following outputs will be available:

- Interactive Ingredient Similarity Plot: A 2D or 3D visualization that shows how ingredients in different cosmetic products relate to each other.
- Cosmetic Product Recommendations: A list of recommended products based on ingredient similarity.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
The dataset used in this project was sourced from Sephora. Thanks to their publicly available data on cosmetic products.
Thanks to the creators of the libraries Word2Vec, t-SNE, and Bokeh for providing the tools that made this analysis possible.
