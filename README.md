# YPDL-SentimentAnalysis-LR
Resources for first workshop inn Your Path to Deep Learning series. 


# Step 1: 
Create IBM Cloud account using this link: https://ibm.biz/YourPathToDeepLearning
If you already have IBM Cloud Account then use this link to Log-in to your existing Account

# Step 2: 
  After successful creation of Account, you will be redirected to Dashboard. On top side, you will see a search bar. Search for "Watson Studio". Watson Studio service will show up. Click on it.
  <img width="1680" alt="1" src="https://user-images.githubusercontent.com/30890631/130508270-3fc0bf23-bdf5-4346-b2ed-3c517b292477.png">

  
# Step 3:
  Dont be confused with Location if another location shows up for you. You can select "Dallas (us-south)". In description you can see the details of service plan. Make sure "Lite" account is selected. Scroll down and check service name. You can change it to whatever you want. Now click on "Create".
  <img width="1679" alt="2" src="https://user-images.githubusercontent.com/30890631/130508277-40bd0320-db73-475a-a28b-e925d9cebeba.png">
  
# Step 4: 
  Once service is created, it will pop up on your screen and wait to be initialized. 
  <img width="1166" alt="3" src="https://user-images.githubusercontent.com/30890631/130508783-9096b68d-f744-4e8a-8680-2d6da6770d3a.png">
  When initialized, click on "Get Started". New window will open for Watson Studio also called "Cloud Pak for Data as a Service". While it is loading, lets create another service, go to the previous tab of Watson Studio Service
  
# Step 6: 
<img width="1677" alt="4" src="https://user-images.githubusercontent.com/30890631/130509388-80ca3f50-45a0-4604-a6cc-794ef9039c9a.png">
  Go to the search bar annd search for "object storage". Create Object Storage Service similarly to Watson Studio - please make sure that the region in both services is same. 
  
# Step 7:
  Navigate back to the Watson Studio dashboard that looks like below. 
  <img width="1677" alt="5" src="https://user-images.githubusercontent.com/30890631/130509913-81d4cc35-455f-4798-9ba0-51d290384148.png">
  On Left side, you will see "Quick Navigation". Click on "Projects". On top right click on "Create a Project". Create an empty project. Name your project and connect with an object storage service.
  
# Step 8:

On top you will se "Add to Project +" option, click on it and add "Notebook". Go to "From File". Download notebook called "YPDL-LogisticRegression.ipynb" from here: https://github.com/IBMDeveloperMEA/YPDL-SentimentAnalysis-LR

# Step 9: 
  Load the notebook and run the cells
