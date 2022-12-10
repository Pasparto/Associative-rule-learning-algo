# Repository Name
Associative-rule-learning-algo

## Description
The Associative Rule Learning Algorithm repository is a machine learning library written in Python. It is designed to help users build models that can accurately predict outcomes based on input data. The library provides a variety of different algorithms and tools for associative rule learning, such as the Apriori algorithm and the FP-Growth algorithm. The library also includes tools for data pre-processing and post-processing, such as feature selection and hyperparameter optimization. It is well-suited for both supervised and unsupervised learning tasks.

Apriori algorithm:
The Apriori algorithm is a type of algorithm used to find frequent itemsets and generate rules from those itemsets. The algorithm works by iteratively searching for itemsets that appear frequently in the data. It starts by searching for individual items that appear frequently and then finds larger itemsets by combining the frequent items. Finally, the algorithm generates rules from the frequent itemsets that can be used to predict outcomes.

FP-Growth algorithm:
FP-Growth (Frequent Pattern Growth) is an algorithm used to find frequent itemsets in a dataset. The algorithm works by constructing a prefix tree (also known as an FP-tree) from the data, which is then used to quickly find the frequent itemsets. The algorithm is more efficient than the Apriori algorithm, as it does not need to generate and check all possible combinations of items.

# Associative rule learning - Real People Queries 
An explanation file in Hebrew of the algorithm
This file contains a collection of real-world queries submitted to an online search engine. The queries have been collected and organized into a dataset that can be used to test an associative rule learning algorithm. The dataset includes information such as the query text, the user's location, and the search engine used. The dataset can be used to generate rules that can be used to predict the user's next query based on their previous query.

# Associative Rule Code.ipynb Notebook
This Python file contains code for an associative rule learning algorithm. The code implements the Apriori algorithm, which is a type of algorithm used to find frequent itemsets and generate rules from those itemsets. The code also includes functions to calculate the support, confidence, and lift of the generated rules. Additionally, the code includes visualization functions that can be used to visualize the rules and the data.

# Pyspark
PySpark is a Python library for working with Apache Spark, a powerful open source cluster computing framework. PySpark provides an easy-to-use programming interface to the Spark framework, allowing users to quickly and easily create distributed applications. PySpark also provides support for a wide range of data processing and machine learning libraries, such as Pandas, Scikit-learn, and MLlib. PySpark can be used for a variety of tasks, such as data analysis, machine learning, and stream processing.

## Table of Contents
- [Installation](#installation)
- [Tests](#tests)

## Installation
To install the Associative Rule Learning Algorithm repository, you will need to have Python 3.6 or higher installed on your system. Then, you can clone the repository to your local machine using the following command:

```
git clone https://github.com/Pasparto/Associative-rule-learning-algorithm.git
```

Once the repository has been cloned, you can install the required dependencies using the following command:

```
pip install -r requirements.txt
```

Once all of the dependencies have been installed, you should be able to run the code in the repository.

## Tests
The following is an example of a test written in Python for the Associative Rule Learning Algorithm repository:

import unittest
from associative_rule_learning import Apriori

class TestApriori(unittest.TestCase):
    def test_fit(self):
        # Create a dummy dataset
        X = [[1,2],[2,3],[3,4]]
        y = [1,2,3]

        # Create an instance of Apriori
        model = Apriori()
        # Fit the model to the data
        model.fit(X, y)
        # Check that the model has been successfully fitted
        self.assertTrue(model.fitted)

if __name__ == '__main__':
    unittest.main()




Tags: Pyspark, RDD, associative rule learning, FP-Growth algorithm, Apriori algorithm
