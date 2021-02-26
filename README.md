# Analyzing Wine Quality Scores
Final Project for Northwestern Data Analytics Bootcamp
### By: Diane Witt, Jeni Lamoureux, Lenn Grayes and Allison Palka

![logo.jpg](attachment:logo.png)

# Our Dataset

This is our Analysis and Exploration of Vinho Verde wine qualities. 

"Vinho Verde" is Portuguese for "green wine" and refers to a region in the lush, green, rolling hills of Northern Portugal. This region starts just below the Portuguese-Spanish border, and extends all the way to the Atlantic Ocean. 

Our analysis comprised ot testing multiple Machine Learning classifier and regression models using both the red and white wine quality datasets to determine the most accurate model for predicting the quality of Vinho Verde wines for use in a consumer buying guide. 

### Citations

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016
[Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf
[bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib

https://data.world/food/wine-quality/workspace/project-summary?agentid=food&datasetid=wine-quality

https://waterhouse.ucdavis.edu/whats-in-wine

https://vinepair.com/wine-blog/7-things-you-need-to-know-about-vinho-verde/

Relevant Information:

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine.
For more details, consult: http://www.vinhoverde.pt/en/ or the reference [Cortez et al., 2009].Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables
are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

We found this dataset to be extremely organized and clean--which allowed us to easily analyze data and explore Machine learning preprocessing.


<hr>

## Attribute Info
**Input variables (based on physicochemical tests):**

1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol

**Output variable (based on sensory data):**

12. quality (score between 0 and 10)

## Attribute Description

Variable | Description
------------ | -------------
Fixed Acidity | Fundamental property of wine, limiting sourness
Volatile Acidity | Used as indicator of wine spoilage
Citric Acid | Primary acid in fruit, used to add acidity to wine
Residual Sugar | Leftover natural sugars from fermentation,sweetness
Chlorides | Amount of salt in wine
Free Sulfur Dioxide | Preservation ability; prevents microbial growth
Total Sulfur Dioxide| Amount of free/bound forms of SO2, undetectable
Density | Wine density close to that of water, dry(less) and sweet(more)
pH | Describes how acidic a wine is on pH scale of 0(high)-14(low)
Sulphates | Wine additive that can contribute to SO2 levels
Alcohol | Percent of alcohol content 
quality | Content in the second column


<hr>

## Models Reviewed

- Random Forest
- Logistic Regression
- Gaussian Naive Baise
- Decision Tree
- K Nearest Neighbor
- MultiLayer Perceptron
