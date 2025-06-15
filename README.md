# Movie-Success-Prediction

## Website Link
Navigate to the following link to access this repository's GitHub Page: https://dbruce32.github.io/Movie-Success-Prediction/

## Directories and Files
```
Movie-Success-Prediction/
├── .github/
│   └── workflows/
│       └── [GitHub Actions workflows for CI/CD or automation]
├── .jekyll-cache/
│   └── Jekyll/                        # Misc: Used for site setup
├── ML Algorithms/
│   ├── model_assets/
│   │   ├── preprocessor.pkl        # Python pickle file that stores the trained preprocessor used in the Neural Network
│   │   └── revenue_predictor.pth   # PyTorch state dictionary for predicted revenue values from the trained model
│   ├── Linear_Regression.ipynb     # Jupyter Notebook implementing Linear Regression on the dataset
│   ├── Random_Forest.ipynb         # Implements a Random Forest Regressor using features like budget, popularity, vote count
│   ├── XGBRegressor.ipynb          # Applies XGBoost with preprocessing (OHE, scaling), training, and evaluation
│   ├── neural_net.ipynb            # Feedforward Neural Network with architecture definition and prediction routine
│   └── movies_metadata.csv         # Main dataset used to train all ML models
├── _layouts/                       # Contains website structure
```