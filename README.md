We've uploaded some large files to our Amazon S3 bucket due to size limitations. You can access them through the following link:



Feel free to download and use these files as needed.

# MultiLabel-Classification-For-Github-Issues

How to run our code to replicate the study result
This section provides a step-by-step guide for users to replicate the project workflow, from data 
collection to model training and testing.
1. Data Collection
To collect data for the project, follow these steps:
(1) Obtain the links of the repository issues from the GitHub API.
(2) Save the links into a gitApiLinks.csv named file.
(3) Run the provided code to retrieve data in JSON format using the requests library.
(4) Save the obtained data into a text file for future use.
2. Data Preprocessing
For data preprocessing, perform the following actions:
(1) Read the data from the saved text file.
(2) Run the preprocessing code to extract relevant labels and format the data.
3. Model Training and Testing
To train and test the classification model, follow these steps:
(1) Run the code for model training, which leverages advanced machine-learning techniques 
such as natural language processing and deep learning.
(2) Evaluate the model using metrics such as precision, recall, and F1-score.
4. Recommendation System
To use the recommendation system, follow these steps:
(1) Run the code for the recommendation system, which utilizes the trained classification model.
(2) Input relevant data, and the system will provide personalized github-issue suggestions.
Note: Ensure that all dependencies, including Python libraries, are installed before running the 
code. Refer to the project documentation for specific requirements.
5. Example Commands
Here are example commands for each step:
# Data Collection
python collect_data.py filename.csv
# Data Preprocessing
python preprocess_data.py data.txt
# Model Training
python train_model.py
# Model Testing
python test_model.py
# Recommendation System
python recommend_issues.py
