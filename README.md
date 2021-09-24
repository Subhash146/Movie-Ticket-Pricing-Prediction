Statement :-
I have taken the data set of Movie ticket Prices Sale history of movies in cinemas. The granularity is show time. It means the total sales computed by date, cinema, movie, show time. Also occupation percent (on available cinema capacity) computed at show time. Some tickets might cancelled due to reservation or any other reasons.

This DataSet Contains The Cinema ID, Total sales, Total capacity of the cinema Etc.

What I have done?

First I imported the dataset into colab and analyze and understood the data set properly by going through some of the info like columns, info, etc.

After analyzing, I found correlation between all colums and plotted the graph to find out relation between different columns using heatmap.

Then I spillted the data set into train set and test set. I will use train set to create and train the model and test test to further test and found the accuracy at the end.

I applied Linear Regression and fitted the data set and then did the prediction on the test set.

I scatter the prediction of Y (student condition) as per the input X_test using matplot library and then plotted using seaborn library.

At last I found the accuracy of the prediction.
