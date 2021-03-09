
# Spam-Filter

   ## Classifying SMS or emails Messages as either Spam or not Spam  (Spam Filtering - Text Classification)
   
   ### Problem Statement :
        The problem is that many people receive spam (emails,sms message , …) 
        These type of messages aims to collect users personal information ,
        so in This project I have data set contains 5574 classified message and aim To use (NLTK) for NLP operations and
        ML to predict that new message is spam or not spam.
      
  * The paper I use it as reference is called : (Text_Classification_Using_Machine_Learning)
   
   ### Datasets and Inputs :
        SMS Spam Dataset, The size of the dataset is 5574 sample row data and contains two columns.
        First column (Labels)contains classification of message its values : (ham(legitimate) or spam ) 
        and Second one (Feature) is message content . 
        SMS Spam Collection has a total of 4,827 SMS legitimate messages (86.6%) 
        and a total of 747 (13.4%) spam messages. 
        I'll split dataset into 75% & 25% ,I will take 25% of data as Testing set and 75% as Training set.
 
   ### Solution Statement :
         We want to build a robot to filter incoming  emails & SMS for detecting spam emails and spam SMS ,
         Using Machine Learning Techniques & NLTK for NLP operations ,
         It was my capstone for Udacity nanodegree in Machine learning engineer track,
         It's a binary classification problem to determine if this email or SMS is spam or not (safe)
         Models that i'll use : K Nearest Neighbors, Decision Tree, Logistic Regression, Naive Bayes, SVM Linear .

   ### Benchmark Model :
        We will use benchmark model to compare to our final
        result to make sure it works; we will use Naive bias
        classifier , as it is easy and has an initial result without
        tuning or using complex methods.
        
   ### Evaluation Metrics :
        First thing to do is deal with ​imbalanced classes “or data in the
        dataset” by using Confusion matrix or F1 score or ROC and
        AUROC
        
        
   ## The strategy that I will follow is :
        1. Download and pre-process the SMS Spam Collection v.1 dataset.
        2. Test and find best approach (word count or tf-idf vectorizer) to classify the messages.
        3. Selection of approach and splitting the dataset into training and testing data.
        4. Initialize various classifiers and train it.
        5. Evaluate the classifiers and finding best the model for a dataset
   
  # * That's it and you'll find all details in project files and code. 
   
   
