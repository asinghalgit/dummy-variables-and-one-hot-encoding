# dummy-variables-and-one-hot-encoding
This is an example of using dummy variables and one hot encoding in ML.

Following is training data set where feature set includes area represented as a number and
town as text. ML models do not understand text data. It only understands number. 

![Training Data](2.jpg)

![Categorical Variables](1.jpg)

1. Nominal variables do not have any order relationship.
2. Ordinal variables like degree has order. For example - master is higher than graduate.

Here, in training data set we are dealing with nominal variables and simple integer encoding will not work. Simple
integer encoding is assigning numbers to sequential data like 1 to monroe township and 2 to west windsor and 3 to 
robinsville. If we apply simple integer encoding (also known as label encoding) then model will compare it to one another
which does not make any sense.

Hence, a technique is used here called one hot encoding.
