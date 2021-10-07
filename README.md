# Natural-Language-Processing
Sentiment Analysis on Code-Mixed Tamil data

The text data is pre-processed to remove special characters, emoticons, tags, numbers etc,.
The pre-processed input converted into intermediate represenation using Term Frequency-Inverse Document Frequency (TF-IDF) which counts the occurances of each term in the document.
The task is to classify the data into 5 classes namely Positive, Megative, Mixed_feelings, Not_Tamil, Unknown_state.
The classification is performed using Random Forest. 
Classification report is generated to evaluate the accuracy of classification. 
