# Bosch Production Line Performance Analysis
### Pujan Malavia

![bosch ](https://user-images.githubusercontent.com/19572673/64445028-7f918280-d0a3-11e9-8bbe-9838812a5542.png)

### Link to Dataset:

https://www.kaggle.com/c/bosch-production-line-performance/data

### Abstract:

A good chocolate soufflé is decadent, delicious, and delicate. But, it's a challenge to prepare. When you pull a disappointingly deflated dessert out of the oven, you instinctively retrace your steps to identify at what point you went wrong. Bosch, one of the world's leading manufacturing companies, has an imperative to ensure that the recipes for the production of its advanced mechanical components are of the highest quality and safety standards. Part of doing so is closely monitoring its parts as they progress through the manufacturing processes.

Because Bosch records data at every step along its assembly lines, they have the ability to apply advanced analytics to improve these manufacturing processes. However, the intricacies of the data and complexities of the production line pose problems for current methods.
In this competition, Bosch is challenging Kagglers to predict internal failures using thousands of measurements and tests made for each component along the assembly line. This would enable Bosch to bring quality products at lower costs to the end user.

### Industry:

Engineering/Technology

### Company Information:

Robert Bosch GmbH, or Bosch, is a German multinational engineering and technology company headquartered in Gerlingen, near Stuttgart, Germany. The company was founded by Robert Bosch in Stuttgart in 1886. Bosch is 92% owned by Robert Bosch Stiftung.
Bosch's core operating areas are spread across four business sectors; mobility (hardware and software), consumer goods (including household appliances and power tools), industrial technology (including drive and control) and energy and building technology.

https://en.wikipedia.org/wiki/Robert_Bosch_GmbH

https://www.bosch.us/

### Use Case:

Predict internal failures using thousands of measurements and tests made for each component along the assembly line.

### Initial Dataset(s):
train_numeric.csv - the training set numeric features (this file contains the 'Response' variable)

test_numeric.csv - the test set numeric features (you must predict the 'Response' for these Ids)

train_categorical.csv - the training set categorical features

test_categorical.csv - the test set categorical features

train_date.csv - the training set date features

test_date.csv - the test set date features

sample_submission.csv - a sample submission file in the correct format

### Software:
Python (Jupyter Notebook)

### Data:

The data for this competition represents measurements of parts as they move through Bosch's production lines. Each part has a unique Id. The goal is to predict which parts will fail quality control (represented by a 'Response' = 1).
The dataset contains an extremely large number of anonymized features. Features are named according to a convention that tells you the production line, the station on the line, and a feature number. E.g. L3_S36_F3939 is a feature measured on line 3, station 36, and is feature number 3939.
On account of the large size of the dataset, we have separated the files by the type of feature they contain: numerical, categorical, and finally, a file with date features. The date features provide a timestamp for when each measurement was taken. Each date column ends in a number that corresponds to the previous feature number. E.g. the value of L0_S0_D1 is the time at which L0_S0_F0 was taken.
In addition to being one of the largest datasets (in terms of number of features) ever hosted on Kaggle, the ground truth for this competition is highly imbalanced. Together, these two attributes are expected to make this a challenging problem.

### Data fields
ID 

Response
