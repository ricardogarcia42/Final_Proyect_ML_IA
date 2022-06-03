# Final_Project_ML_IA
This repository is for a final proyect submission for the emphasis class of the Pontificia Universidad Javeriana titled "Inteligrncia Artificial".

Proyect title: Model prediction for loan status
Student: Ricardo Garcia

Intro:

As we are coming to the end of our undergrad program in Electrical Engineering there will be many other challenges we will have to handle in our daily lives. Starting a job and being able to grow financially is a challenge for all of us in the upcoming future and for the rest of our lives. This is why I have chosen to do this project to have a small idea about loans and get to apply machine learning to predict the loan status of people that have applied for a loan. Here you will be able to look at what variables and the specifics of which things do a lender brings into consideration when applying to a loan. Applying machine learning to this classification project will give the outcome of the loan status depending on the variables taken into account. 
For more information about the varibales we will be considering go to the variables.xsl file in the repository. 

Developement:

To conceive this machine learning project we will have to use a dataset with the name loans.csv on the files of this repository. The dataset is not complete for this we will perform some data engineering where the visualization methods are applpied to understand the data we have. As this dataset is not the biggest one, it is not recommended to erase the information that is missing as the result and behavior of our training model can be very poor. For this reason I have filled the missing information with its averaged values to have the most information available to work with for the numerical values. 
As well as filling the missing data of text values will be filled with the most common result of this text variables. 

Trining a model for this project from the dataset will have some modification on the relevant text values. Before training our model it is important to notice the conversion of text values to numerical values, assigning them a value of 0,1 or 2 dependig on the outcome of each text variable. If there are only two option it will turn in to 1 or 0 if it has 3 then wi will give the values of 0,1 or 2. 

After we have done this data engineering work we will be able to apply our machine learning methods and train our model. The interest of the project is predicting on the loan status of an applicant depending on the variables taken into account for a loan. For the project after splitting the dataset to train a model 2 method of classification will be used Support Vector Machine (SVM) and KNN model. For the verification of the models the confussion matrix will be used to test the accuracy of the model for each othe the methods used and how well is its prediction. After this a dimensiional reduction via PCA will be performed and we a new verification of the methods will ve evaluated to see of the accuracy of the model has improved or not. 

Support Vector Machine: 

This method of classification is used for supervised learning models and regression analysis. SVM uses the data given as vectors in an n-dimensional space where the SVM is incharged of the contruction of a hiperplane where the margin is being maximized of the different data of the data given. It measures the distance between two classes and is able to create a classification depending on the distance it has to the separation between both sets of data. 

KNN: 

KNN is a method of classification for supervised learning models. KNN measures the distance between the point of a data set (K) with respect to the other data points to decided if the distances from the main point is near to this K point and classifies it. This can be donde for several K, but remember to be carefull choosing the value of K it can result in a very bad conclusion if it is not choosen right. 

For more info regarding this two methods I suggest you to head over to the next links, where doctor Francisco Calderon explains in detail the methods. 
SVM : https://www.youtube.com/watch?v=vemcbJnRqJU&list=PLar_Hmbx3oKoK-xl8UZcW03hDTXJd5B9E&index=13
KNN:  https://www.youtube.com/watch?v=HHsA2ZqIa2M&list=PLar_Hmbx3oKoK-xl8UZcW03hDTXJd5B9E&index=11&t=40s
Confussion Matrix: https://www.youtube.com/watch?v=85eooNbVtVw&list=PLar_Hmbx3oKoK-xl8UZcW03hDTXJd5B9E&index=7
PCA: https://www.youtube.com/watch?v=SigYQsSNPg8&list=PLar_Hmbx3oKoK-xl8UZcW03hDTXJd5B9E&index=15

Results: 
![image](https://user-images.githubusercontent.com/23547343/171961674-855cb0f2-3393-4450-96ef-7daf963e674f.png)
![image](https://user-images.githubusercontent.com/23547343/171961701-780f9542-a6b4-4fce-a015-7d8a02570b35.png)
![image](https://user-images.githubusercontent.com/23547343/171961717-60c8d39b-b7d1-4f7e-bde8-9bdcc601e53b.png)

After Performing PCA: 

![image](https://user-images.githubusercontent.com/23547343/171961753-c81de4f8-fe23-4d87-9feb-053a4e5921e6.png)
![image](https://user-images.githubusercontent.com/23547343/171961777-29f2e7c9-1198-4ccd-ad7f-cdf6e3d46024.png)
![image](https://user-images.githubusercontent.com/23547343/171961791-9e92abc6-4dc5-4be4-885a-0eb9e6fb2a6d.png)

Conclusion: 

The results for the trained model are of a high accuracy but this does not mean it is good. It is a dataset just fine to perform this project but it is not very confident because it is small and filling its values can improve its accuracy but does not mean it is absolutely right. After performing a dimensional reduction the results where the same, but this result is as acpected as the dataset is not the biggest one. 


