# Product Recommendation System with NLP and Clustering

This project explores product descriptions to group similar items and build a simple recommendation system.

The main idea is to use text data to better understand the structure of a product catalog and suggest related products based on description similarity.

## Project Scope

The project focuses on three main tasks:

- **text preprocessing** of product descriptions,
- **clustering** similar products into coherent groups,
- **building a basic recommendation system** from these groups.

The recommendation logic is simple: if two products belong to the same cluster, they are treated as similar and can be recommended together.

## Workflow

The notebook is organized into the following steps:

1. **Exploratory Data Analysis**
   - inspect the dataset structure
   - check missing values
   - understand the product description field

2. **NLP preprocessing**
   - clean the raw descriptions
   - lemmatize the text
   - remove stopwords and low-information words

3. **Vectorization and dimensionality reduction**
   - transform text into TF-IDF features
   - reduce dimensionality with TruncatedSVD

4. **Clustering**
   - test and compare clustering methods
   - interpret the resulting groups with visualizations and word clouds

5. **Recommendation system**
   - retrieve products from the same cluster as a selected item
   - display similar items based on cluster membership

## Main Idea

This is not a production-ready recommendation engine.  
The goal is to build a clear and interpretable first approach to product recommendation using only product descriptions.

It is mainly useful for:
- exploring the catalog,
- identifying product themes,
- and creating a basic recommendation logic from text data.

## Tools Used

- Python
- pandas
- matplotlib / seaborn
- scikit-learn
- spaCy
- wordcloud

## Project Structure

```bash
.
├── data.csv
├── notebook.ipynb
└── README.md

# Product Recommendation System with NLP and Clustering

This project explores product descriptions to group similar items and build a simple recommendation system.

The main idea is to use text data to better understand the structure of a product catalog and suggest related products based on description similarity.

## Project Scope

The project focuses on three main tasks:

- **text preprocessing** of product descriptions,
- **clustering** similar products into coherent groups,
- **building a basic recommendation system** from these groups.

The recommendation logic is simple: if two products belong to the same cluster, they are treated as similar and can be recommended together.

## Workflow

The notebook is organized into the following steps:

1. **Exploratory Data Analysis**
   - inspect the dataset structure
   - check missing values
   - understand the product description field

2. **NLP preprocessing**
   - clean the raw descriptions
   - lemmatize the text
   - remove stopwords and low-information words

3. **Vectorization and dimensionality reduction**
   - transform text into TF-IDF features
   - reduce dimensionality with TruncatedSVD

4. **Clustering**
   - test and compare clustering methods
   - interpret the resulting groups with visualizations and word clouds

5. **Recommendation system**
   - retrieve products from the same cluster as a selected item
   - display similar items based on cluster membership

## Main Idea

This is not a production-ready recommendation engine.  
The goal is to build a clear and interpretable first approach to product recommendation using only product descriptions.

It is mainly useful for:
- exploring the catalog,
- identifying product themes,
- and creating a basic recommendation logic from text data.

## Tools Used

- Python
- pandas
- matplotlib / seaborn
- scikit-learn
- spaCy
- wordcloud

## Project Structure

```bash
.
├── data.csv
├── notebook.ipynb
└── README.md

##Possible Extensions

This project could be improved by:

- combining clustering with cosine similarity,
- using richer text embeddings,
- adding product metadata such as titles, categories, or images,
- building a small interactive interface.