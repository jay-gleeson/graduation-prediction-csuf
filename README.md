<div align="center">
  <img alt="GitHub License" src="https://img.shields.io/github/license/jay-gleeson/graduation-prediction-csuf">
  <img src="https://img.shields.io/badge/TensorFlow-ff8f00?logo=tensorflow&amp;logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&amp;logoColor=fff" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?logo=jupyter&amp;logoColor=fff" alt="Jupyter Notebook">
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&amp;logoColor=fff" alt="Google Colab">
  <img src="https://img.shields.io/badge/Anaconda-44A833?logo=anaconda&amp;logoColor=fff" alt="Anaconda">
  <img src="https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&amp;logoColor=fff" alt="Matplotlib">
  <img src="https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&amp;logoColor=fff" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&amp;logoColor=fff" alt="Pandas">
  <img src="https://img.shields.io/badge/-scikit--learn-%23F7931E?logo=scikit-learn&amp;logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Plotly-7A76FF?logo=plotly&amp;logoColor=fff" alt="Plotly">
  <img src="https://img.shields.io/badge/-Seaborn-6BA1AE?logo=seaborn&amp;logoColor=fff" alt="Seaborn">
  
</div>

# Graduation Prediction Data Science Project 🎓

This project, completed by [Jay Gleeson](https://www.github.com/jay-gleeson) and [Victoria Uriostegui](https://github.com/victoria-uriostegui/) was performed with the help of the [CIC | PCUBED](https://www.fullerton.edu/ecs/cicpcubed/) organization at Cal State Fullerton. 


## Background 🗣️

According to research completed by the Department of Education, while high school graduation rates have been increasing on average in the United States, [lower-income households’ graduation rates are declining](https://nces.ed.gov/programs/coe/indicator/coi/high-school-graduation-rates).¹ Thus, the crux of our research was to see if there was a significant bias based on that statistic. The hypothesis developed was whether graduation rates correlate with household income statistics and if they could be predicted using various data prediction models.
## Tools 🪛

Various tools were utilized for our project. After initially using [Anaconda](https://www.anaconda.com/products/navigator) as our main virtual environment, we eventually settled for [Google Colab](https://colab.research.google.com/), a cloud-based tool that matched our use-case. Within Google Colab, we set up a Jupyter Notebook environment loaded with [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), and [TensorFlow](https://www.tensorflow.org/) packages. We also utilized [Seaborn](https://seaborn.pydata.org/) for making our heatmap to determine correlation rates between data columns. NumPy supported our use of arrays and tensors for our project, Pandas made it possible to clean our data effectively, and TensorFlow created an easy method for writing our neural network. The three models we settled on were a neural network, a Decision Tree Regressor, and a Random Forest Regressor. [Scikit-learn](https://scikit-learn.org/) quickly became an invaluable tool for splitting our dataset into training and prediction data, as well as providing the library for our Decision Tree and Random Forest models. Finally, we used both [Plotly](https://plotly.com/python/), to create an interactive US map, and [Matplotlib](https://matplotlib.org/), to create various data visualization graphs. 

*Note the database utilized in this Research Project was acquired through [Kaggle](https://www.kaggle.com/datasets/goldenoakresearch/us-acs-mortgage-equity-loans-rent-statistics) and was created by Golden Oak Research Group in Orlando, Florida.²*
## Conclusions 💡

Most recently, our previous logistic regression models were all swapped out with regression models to fit more accurately with our database's high school graduation data. Thus, after developing our models, training, and confirming predictions and accuracy scores, we ended up with very promising low error rates for each of our models. Our neural network ended up having a Mean Absolute Error (MAE) rate of 0.0718, our Random Forest Regressor had an MAE rate of 0.0682, and our Decision Tree Regressor had an MAE rate of 0.0678. R Squared (R2), Root Mean Squared Error (RMSE), and Mean Percent Error (MPE) rates can be viewed within the [.ipynb](data_science.ipynb). Thus, given low error rates and sufficient model accuracy, we can firmly state that is there is indeed a predicable correlation between household income factors and high school graduation rates. 

## Instructions 📝
### Method 1: Local reproduction
   1. Clone the repo
   ```bash 
      git clone https://github.com/jay-gleeson/graduation-prediction-csuf.git
      cd graduation-prediction-csuf
   ```
   2. Setup virtual environment.
   ```
      python -m venv venv
      venv\Scripts\activate
      pip install -r requirements.txt
   ```
   3. Launch Jupyter Notebook.
   ```
      jupyter notebook
   ```

### Method 2: Google Colab
1. Open .ipynb in Google Colab.
   See: [Open in Colab](data_science.ipynb).
2. Run Jupyter Notebook via Runtime >> Run All or Ctrl+F9.


## Presentation 🗨️

Below is a copy of our original presentation for the Project RAISE Summer Research Symposium at California State University Fullerton.

![Presentation](https://github.com/user-attachments/assets/27b24758-c3ee-4810-8fa4-c8e6a8e6f0cb)


## 📖 References
¹ National Center for Education Statistics, “High School Graduation Rates.” U.S. Department of Education, Institute of Education Sciences, 2024, [https://nces.ed.gov/programs/coe/indicator/coi](https://nces.ed.gov/programs/coe/indicator/coi).

² Golden Oak Research Group. “Insightful & Vast USA Statistics.” Kaggle.com, Alexander Geiger, 2018, [https://www.kaggle.com/datasets/goldenoakresearch/us-acs-mortgage-equity-loans-rent-statistics](https://www.kaggle.com/datasets/goldenoakresearch/us-acs-mortgage-equity-loans-rent-statistics).

