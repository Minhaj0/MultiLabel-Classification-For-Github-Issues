We've uploaded some large files to our Amazon S3 bucket due to size limitations. You can access them through the following link:

https://githubissuesdata.s3.us-east-2.amazonaws.com/data.txt

Feel free to download and use these files as needed.

# MultiLabel-Classification-For-Github-Issues

How to run our code to replicate the study result
This section provides a step-by-step guide for users to replicate the project workflow, from data 
collection to model training and testing.
1. Data Collection
To collect data for the project, follow these steps:
(1) Obtain the links of the repository issues from the GitHub API.
(2) Save the links into a gitApiLinks.csv named file.
(3) Run the code from DataMining.ipynb to retrieve data in JSON format using the requests library.
(4) Save the obtained data into a text file for future use.

# Execution of MultiLabel Classification For GitHub Issues.ipynb file needed for remaining steps

2. Data Preprocessing
For data preprocessing, perform the following actions:
(1) Read the saved text file's data or just use our Amazon S3 link to use the dataset we already mined.
(2) Run the preprocessing code to extract relevant labels and format the data.
3. Model Training and Testing
To train and test the classification model, follow these steps:
(1) Run the code for model training, which leverages advanced machine-learning techniques 
such as natural language processing and deep learning.
(2) Evaluate the model using precision, recall, and F1-score metrics.
4. Recommendation System
To use the recommendation system, follow these steps:
(1) Run the code for the recommendation system, which utilizes the trained classification model.
(2) Input relevant data; the system will provide personalized github-issue suggestions.
Note: Ensure that all dependencies, including Python libraries, are installed before running the 
code. Refer to the project documentation for specific requirements.
5. Example Commands
Here are example commands for each step:
# Data Collection
Add repo links to gitApiLinks.csv saved in the same location
# Data Preprocessing
Used nltk.corpus library for data preprocessing
# Model Training
MultiOutputClassifier and RandomForestClassifier used for model Training
# Model Testing
multi_target_forest.predict used for testing issues
