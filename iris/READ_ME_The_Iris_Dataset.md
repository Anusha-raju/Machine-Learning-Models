# The Iris Dataset

This dataset consists of data related to classification of the species of the iris flower.

Classification problem : Identifying the categories of the given data by its attributes.

Iris flower consists of 3 categories :

- ***Iris-setosa***

- ***Iris-versicolor***

- ***Iris-virginica***



The total dataset consists of ***150 rows*** and ***6 columns***

Among the 6 columns the 'Id' column is of no significance ,hence the column can be droped.

`iris.drop('Id',axis=1)`



The columns :  Sepal-Width(cm) ,Sepal-Length(cm) ,Petal-Length(cm), Petal-Width(cm) are all the features or the Independant variable.

The column ***'Species'*** is the target variable or the dependent variable.

This folder consists of 2 files :

- Data_Visualization: here python libraries ['numpy', 'pandas', 'seaborn' , 'matplotlib' ] are used for understanding the data and its characteristics
- Modelling : here various ML models are used and compared for its performance.





 The data is a balanced data i.e each category of species has equal number of rows.

`iris.info()`

Although from data visualising the 'Iris-setosa' can be linearly seperable the other two categories can't.

Hence various ML classification model techniques is used in "Modelling.ipynb"

