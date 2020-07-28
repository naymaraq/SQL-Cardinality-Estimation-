# SQL-Cardinality-Estimation
An accurate cardinality estimation using Recursive Neural Networks


Cardinality estimation is a key component in query optimization. To choose the best executing plan, the query optimizer should precisely estimate the selectivity of a SQL predicate -- the number of rows in relation selected by the predicate without actual execution.



![Model Architecture](https://github.com/naymaraq/SQL-Cardinality-Estimation/blob/master/imgs/treernn.png)

## To train a model run following
`python3 -m benchmark.models.treernn.train`

## To reproduce paper results look at this
`python3 -m benchmark.evaluation.eval`

