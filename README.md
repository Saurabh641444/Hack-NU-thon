# Hack-NU-thon
This project is made in Hack-NU-Thon  which is Hackathon organised by Nirma University

### Group Members
1. Saurabh Jejurkar
2. Vedant Jore
3. Harshal Hirpara
4. Ansh Asija

## Description

## Domain:- Agriculture
## Technology:- Machine Learning, Deep Learning and Web Development
## Languages:- python, html, css and javascript
## Framework:- Bootstrap, Flask and Adobe
## Deployment server:- Heroku

In agriculture there is lack of use of technologies. Farmers loose their income because they can't find out diseases of plants in early stage. If they found out then they can use fertilizers to save the production of crops. By using technologies like Deep learning we can find out disease of the plant using there leaves in website. In website we have also included the Fertilizers store and after disease detection we have suggested fertilizer to farmer using API. In fertilizers store we have included the insecticides, pesticides and fertilizers along with its description and prize. Farmer can do online fertilizer ordering
<br/>
We have included crop recommendation system in this website. This is developed by machine learning algorithm Random Forest. In this by using N, P, K , Ph of soil and rainfall value of particular area farmer can easily find out which crop is suitable for his field.

## 1. Crop Recommendation System
Dataset:- cpdata.csv which is open source dataset used here.
### Libraries
1. pandas
2. scikit learn
3. matplotlib
4. seaborn
5. numpy
### Machine Learning Algorithms used
1. Support Vector Machine
2. Logistic Regression
3. Random Forest 
4. Decision Tree
5. Naive Bayes
6. XGBoost
<br/>
In this we have found out that Random forest having good Accuracy
<br/>
![](https://github.com/Saurabh641444/Hack-NU-thon/blob/b10986bd546dffd3622709d0ad292889106b038c/app/static/images/HACKNUTHON1.png)
<br/>
The accuracy of best model is 99.09%
<br/>

## 2. PLANT DISEASE CLASSIFICATION USING RESNET-9 
### **Description of the dataset 📝**
This dataset is created using offline augmentation from the original dataset. The original PlantVillage Dataset can be found here.This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into 80/20 ratio of training and validation set preserving the directory structure. A new directory containing 33 test images is created later for prediction purpose.<br/>
### Libraries used
1. Numpy
2. Pandas 
3. Pytorch
<br/>
We have have use Pytorch here so it have 5 step life cycle<br/>
The five steps in the life-cycle are as follows:<br/>
1. Prepare the Data.
2. Define the Model.
3. Train the Model.
4. Evaluate the Model.
5. Make Predictions.
<br/>
### Deep Learning Algorithm used- ResNet-9
In ResNets, unlike in traditional neural networks, each layer feeds into the next layer, we use a network with residual blocks, each layer feeds into the next layer and directly into the layers about 2–3 hops away, to avoid over-fitting (a situation when validation loss stop decreasing at a point and then keeps increasing while training loss still decreases). This also helps in preventing vanishing gradient problem and allow us to train deep neural networks. Here is a simple residual block:
<br/>
![](https://github.com/Saurabh641444/Hack-NU-thon/blob/b10986bd546dffd3622709d0ad292889106b038c/app/static/images/HACKNUTHON2.png)
<br/>
The accuracy of the model is 99.2%
<br/>
### Validation Accuracy
<br/>
![](https://github.com/Saurabh641444/Hack-NU-thon/blob/b10986bd546dffd3622709d0ad292889106b038c/app/static/images/HACKNUTHON3.png)
<br/>
### Validation Loss
<br/>
![](https://github.com/Saurabh641444/Hack-NU-thon/blob/b10986bd546dffd3622709d0ad292889106b038c/app/static/images/HACKNUTHON4.png)
<br/>

## 3. Online Fertilizer store
### Features:
1. Farmer can buy fertilizers, insecticides and pesticides
2. Description and prize of product is available
3. Farmer can add fertilizers in cart and buy them online.






