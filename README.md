
# Graduation Prediction Data Science Project 🎓

This project, completed by [Jay Gleeson](https://www.github.com/jay-gleeson) and [Victoria Uriostegui](https://github.com/victoria-uriostegui/) was performed with the help of the [CIC | PCUBED](https://www.fullerton.edu/ecs/cicpcubed/) organization at Cal State Fullerton. 


## Background 🗣️

According to research completed by the Department of Education, while high school graduation rates have been increasing on average in the United States, [lower-income households’ graduation rates are declining](https://nces.ed.gov/programs/coe/indicator/coi/high-school-graduation-rates). Thus, the crux of our research was to see if there was a significant bias based on that statistic. The hypothesis developed was whether graduation rates correlate with household income statistics and if they could be predicted using various data prediction models.
## Tools 🪛

Various tools were utilized for our project. After initially using [Anaconda](https://www.anaconda.com/products/navigator) as our main virtual environment, we eventually settled for [Google Colab](https://colab.research.google.com/), a cloud-based tool that matched our use-case. Within Google Colab, we set up a Jupyter Notebook environment loaded with [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), and [TensorFlow](https://www.tensorflow.org/) packages. We also utilized [Seaborn](https://seaborn.pydata.org/) for making our heatmap to determine correlation rates between data columns. NumPy supported our use of arrays and tensors for our project, Pandas made it possible to clean our data effectively, and TensorFlow created an easy method for writing our neural network. The three models we settled on were a neural network, a Decision Tree Classifier, and a Random Forest Classifier. [Scikit-learn](https://scikit-learn.org/) quickly became an invaluable tool for splitting our dataset into training and prediction data, as well as providing the library for our Decision Tree and Random Forest models. Finally, we used both [Plotly](https://plotly.com/python/), to create an interactive US map, and [Matplotlib](https://matplotlib.org/), to create various data visualization graphs. 

*Note the database utilized in this Research Project was acquired through [Kaggle](https://www.kaggle.com/datasets/goldenoakresearch/us-acs-mortgage-equity-loans-rent-statistics) and was created by Golden Oak Research Group in Orlando, Florida.*
## Conclusions 💡

After developing our models, training, and confirming predictions and accuracy scores, we ended up with very promising accuracy scores for each of our models. Our neural network ended up having an accuracy score of eighty-one percent, our Random Forest Classifier had an accuracy of seventy-eight percent, and our Decision Tree Classifier had an accuracy of seventy-six percent. Thus, we can firmly state that is there is indeed a predicable correlation between household income factors and high school graduation rates. 
## Presentation 🗨️

Below is a copy of our presentation for the Project RAISE Summer Research Symposium at Cal State Fullerton. 

![Presentation](https://i.imgur.com/Z1uJKK1.png)


## References

 - Golden Oak Research Group. “Insightful & Vast USA Statistics.” Kaggle.com, Alexander Geiger, 2018, https://www.kaggle.com/datasets/goldenoakresearch/us-acs-mortgage-equity-loans-rent-statistics.

