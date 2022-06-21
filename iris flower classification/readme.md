this is the iris flower classification 

hello everyone I am back with another wonderful post
I have created my first data science project on iris flower classification.
You might be thinking yeah it's not a new thing before me most of the tech geeks have done this. But in my vision project should have 5 Phases
# 1 Getting the knowledge and understanding of the dataset is important
# 2 Why are you analyzing the data what is the need for this step? But if you don't know about your data set how will you know about the parameter to be used, what are the features, what is targeted, or what we need to predict.

# 3 Everyone forgets about cleaning the duplicate data from the dataset. Honestly, I have gone through many notebooks, and sources but I have that no one is cleaning the duplicate data from the data set.

# 4 After this we need to visualize the data through the graphs, chat, and plot the data.
Note I have plotted a few extra graphs just to understand the difference between the type of graphs

# 5 model
first problem you will encounter is what model should be used to predict the targeted value. So first we need to understand what we have to target.
According to my vision, i want to know the species or class type according to the feature or parameter I got.
For example, I have got a new iris flower with sepal length, sepal width, petal width, and petal length but I don't know about the species?

To predict the species i have trained three models
#  1 linear regression
# 2 logistic regression
# 3 KNN

But i want to make you understand that we cant use linear regression in this dataset to classify the species type as linear regression is a continuous form of data and its difficult to make the prediction but if you want to use linear regression you can predict the sepal width by giving sepal width.

So I used logistic regression and KNN to predict the species

# 6 Last but not the least this is the most important phase of the model
after your model is trained and tested you need to evaluate the model and for evaluating the model you need to input the random data to see the outcome if your model is predicting the right targeted value then only you can deploy the model
