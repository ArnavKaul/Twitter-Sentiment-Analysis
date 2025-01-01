# Twitter-Sentiment-Analysis


### Project Overview:
This project is more of a case-study of 2 different ML algorithms( Naive-Bayes & Support Vector Machines(SVM)) that deal with analysing tweets and classifying them as positive( indicated as 0) or negative (indicated as 4).

Algorithims covered in this project have been taken from the following research paper -https://arxiv.org/pdf/1601.06971
The dataset for this project has been taken from Kaggle -https://www.kaggle.com/datasets/kazanova/sentiment140/data  (1.6 million tweets).

- **Project Pipeline:**
   -  **Data Cleaning:**
            The first aspect was to clean the tweets.By cleaning we aimed to remove all URLs (e.g. www.xyz.com), hash tags (e.g.#topic), targets (@username).
            Replace all the emoticons with their sentiment.
            Tokenize and remove stop words('is', 'and','the'... etc).
   - **Data Preprocessing:**
     -As per general convention, the data was split into test, train and val data.Following which I vectorized the dataset using 2 different libraries (one for Naive Bayes algo and the other for SVM).
      Finally we studied the accuracy based on N-gram approach. In this case we took unigram, bigram and trigram.
  
 NOTE: While studying SVM we took max_iter=1000 in its model due to certain limitations. At the end it was found out that Naive Bayes with a Unigram approach had the highest accuracy(close to 0.8).

- **Conclusion:**
       This project is more of a case study/comparision project and is my first attempt in recreating/writing code based of a research-paper. Any inconsistencies in code/mistakes/advice/suggestions about the project are   appreciated. 

  **Peace!**
  
          
