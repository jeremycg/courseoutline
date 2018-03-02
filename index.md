## Course Outline

Data Science is a rapidly evolving industry, combining programming, statistics and hacking
into a new field.

A typical data science work flow can start with acquiring data from an API or database,
validating and cleaning, carrying out exploratory data analysis and statistical tests,
defining and fitting a machine learning or deep learning model, and reporting results or pushing
the model to production.

We can pull out the major topics required to carry out this pipeline, and teach them to you in a 10 week course!

### Introduction and Setup
- jupyter notebooks
- anaconda as a system
- text editor choice
- learn the environment

### Python Language
- introduction
- control flow
- functions
- classes
- common packages
- pandas/numpy/scipy

### R Language
- basic introduction

### Working with data
- data munging
- exploratory data analysis
- data validation
- basic data structures
- databases - SQL
- Spark
- Scraping and APIs

### Communicating with Data
- notebooks and markdown
- graphing - matplotlib, seaborn, bokeh
- graphing - plotly
- report making
- report automation
- working with excel

### Basic Statistics
- probability distributions
- hypothesis testing
- ANOVA
- linear and logistic regression
- AB testing, experimental design
- modeling
- introduction to Bayes

### Basic Linear Algebra
- numpy
- matrix calculations
- functions and derivatives
- cost functions
- gradient descent

### Machine learning
- methodology - supervised vs unsupervised
- train and test
- clustering and classification - kmeans, SVM, decision trees
- measuring and fitting models

### Deep Learning
- theory - why neural networks?
- tensor flow
- pytorch
- worked examples

### Working as a developer
- version control
- github and github webpages
- automated testing
- linux/shell
- debugging and finding help
- working in the cloud
- workflows in a team
- deploying models to production
- interviewing for data science positions


## Capstone

The capstone project is intended to be an independent, but guided, final project to cement your skills
and showcase your work to potential employers.

Capstones should be completed as jupyter notebooks, shiny apps, or other webpages or apps,
so that they can be shared and remixed.

Numerous cities, countries and NGOs have recently started releasing open data sets
and Toronto is no exception.

You can find the city of Toronto's [open data page here](https://www.toronto.ca/city-government/data-research-maps/open-data/)

Toronto has 272 distinct open data sets available for analysis. Take a look at some of the apps and reports that have
been made using the data [here](https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-gallery/).
If Toronto doesn't inspire, choose any other municipal or governmental dataset.

For your capstone, choose a dataset that interests you, and think of a question, visualisation,
model, or report that would be of interest to the wider public. Can you predict potholes on the
401? Can you break down which kinds of restaurants get closed for health violations? Can you figure out why your
streetcar is always late?

Once you have an idea of your desired topic, spend some time discussing with your mentor
to figure out best approaches, and how to proceed.

### More Detailed example:

311 is a line which residents can call to report city related matters, and the anonymised data is
  shared through an API which we can access.

Graffiti reports are tagged with a location, time reported, and one of five categories.

Using the data from the open data portal:
1. Create a visualisation of the data - a heatmap might be a good choice. Try using the google maps api to make it interactive
2. Investigate the different categories of graffiti - do they show a temporal or spatial pattern? How can we test this?
3. Try removing the category from the graffiti label - can we cluster the reports back into their labels? What are the main predictive variables?
4. The reports span a long time period - Create a model which explains at least two years of data. Some explanatory
details that would be worth considering are - season, weekday/weekend, school holidays, temperature
5. Using your model, predict the next few weeks of graffiti - how confident are you? How would you measure your expected predictions?
