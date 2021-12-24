# C.S. John Lee's Data Science Portfolio

Hello, I am John.  
I love working with data and learning to work with data.  
Below are projects that I'd like to share with you. More to come!  

## Machine Learning 
- [Methane Anomaly Detector](https://github.com/sanjayms01/methane)  |   [[SlideDeck]](https://docs.google.com/presentation/d/11YTivxMuYAa7_YLMh8lfQjb4NlsIZNBQ4tynZrQVwfc/edit)   | [[Product Demo]](https://www.ischool.berkeley.edu/projects/2021/methane-anomaly-detector)
Detected atmospheric methane concentration anomalies by using an Long Short-Term Memory (LSTM) Autoencoder. This includes building the data pipeline to retrieve data from European Space Agency's Sentinel 5P real-time satellite measurements, ERA5 weather data, and California Climate Zones, feature engineering, and hyperparameter tuning. Our group also built a public website, www.methaneanomalydetector.com, to showcase the anomaly detection as well as visualizations about the data. Please refer to product demo shown on the bottom right of the website linked above.   
  ![Image of W266 Paper](https://raw.githubusercontent.com/CSJohnLee/projects_ucb_mids/master/Images/stackreqa.png)  
  

- [Question-Answering Task with Natural Language Processing Models](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/stackoverflow_reqa)  |   [[SlideDeck]](https://docs.google.com/presentation/d/1hi7xf_9UxuG7_e1n8TSSkoI3qRV78HULg08lMpaYP9s/edit?usp=sharing)   | [[Notebooks]](https://github.com/sanjayms01/StackReQA)
Retrieved answers to Stack Overflow questions by utilizing different language embeddings, data ordering techniques, and deep learning architectures to determine the most ideal method by evaluating on the mean reciprocal rank (MRR) score. Specifically, embedded data with Universal Sentence Encoder (USE), Bidirectional Encoder Representations from Transformers (BERT), and Word2Vec. Final model achieved a 26% increase in performance compared to the popular TFIDF BM-25 model.
  ![Image of W266 Paper](https://raw.githubusercontent.com/CSJohnLee/projects_ucb_mids/master/Images/stackreqa.png)  


- [Predicting Flight Delays (at Scale)](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/flight_delays_prediction)  |   [[SlideDeck]](https://docs.google.com/presentation/d/1VkYIzGgzorXwzKhASuqDeq1tBfVdYDn3LabyfhQdw64/edit?usp=sharing)   
Predicted flight delays on the Databricks platform. Utilized Spark to process over 30 million rows (20+ GB) of data. Logistic Regression, Decision Tree, Random Forest, and Gradient Boosted Trees algorithms from the MLlib Package were tuned by varying hyper-parameters, creating new features, and reducing dimensions with Principal Component Analysis. 


- [House Price Prediction](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/house_price_prediction)  |   [[SlideDeck]](https://docs.google.com/presentation/d/1B8kliL58PaSFKafOiJD0OPBr-FkByLgqiz3M6acir3o/edit?usp=sharing)    
  Utilized linear regression, decision trees with ensembling methods, and neural networks to predict housing price on a Kaggle dataset.  
  ![Image of House Price](https://raw.githubusercontent.com/CSJohnLee/projects_ucb_mids/master/Images/house_price_predict.PNG)  


- [Digit Classification](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/digit_classification)  
  Utilized k-Nearest Neighbors and Naive Bayes models on the MNIST digits dataset to classify digits. Also generated images with Naive Bayes!  
  ![Image of Generated Digits](https://raw.githubusercontent.com/CSJohnLee/projects_ucb_mids/master/Images/generated_images.png)  
  
## Exploratory Data Analysis 
- [COVID-19](https://github.com/CSJohnLee/COVID19_Project)  |   [[SlideDeck]](https://docs.google.com/presentation/d/1z9M6WjM0kyZV0tBjC2mafpYZLWmoRZ9VFko0kUA46zE/edit?usp=sharing)    
  An Analysis of COVID-19 Dataset.  
  ![Image of COVID19](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Images/CaseOverTime.gif?raw=true)   

- [Weather & Baseball](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/Weather_Baseball_Data_Analysis_with_Pandas_and_Numpy)  
  An Analysis of a Baseball Dataset with Pandas and Numpy  
  ![Image of sfn's game frequency](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Images/weather_baseball.png?raw=true)

## Statistics in R 
- [Facebook Marketplace Experiment](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/fb-marketplace-exp)  
  Conducted a between-subjects randomized block design experiment to measure the potential treatment effect of image quality on bidding price. Utilized Qualtrics XM's API for a pre-experimental survey (for power analysis) and Facebook Marketplace for the actual experiment. Produced linear and log-linear multi-variate regression models that showed statistical signifiance on the treatment variable, suggesting that a higher quality image leads to a greater maximum bid price.

  ![Image of Photos](https://raw.githubusercontent.com/CSJohnLee/projects_ucb_mids/master/Images/FB_marketplace.png)  
   
 - [Comparing Means Lab](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/comparing_means_lab)  
   *Objective:* Address research questions on American National Election Studies (ANES) surveys about voters in United States. Determine what type of test is most appropriately utilized (parametric vs nonparametric, unpaired versus paired)  
   
   ![Image of Comparing Means](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Images/comparing_means.PNG?raw=true)  
     
- [Reducing Crimes Lab](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/reducing_crimes_lab)  
   *Objective:* Examine a dataset of crime statistics to help a political campaign understand the determinants of crime and to generate policy suggestions that are applicable to local government. Create multi-variate linear regression models and determine if the classical linear assumptions are satisifed.   
     
   ![Image of Reducing Crimes](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Images/reducing_crime.PNG?raw=true)

## Google Cloud Platform (GCP) and Big Query
- [Lyft Bay Wheels](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/lyft_bay_wheels_data_analysis)  
  An Analysis with Google Cloud Platform (GCP), Big Query, and SQL.

## Programming
- [Migrate](https://github.com/CSJohnLee/projects_ucb_mids/tree/master/Migrate_An_OOP_Project)  
  An Object-Oriented Programming Project in Python. Please refer to [design document](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Migrate_An_OOP_Project/Design_Doc_CSJL_Final.pdf) for a description and instructions. 

## Research Design Presentations
- [SHIND!G](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Research_Design_Presentations/SHIND!G.pptx)    
   *Objective*: To develop a research design that could answer an important data science question. Create a slidedeck to pitch to potential stakeholders or investors on this potential project.
- [Celebrity Location Identification for Paparazzi](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Research_Design_Presentations/Celebrity_Location_Identification_for_Paparazzi.pptx)   
   *Objective*: Apply research design concepts to identify a business problem and reseearch question, and to describe how data science can answer that question.
- [How Your Personal Data Can Help Catch Violent Criminals](https://github.com/CSJohnLee/projects_ucb_mids/blob/master/Research_Design_Presentations/How_Your_Personal_Data_Can_Help_Catch_Violent_Criminals.pptx)  
   *Objective*: To explore a controversial debate in data science that will likely affect a domain of your choice. 





















