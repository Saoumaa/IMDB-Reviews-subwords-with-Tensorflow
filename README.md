# IMDB-Reviews-subwords-with-Tensorflow

This is an examlpe of NLP. 

In this project, sentiment analysis is performed in IMDB reviews.

The procedure is shown below.

## Loading the dataset.

The dataset was loaded online ,it was downloaded via its link and used here.

The image below is the screen capture of the texts from the reviews gotten.
![image](https://user-images.githubusercontent.com/104036386/182486245-3ba3505e-cda2-47d2-9b00-ce71244a0469.png)


### Data cleaning

The necessary cleaning in NLP is the removal of stopwords and punctuations.

### Preprocessing

Preprocessing is performed using keras preprocessing library. The preprocessing include tokeizing the texts and padding the texts. 

After all preprocessing the model was trained. 
The image below shows how it was trained. 

![image](https://user-images.githubusercontent.com/104036386/182486903-ce64f44f-bec4-4c37-83b0-17034a4757dd.png)

The model was trained over 10 epochs to avoid overfitting.
The result is shown below.

![download](https://user-images.githubusercontent.com/104036386/182487009-b7b8bd3e-320b-4fd6-b899-f65ddc3b0df5.png)

![download](https://user-images.githubusercontent.com/104036386/182487027-b8dbc5e2-21ff-40e5-b120-8e96f3ed70bf.png)

It is adviced to look into the code for better understanding of the process.
