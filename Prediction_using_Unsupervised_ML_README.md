# task_2_grip_tsf_tasks 
# Prediction_using_Unsupervised_Machine_Learning

We have to choose the K that has minimum inter-cluster variation or total within sum of squares.(WSS)
WSS is used to find compactness of clustering .There is no hard and fas rule to calculate the value of K that has minimum Wss
value to calculate the value of K that has minimum wss value but we have some methods by which we can make the approximation about the best value of K.


# Elbow Method:-
We will provide it with different number of k value , This method will try to find the total WSS for a given K values , but the number of cluster should be chosen so thatadding another cluster doesn't improve total WSS
wherver the variance of WSS stops dropping significantly that will be chosen as the optimal value for K.        
