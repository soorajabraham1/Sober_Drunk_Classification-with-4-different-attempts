# Sober_Drunk_Classification-with-4-different-attempts
Here I triedOto classify the faces of people based on sober or drunk.  ⧹  ⧹ 
I compare different classifiation algorithms such as logistic regression, Random forest and Gradient Boost.
In the first method, I diretly tried train using entire dataset without cleaning it.
Seond I cleaned the dataset and tried to classify into 4 classes.
Third, I considered 0 Glasses wine and one glass wine as sober and 2 glass wine and 3 glass wine a s drunk and trained without cleaninmg the dataset.
finally,I considered 0 Glasses wine and one glass wine as sober and 2 glass wine and 3 glass wine a s drunk and trained with cleaned dataset. 


Steps done:
On detailed analysis of the dataset, I came to know that there is a relation between the emotions of the people and the drunkenness.
In the given dataset, peoplre tend to be more relaxed and happy on being drunk. so i thought of first extrating the emotions of the people and then try to classify them based on sober or drunk.
for that I chose deepface a deep learning model by face book. I extrated the perentage of each emotions. so the output was a set of values for happy, angry, disgust ,sad,etc..
now I used the logistic regression, random forest and gradient boost  to train based on the given datas. ⧹  ⧹ 
