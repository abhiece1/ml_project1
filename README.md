# ml_project1
This is a readme file wherein , the approach and the code dependencies have been shown
Now seee…..
Here we have taken the data of nasa — nearest earth objects. Then we interpreted that what all could we possibly draw out from this data..


Now we had 10 types of columns wherein the data represented id, name ,estimated diameter, orbiting_body, relative_velocity, etc..
Out of which , as we could see, the data of id ,name won’t help us in any kind of comparison b/w different data points as these entries are different for every data point..
Also,since the orbiting body is Earth and the sentry object is False, ie same kind of data is present, hence these columns are of no use , hence should be dropped..
 

The variable we created is named as— train, also ,we have plotted the heat map which shows the dependence of one column over the other, in the scale of 0 to 1.. for eg , take the case of est_diameter_min , est_diameter_max,
In this case , the values of the data points of these attributes/columns are near to the same , so hence the heat-plot shows no variation in its values
We have also shown a count plot for ‘hazardous’ , which shows that how much ‘0’s’ and ‘1’s’ does the column of hazardous contain in our data ……
Now after looking at these plots , we get the idea of about how much of our data is changing with increasing data points and how much of it is not changing much..
Now that we’ve seen our data , then we train our model using train_test_split which belongs to the sklearn library.., and split our data into training set and testing set..by making “test_size=0.3” we ensured that the data was divided into 70:30 ratio for training:testing.
 Now after training our model , we try to predict the accuracy and precision, f1_scores of our data.. by implementing different kernels from Support vector machines Classifiers..
Support vector machines (SVMs) are a set of supervised learning methods used for classification, regression and outliers detection.
The advantages of support vector machines are:
Effective in high dimensional spaces. 
Still effective in cases where number of dimensions is greater than the number of samples.
Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
We can also create our own kernels in svm that we would like to see ..


Now after we’ve implemented the kernels on train and test variables , we’ve tried to show comparative study on the “Accuracy”, “Precision", “f1-scores” of different kernels
(Do see that since the linear kernel was taking too long , so it is not implemented in the  comparative study though the code is mentioned .. )
