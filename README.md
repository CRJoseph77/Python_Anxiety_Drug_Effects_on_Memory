![](Python_memory_coverphoto.PNG)

# Exploring the Effects of Anti-Anxiety Drugs on Memory in Python
Do different anti-anxiety drugs, different dosages of those drugs, or emotional priming lead to changes in performance on a memory test?

# Project Overview
This project uses data from a simulated experiment that examines the effect of anti-anxiety medication on memory. Virtual participants were randomly assigned to one of three anti-anxiety drug conditions (Xanax, Halcion, or control), one of three dosage conditions (low, moderate, high), and one of two emotional priming conditions (happy or sad). Completion time on a memory task was assessed before exposure to the drug and emotional priming condition, and again after exposure to the drug and emotional priming condition. The primary dependent measure is the difference in response time on the memory task after exposure to the drug and emotional priming condition compared to before. Higher scores indicate a decrease in performance - the task took more time after exposure to the drug and emotional priming condition than before. Lower (or negative) scores indicate an increase in memory performance. 

Data exploration and hypothesis testing were performed in Python. The data was cleaned and structured in preparation for analysis. Next, multiple statistical tests were conducted to evaluate the effects of drug type, drug dosage, and emotional priming on memory. Hypothesis tests conducted include a two-sample t-test (an A/B test), a one-way ANOVA, and multiple two-way ANOVAs. Visualizations were created to elaborate on the test results. 

# Installation and Setup
## Code and Resources Used
Editor Used: This project was created in an online Jupyter Notebook.

Python Version: Python 3.

## Python packages used
Data manipulation: pandas, numpy.

Data visualization: matplotlib, seaborn.

Statistical analysis: statsmodels

# Data
Source data: The dataset used for this project was downloaded from Kaggle. It contains data generated at UCLA from a virtual environment on virtual participants that simulate real human behavior. The data can be found here: https://www.kaggle.com/datasets/steveahn/memory-test-on-drugged-islanders-data.

Data limitations: Even though the data was not collected from real participants, the dataset is still suitable for the purposes of this project. Any results and conclusions should be interpreted cautiously as they may not represent actual, real-world effects of anti-anxiety medications on memory. 

Preprocessing: No preprocessing was performed prior to uploading the dataset to the Jupyter Notebook.

# [Code Structure](drug_effects_on_memory_hypothesis_testing_python.ipynb)
1. Importing packages and data - Relevant packages and the dataset were imported into the Jupyter Notebook.

2. Exploratory data analysis - The data was cleaned, explored, and structured, and cleaning was validated to ensure the data was prepared for analysis.

3. Hypothesis testing - Multiple hypothesis tests were conducted to evaluate the effect of anti-anxiety drugs on memory, including a two-sample t-test, a one-way ANOVA, and multiple two-way ANOVAs. The results of these tests were discussed and visualized.

4. Visualizations - Data relationships were visualized for further examination.

# Results and Evaluation
Given that this data was not collected from real human participants, these analyses are purely exploratory for purposes of this project and any conclusions should be interpreted cautiously.

Data was successfully cleaned and structured prior to analysis. The statistical hypothesis tests revealed multiple significant effects. Drug condition significantly impacted memory scores, with the Xanax group showing significant decreases in memory performance relative to the other two conditions. There was also a significant effect of dosage, with the higher dosage group showing a decrease in memory performance relative to the low and moderate dosage groups. Lastly, there was a significant interaction between drug condition and dosage condition. Differences in memory test performance for observations in the Xanax group were greatly affected by dosage, with higher dosage being associated with decreased memory performance relative to moderate and low dosage conditions. The magnitude and direction of the effect of dosage was not present to the same degree in the other two drug conditions. The effects of the emotional priming condition were not significant, and they did not significantly interact with drug condition.

# References
Kaggle Data: https://www.kaggle.com/datasets/steveahn/memory-test-on-drugged-islanders-data.

# License
The license associated with the data used for this project is CC0: Public Domain.
