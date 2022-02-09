# Blood_Donation_Management
This study aims to predict if a person will donate blood by using a recency, frequency, monetary, and time (RFMT) marketing model.
PROJECT LINK: https://gallery.cortanaintelligence.com/Experiment/Blood-Donation-Management

PROBLEM STATEMENT:
                    With the proliferation of big data, the need for intelligent and automated Systems has risen. This need is probably felt the most in the field of health care, especially in the area of blood transfusion, since they require supplies at the earliest. Currently, transfusion services are heavily manual in nature, which is not ideal. The rising demand for blood and the decline in donation rates has put a lot of strain on the blood donation supply chain. Hence, creating intelligent systems that can make decisions and improve communication across the supply chain is of great importance. In this paper, we are going to give a general summary of the various machine learning
techniques which have been applied to this domain and compare their advantages and disadvantages.

PROJECT DESCRIPTION:
                      The donation of blood is important because most often people requiring blood do not receive it on time causing loss of life. Examples include severe accidents, patients suffering from dengue or malaria, or organ transplants. Extreme health conditions such as Leukemia and bone marrow cancer, where affected individuals experience sudden high blood loss and need an urgent supply of blood and do not have it can also lead to loss of life. Sound data-driven systems for tracking and predicting donations and supply needs can improve the entire supply chain, making sure that more patients get the blood transfusions they need, which can reduce mortality risk.
                      
Machine Learning is not only successful in business but also helping the healthcare industry and revolutionizing it. Here, we are presenting a very simple machine learning model to predict that during an ask to donate blood who will respond positively and will donate blood.
 
 ![Blood Donation Management Mind Map](https://user-images.githubusercontent.com/89583866/153216060-0658ec63-0034-4428-ba47-8f88fca6a8f8.JPG)

In the above model, we have used the following 

1) How to treat with imbalanced dataset using SMOTE technique. 2) How to apply R script. 3) How to compare two models. 

The data has 5 attributes and need to predict the 5th one. R (Recency - months since last donation), F (Frequency - total number of donation), M (Monetary - total blood donated in c.c.), T (Time - months since first donation), and a binary variable representing whether he/she donated blood in March 2007 (1 stand for donating blood; 0 stands for not donating blood).

![Blood Donation Management Histogram](https://user-images.githubusercontent.com/89583866/153217529-83de486c-60a5-4bae-9347-9a6fbe5744c6.JPG)

![Blood Donation Management Statistics](https://user-images.githubusercontent.com/89583866/153221690-ffc1587a-c5dc-4e34-b5a8-37a17f0b846b.JPG)

Dataset was checked for inconsistencies and attributes normalised to get an even distribution. Increased the number of low incidence examples (True positives) in a dataset using synthetic minority oversampling to try to get a good accuracy. On the available two class classification algos, Decision forest gave the most efficient result,
                        
 ![Blood Donation Management Result Dataset](https://user-images.githubusercontent.com/89583866/153217921-3a351deb-4b6c-4fe0-b429-50ba3d5688d5.JPG)

We have compared the performance of various binary classification algorithms not investigated previously on clustered data and non-clustered data to see if we can better predict if a person is going to donate blood or not.           

https://user-images.githubusercontent.com/89583866/153222051-16ebdc61-688d-4b78-a408-28199abf7e36.mp4
