# User Reviews Sentiment Analysis using Logistic Regression

## Workshop Resources

- Login/Sign Up for IBM Cloud: https://ibm.biz/YourPathToDeepLearning
  
- Hands-On Guide: https://github.com/IBMDeveloperMEA/YPDL-SentimentAnalysis-LR

- Slides: https://ibmdevelopermea.github.io/YPDL-SentimentAnalysis-LR

- Workshop Replay: https://www.crowdcast.io/e/ypdl-1

### **Sign-up/Login to IBM Cloud**

If you are an existing user please [login to IBM Cloud](https://ibm.biz/YourPathToDeepLearning)

And if you are not, don't worry! We have got you covered! There are 3 steps to create your account on [IBM Cloud](https://ibm.biz/YourPathToDeepLearning): <br>
1- Put your email and password. <br>
2- You get a verification link with the registered email to verify your account. <br>
3- Fill the personal information fields. <br>
** Please make sure you select the country you are in when asked at any step of the registration process.
  
<img width="1188" alt="Screen Shot 2021-05-31 at 11 25 01 AM" src="https://user-images.githubusercontent.com/15332386/120156441-0769d980-c203-11eb-8cb3-29f4a8d5616a.png">

# About the workshop

While Deep Learning is a subset of Machine Learning, the prediction methodology in deep learning is different and works similar to how a human brain uses neural pathways to process information & learn from it. In this workshop we will learn about the building blocks of deep learning, neural networks, and how they work. We'll start with Logistic Regression - a simple and basic neural network classification algorithm, having just a one-layer neural network. 

In this first workshop of the Your Path to Deeep Learning series, we will teach audience how to use Natural language processing to classify user reviews from the IMDB Dataset. Developers can leverage user reviews for a given product or service from social media sites and customer reviews, and use Deep Learning models &amp; identify patterns to predict sentiments, or other statistics to be used for business decisions. In this workshop, the user reviews will be classified using Logistic Regression to predict whether the review is positive or negative.

### What will you learn? ✍🏼
- Introduction to Simple Neural Networks like Logistic Regression
- Natural language processing and text classification
- Analyze user sentiment from their reviews

# Workshop Tutorial 

## Step 1: 
Create IBM Cloud account using this link: https://ibm.biz/YourPathToDeepLearning
If you already have IBM Cloud Account then use this link to Log-in to your existing Account

## Step 2: 
  After successful creation of Account, you will be redirected to Dashboard. On top side, you will see a search bar. Search for "Watson Studio". Watson Studio service will show up. Click on it.
  <img width="1680" alt="1" src="https://user-images.githubusercontent.com/30890631/130508270-3fc0bf23-bdf5-4346-b2ed-3c517b292477.png">

  
## Step 3:
  Dont be confused with Location if another location shows up for you. You can select "Dallas (us-south)". In description you can see the details of service plan. Make sure "Lite" account is selected. Scroll down and check service name. You can change it to whatever you want. Now click on "Create".
  <img width="1679" alt="2" src="https://user-images.githubusercontent.com/30890631/130508277-40bd0320-db73-475a-a28b-e925d9cebeba.png">
  
## Step 4: 
  Once service is created, it will pop up on your screen and wait to be initialized. 
  <img width="1166" alt="3" src="https://user-images.githubusercontent.com/30890631/130508783-9096b68d-f744-4e8a-8680-2d6da6770d3a.png">
  When initialized, click on "Get Started". New window will open for Watson Studio also called "Cloud Pak for Data as a Service". While it is loading, lets create another service, go to the previous tab of Watson Studio Service
  
## Step 6: 
<img width="1677" alt="4" src="https://user-images.githubusercontent.com/30890631/130509388-80ca3f50-45a0-4604-a6cc-794ef9039c9a.png">
  Go to the search bar annd search for "object storage". Create Object Storage Service similarly to Watson Studio - please make sure that the region in both services is same. 
  
## Step 7:
  Navigate back to the Watson Studio dashboard that looks like below. 
  <img width="1677" alt="5" src="https://user-images.githubusercontent.com/30890631/130509913-81d4cc35-455f-4798-9ba0-51d290384148.png">
  On Left side, you will see "Quick Navigation". Click on "Projects". On top right click on "Create a Project". Create an empty project. Name your project and connect with an object storage service.
  
## Step 8:

On top you will se "Add to Project +" option, click on it and add "Notebook". Go to "From File". Download notebook called "YPDL-LogisticRegression.ipynb" from here: ```https://github.com/IBMDeveloperMEA/YPDL-SentimentAnalysis-LR```

Alternatively, you can also select the option "From URL" and paste the following URL ```https://raw.githubusercontent.com/IBMDeveloperMEA/YPDL-SentimentAnalysis-LR/main/YPDL-LogisticRegression.ipynb```

## Step 9: 
  Load the notebook and run the cells

Check out https://www.crowdcast.io/e/ypdl-1 to know the proper explanation of the concept and what you need to know.

## Workshop Resources

- Login/Sign Up for IBM Cloud: https://ibm.biz/YourPathToDeepLearning
  
- Hands-On Guide: https://github.com/IBMDeveloperMEA/YPDL-SentimentAnalysis-LR

- Slides: https://ibmdevelopermea.github.io/YPDL-SentimentAnalysis-LR

- Workshop Replay: https://www.crowdcast.io/e/ypdl-1

## Links to other sessions in Your Path to Deep Learning

- 25th August - 6PM-8PM (GST) 
    -  Identify Handwritten Digits using Convolutional Neural Networks with TensorFlow
    - https://www.crowdcast.io/e/ypdl-2

- 30th August - 6PM-8PM (GST) 
    -  Language Processing using Recurrent Neural Networks with TensorFlow
    - https://www.crowdcast.io/e/ypdl-3

- 1st September - 6PM-8PM (GST)
    -  Personalized Recommendation Engines with TensorFlow
    - https://www.crowdcast.io/e/ypdl-4
