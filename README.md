## Finding Donors for CharityML

In this project, I employed several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. I assessed the best candidate algorithm from preliminary results and further optimized this algorithm to best model the data.

My goal with this implementation was to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will see) infer this value from other publically available features.

The dataset for this project originates from the UCI Machine Learning Repository. The dataset was donated by Ron Kohavi and Barry Becker, after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid". You can find the article by Ron Kohavi online. The data I investigate here consists of small changes to the original dataset, such as removing the 'fnlwgt' feature and records with missing or ill-formatted entries.

Algorithms deployed: Random Forest Classifier, Naive Bayes, and Support Vector Machine![image](https://user-images.githubusercontent.com/32248180/162636746-59b74447-737d-4570-8d8c-75ad38dd9511.png)
