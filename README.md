# 🫀 Heart Attack Analysis & Prediction: Exploring Factors and Building a Predictive Model

<p align="center">
  <img src="https://github.com/gordonkwokkwok/Heart-Attack-Analysis-and-Prediction/assets/112631794/7695387f-1c77-48aa-9b03-2494d7e21a24" alt="Heart Attack Prediction" width="500">
</p>

## 📚 Introduction
This project focuses on the analysis and prediction of heart attacks using a dataset containing various factors related to heart health. By exploring the dataset, applying machine learning techniques, and leveraging data analysis, the project aims to gain insights into the factors contributing to heart attacks and develop a predictive model. The findings can help in understanding the risk factors associated with heart attacks and potentially aid in identifying individuals at higher risk.

## 🎯 Objective
1. Showcase the ETL process and feature engineering techniques.
2. Apply advanced Python functions and numpy operations for data transformation.
3. Visualize the data using matplotlib and seaborn.
4. Apply machine learning techniques, specifically RandomForestClassifier, for heart attack prediction.

## 🔍 About Dataset
| No. | Feature    | Description                                                                       |
|-----|------------|-----------------------------------------------------------------------------------|
| 1   | age        | Age of the patient                                                                |
| 2   | sex        | Sex of the patient                                                                |
| 3   | exang      | Exercise-induced angina (1 = yes; 0 = no)                                          |
| 4   | ca         | Number of major vessels (0-3)                                                     |
| 5   | cp         | Chest Pain type                                                                   |
| 6   | trtbps     | Resting blood pressure (in mm Hg)                                                  |
| 7   | chol       | Cholesterol in mg/dl fetched via BMI sensor                                        |
| 8   | fbs        | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)                               |
| 9   | rest_ecg   | Resting electrocardiographic results                                               |
| 10  | thalach    | Maximum heart rate achieved                                                       |
| 11  | oldpeak    | ST depression induced by exercise relative to rest                                                                     |
| 12  | slp        | the slope of the peak exercise ST segment                                                                             |
| 13  | thal       | Thalassemia                                                                         |
| 14  | target     | 0 = Less chance of heart attack, 1 = More chance of heart attack                   |

*No.5 - cp(Chest Pain Types):
- Value 1: Typical angina
- Value 2: Atypical angina
- Value 3: Non-anginal pain
- Value 4: Asymptomatic

*No.9 - rest_ecg(Resting Electrocardiographic Results):
- Value 0: Normal
- Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
- Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria

*No.12 - slp(Slope of the Peak):
- Value 0 = unsloping
- Value 1 = flat
- Value 2 = downsloping

*No.13 - thall(thalassemia):
- Value 0 = null
- Value 1 = fixed defect
- Value 2 = normal
- Value 3 = reversable defect

## Prerequisite
Creating a virtual environment is recommended for projects, and either venv or conda can be used based on personal preference. After creating the virtual environment, it is necessary to activate it before installing any required libraries. This project created a virtual environment called "cantekEnv"

### 🔧 Tool
- Jupyter Notebook (Version: 6.5.4)
- Python (Version: 3.9.6)
- Git (Version: 2.23.0)

Use following command to check version
```
jupyter notebook --version
python --version
git --version
```

### 📖 Library
Use following command to install the following libraries:
```
pip3 install numpy
pip3 install pandas
pip3 install matplotlib
pip3 install seaborn
pip3 install scikit-learn
```

## Command to run the project:
```
conda activate cantekEnv
jupyter notebook
```

## 🌐 Dataset
- [Link](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset?select=heart.csv) ; or
- [Download Here](https://github.com/gordonkwokkwok/Heart-Attack-Analysis-and-Prediction/blob/main/heart.csv)

## 👥 Contributer
- [Gordon Kwok](https://www.linkedin.com/in/gordonkwokch/)

## 🤝 Acknowledgments

I would like to express our gratitude to the following individuals and organizations for their contributions and support in making this project possible:

- Will: an instructor of the course, provided valuable guidance, mentorship, and expertise throughout the project. His support was instrumental in shaping the direction of the project and ensuring its success.
- [Cantek IT Program](https://www.cantekcanada.com/): Cantek IT Program, an educational institution, played a significant role in supporting the project. They provided resources, facilities, and a conducive learning environment for the team to work on the project.
- [Rashik Rahman](https://www.kaggle.com/rashikrahmanpritom): I express my gratitude to Rashik Rahman for providing the heart attack dataset on Kaggle. This dataset served as a valuable resource for my analysis and prediction tasks, enabling me to explore and gain insights into heart attack classification.

I am thankful for their valuable input, feedback, and assistance throughout the development process. Their expertise and dedication have greatly enhanced the quality and functionality of this project.

## 💪 Support
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/gordonhei25)

Give a ⭐️ if this project helped you!
