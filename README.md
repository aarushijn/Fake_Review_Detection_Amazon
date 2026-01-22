## Features
 - Machine Learning Approach: Develop a machine learning-based solution to detect fake reviews using a dataset of reviews collected from online platforms.

 - Feature Extraction: Preprocess the reviews to extract relevant features that will be used to train a classifier.

 - Classifier Evaluation: Explore various machine learning algorithms and techniques to achieve optimal performance in detecting fake reviews. Evaluate the classifier using standard metrics such as precision, recall, and F1 score.

 - Python and ML Libraries: Implement the project using Python and utilize machine learning libraries such as Scikit-Learn and TensorFlow.

## Setup and Usage
 1. Move into the data folder using the command cd data.

 2. Run the code using the Streamlit command: streamlit run <File_Name>.py. The UI is built with Streamlit, which connects with the backend Python code and displays the results.

 3. The frontend.py file contains graphs and results obtained from the dataset using SVM, Random Forest, Decision Trees, CNN Model, and ANN Model.

 4. Move the lstm.h5 and bert.h5 files to the data folder, along with frontend.py and changes.py.

### Run the following commands:
    cd data
    streamlit run changes.py
    streamlit run frontend.py
