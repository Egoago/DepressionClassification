# WineQuality
This project was created in 2021 spring semester for AIT Deep Learning course.
The only author is Ágoston István Csehi.

## Topic
My goal is to measure the quality of wine based on some chemical parameters. The main idea is to construct a Deep Neural Network based on the white wine dataset and after that test how well does it work on the much smaller red whine dataset, which has the same parameters.

## Data
The datasets was retrieved from [here](http://www3.dsi.uminho.pt/pcortez/wine/).
The white wine dataset consist of 4898 rows, while the red one only has 1599.
Both has 12 columns.

### Parameters:

#### Input variables (based on physicochemical tests):
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
12. 
#### Output variable (based on sensory data):
12. quality (score between 0 and 10)

## Acknowledgments
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
