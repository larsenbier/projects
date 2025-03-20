# Projects

## Data Science and Coding

### Inception Network in Pytorch - [View Here](https://github.com/larsenbier/DataRes-Research-Team-Coding-Assessment---Inception-Net)

*Project completed as part of the Research Team Coding Assessment for DataRes at UCLA, 2024.*

**Project:** Use pytorch to implement machine learning algorithms and deep neural networks.

* Used pytorch to implement linear, logistic, and softmax regression from scratch.
* Used the pytorch.nn module to implement multiplayer perceptrons, shallow conv nets, and a deep convolutional neural network class based on the GoogLeNet Model from "Going Deeper With Convolutions" (Szegedy et. al., 2014).

### Regression Analysis of Housing Prices - Kaggle Competition - [View Here](https://github.com/larsenbier/Regression-Analysis-of-Housing-Prices---Kaggle-Competition)

*Project completed independently, 2024.*

**Project:** Analyzing what factors influence housing prices and building a gradient boosted decision tree to predict housing prices from the [Ames Housing Dataset](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset).

* Performed extensive data imputation by analyzing the dataset features.
* Created seaborn and matplotlib visualizations to aid in exploratory data analysis and transforming the data.
* Performed label encoding, dimensionality reduction with PCA, and feature selection to prepare the dataset for machine learning applications.
* Built an XGBoost decision tree and performed extensive hyperparameter tuning, cross-validating over 5000 combinations of 6 different hyperparameters using random search over a carefully selected hyperparameter space.

### Census Bureau API Data Scraper - [View Here](https://github.com/larsenbier/SVED-Census-Data-Scraper)

*Project completed during internship at Sun Valley Economic Development ([SVED](https://sunvalleyeconomy.com/)), 2024.*

**Project:** Employing the US Census Bureau's American Community Survey [API](https://www.census.gov/data/developers/data-sets/acs-5year.html) to scrape data for publishing in SVED's [Economic Profiles](https://sunvalleyeconomy.com/profiles/#2022) and integrating the data scraper into existing excel data pipelines.

* Wrote custom functions to web-scrape and organize Census data from 6 locations over 20+ years of annual surveys.
* Used pandas to perform extensive data manipulation to achieve a desirable format for the data.
* Used openpyxl to parse existing Excel spreadsheets and insert new data without compromising existing data.
* Thoroughly documented the code so that future SVED interns can use it to save time and money on data gathering.

### Abstract Polynomial Toolkit in Python (PyPolynomial) - [View Here](https://github.com/larsenbier/PyPolynomials)

*Project completed independently, 2024.*

**Project:** Create a python module to perform a wide variety of operations on polynomials with coefficients in rings/fields beyond the real numbers. This project was inspired by my first course in abstract algebra.

* Created a python Polynomial class to handle operations on polynomials with coefficients in the following rings: Z, Q, R, C, Z/nZ, and F[x]/p(x) , where F is a field and p(x) is irreducible in F (i.e. field extensions).
* Implemented algorithms to compute polynomial inverses, greatest common divisors, and division, while using abstract algebra to safeguard the algorithms against situations where the they may fail.
* Created Ring and Field classes with the flexibility to support many abstract, user-defined rings, fields, and polynomials.

### Data Blogging Visualizations - [View Here](https://github.com/larsenbier/DataRes-2023-24-Blog-Notebooks/blob/main/README.md)

*Project completed for DataRes at UCLA, 2024.*

**Project:** Analyze datasets to uncover trends and produce compelling visualizations for our Medium blog.

* Cleaned data and performed exploratory data analysis using pandas, matplotlib, seaborn, and plotly.
* Produced advanced yet clear charts and animated charts using plotly express.
* Analyzed connections in the film industry using graph theory.

## Math

### Collection of Proofs on Surjectivity of the Exponential Map from $\mathfrak{so}(3)\rightarrow\text{SO}(3)$ and $M_{n\times n}(\mathbb{C})\rightarrow\text{GL}_n(\mathbb{C})$

*Project completed as part of Math 110B, Group Theory, at UCLA*

**Project:** A short extra credit paper proving properties of the matrix exponential and investigating some examples of sets on which this operation acts surjectively. The motivation was to do an independent study of Matrix Lie Groups. Read the paper [here](./Cases_of_Surjectivity_of_the_Matrix_Exponential__MATH_110B_Paper.pdf).
