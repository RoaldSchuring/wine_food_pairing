# Wine Food Pairing

### Introduction

In this repository, we build an NLP-based method for pairing food with wine. This is spread over two notebooks:

- Wine Food Pairing Data Prep.ipynb: this is the notebook file in which we create wine and food embeddings and prepare all the components we need to produce wine suggestions.
- Wine Food Pairings.ipynb: this is the notebook file in which we lay out the rules for pairing wine with food, and visualize the results.

The raw data for these notebooks comes from two different sources. The corpus of wine reviews was too large to be added to this repository. You can find it at https://www.kaggle.com/roaldschuring/wine-reviews. If you are interested in scraping more wine reviews, please see the scraper used to mine the data from www.winemag.com in this GitHub respository: https://github.com/RoaldSchuring/studying_grape_styles. The corpus of food reviews can be downloaded at https://www.kaggle.com/snap/amazon-fine-food-reviews.

Other files in this repository include:

- varieties_all_geos_normalized.csv: a table normalizing the various geography tags of the wines found on winemag.com
- list_of_foods.csv: a list of foods used to establish boundaries for nonaroma values in our foods

### Technologies

- Python
- Jupyter Notebook

### Project Description

Pairing wine with food is somewhat of a dark art. What ultimately makes for great pairings is a delicate balance between the body, non-aroma and aroma characteristics in the wine and in the food. In this repo, we use data science techniques and the prevailing theory on wine/food pairing to build a wine pairing engine.

### Getting Started

1. Clone this repo.

2. Run the web scraper available in the other repository outlined above to get a full and fresh set of wine reviews.

3. Download the Amazon fine foods dataset.

4. Run Wine Food Pairing Data Prep.ipynb to create all the data artefacts needed to produce wine pairings.

5. Run Wine Food Pairings.ipynb to produce and visualize wine pairings.

### Authors

Roald Schuring
