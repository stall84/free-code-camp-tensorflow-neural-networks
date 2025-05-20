## Core Machine Learning Algorithms (with TensorFlow)

_note: without going into too much detail on the algorithms we've already noted and practiced in [other course-repositories](https://github.com/stall84/ml-basics-exercises-notes/tree/main/notes) and dedicating more time to those that are newer to us._

- **Linear Regression:** See previous [notes here](https://github.com/stall84/ml-basics-exercises-notes/blob/main/notes/6-simple-linear-regresion.md)

- **Classification**

- **Clustering**

- **Hidden Markov Models**

## Concepts Core To All ML Training & Modeling

- ### Training vs Testing Data
- When we train models, we need two sets of data: training and testing (a.k.a _evaluation_).
- The training data is what we feed to the model so that it can develop and learn. It is usually a much larger size than the testing data.
- The testing data is what we use to evaulate the model and see how well it is performing. We must use a seperate set of data that the model has not been trained on to evaluate it.
- Typically you'll use something like a 70-30 split of the total training data to split training and evaluation(testing) sets respectively. So if you have 1000 rows of data, 700 rows would be used to train, and the remaining 300 would be used for the eval/test set

#### Categorical Data:

- values like 'yes' or 'no' or in the Titanic exercise example, Class of the passenger 'First', 'Second' or 'Third' have to be encoded to an interger value for them to make any meaningful influence on the model
