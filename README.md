# Movie-Success-Prediction

## Website Link
Navigate to the following link to access this repository's GitHub Page: https://github.gatech.edu/pages/dbruce32/Movie-Success-Prediction/

## Directories and Files
1. /ML Algorithms/: Contains the sole dataset used to train the models along with the ML algorithms used in their respective Jupyter Notebooks
   - /ML Algorithms/Linear_Regression.ipynb: Jupyter Notebook that contains the Linear Regression algorithm applied on the dataset
   - /ML Algorithms/Movie_ML_Notebook.ipynb: Jupyter Notebook that contains operations to clean the dataset, an EPOCH iteration and a test between actual and predicted values
   - /ML Algorithms/Random_Forest.ipynb: Jupyter Notebook that implements a Random Forest Regressor to predict movie revenue based on features budget, popualrity, vote count etc. 
   - /ML Algorithms/XGBRegressor.ipynb: Jupyter Notebook that performs data preprocessing using One-Hot Encoding, feature engineering, feature scaling, and model training
   - /ML Algorithms/movies_metadata.csv: CSV file containing the main dataset used to train all the models
   - /ML Algorithms/neural_net.ipynb: Jupyter Notebook that implements a Feedforward Neural Network (Multi-Layer Perceptron) using One-Hot Encoding, an architecture definition, and a prediction function
   - /ML Algorithms/preprocessor.pkl: Python file to save the preprocessor after the Neural Network has been trained (unique to each training iteration)
   - /ML Algorithms/revenue_predictor.pth: PyTorch state dictionary that holds predicted revenue values after iteration of Neural Network model
     
2. /_layouts/: Contains images used throughout the GitHub Pages website and html files that encapsulates the midterm and final report
3. All the rest of the files are miscallaneous and are used to apply design elements to the website

