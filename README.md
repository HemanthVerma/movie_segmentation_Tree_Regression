# movie_segmentation_Tree_Regression
We are going to use a decision tree regression algorithm for segemntation of movies
we import the all the required libraries
We use pandas to convert our CSV file to a data frame
Then we perform the tasks of data cleaning
we use train_test_split for splitting our data into 80% for training and remaining 20% for test
we use mean_squared_error and r2_score as performance characterstics
we crete dot file for the tree for making it to plot
we use Pydotplus for making the graph
and create a png type Image


Problems that can be occured in plotting the tree

1. pydotplus not found:

solution : go to conda prompt and install pydotplus with the below command
-> pip install pydotplus


2.graphviz error:

solution: try to check the graphviz directory or else install from the conda prompt
-> conda install -c conda-forge python-graphviz
