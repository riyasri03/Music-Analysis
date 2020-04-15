# Music-Analysis

ABSTRACT

Today, several music platforms provide thousand of new songs; it becomes ambitious to find highly appealing or like-able songs 
within such loads of data. In our project we have considered various attributes like acousticness, danceability, energy, 
instumentalness, key, loudness, mode, speechiness, valence and artist to find whether the audience will like the song or not. 
“1” is used to denote that the audience will like the song and “0” is used to denote that they won’t like that song. 
We have built a classifier that could predict whether or not the audience will like the song. Whole data is divided into 
two parts. 80% of the data is used as training data and the rest 20% as test data. We have used three algorithms to reach to our
result. 
1.Decision Tree 
2. Random Forest  
3. Multiple Linear Regression



EXPLANATION:


1.First of all we have to import some python libraries like numpy (for handling numeric data), Pandas(for reading file from
the system), matplotlib(for plotting graphs) and sklearn (for using the already made training algorithms).
 
2.Read the dataset using pandas libraby.

3.Define the features and output from the imported dataset.

4. Now split the dataset into two parts (here we took 80:20) using test_train_split.

5.Now import the required Algorithm (Random Forest ,Multiple Regressor , Decision Tree)

6.Train the model using the selected algorithm. 

7.Now predict the output using x_test dataset and store it in y_pred. 

8.Compare the y_pred output with the y_testand get the accuracy of the model by using inbuilt accuracy function in sklearn.

9.Print the score.




