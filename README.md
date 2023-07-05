## Heart Failure Prediction using Supervised ML Approach

![image](https://user-images.githubusercontent.com/96771321/189802385-c30359f6-3a21-4aae-b105-4ab51bc30a19.png)

> View Notebook: [Heart_Failure.ipynb](https://github.com/Davidsonity/Heart_Failure/blob/main/Heart_Failure.ipynb)

Heart failure is a critical medical condition that affects a significant number of people worldwide. Predicting heart failure in patients can help medical professionals take proactive measures to prevent adverse outcomes and provide timely interventions. In this project, we aim to build a machine learning model to predict heart failure in patients using a supervised ML approach.

### Dataset Description

The dataset used in this project contains the medical records of 299 patients who experienced heart failure during their follow-up period. Each patient profile consists of 13 clinical features, including age, presence of anemia, high blood pressure, creatinine phosphokinase (CPK) levels, diabetes status, ejection fraction, platelet count, gender, serum creatinine levels, serum sodium levels, smoking habit, follow-up period, and death event.

The dataset can be accessed from the following source: [Heart Failure Clinical Records](http://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records)

### Project Summary

The main objective of this project is to develop a machine learning model that can accurately predict heart failure in patients. To achieve this, we follow a supervised ML approach, where we train the model using the available dataset with labeled heart failure cases. Once trained, the model can then be used to make predictions on new, unseen data.

We employ various ML algorithms and techniques to build and evaluate the model's performance. Evaluation metrics such as recall and F-score are used to assess the model's accuracy in predicting heart failure cases. The model that exhibits the best performance is selected as the final prediction model.

### Project Structure
The project directory is structured as follows:

```
├── HeartFailure_Report.pdf
└── Heart_Failure.ipynb
├── LICENSE
├── README.md
├── heart_failure_clinical_records_dataset.csv
```

- `HeartFailure_Report.pdf` is the report file containing procedures and results.
- `Heart_Failure.ipynb` is the Jupyter Notebook file containing the code and analysis for the Heart Failure Prediction project.
- `LICENSE` is the file specifying the project's license information.
- `README.md` is the README file providing an overview and instructions for the project.
- `heart_failure_clinical_records_dataset.csv` is the dataset file containing the heart failure clinical records.

These files collectively form the structure of the Heart Failure Prediction project repository.

### How to Use the Notebook

To run the project notebook locally, please follow these steps:

1. Clone this repository to your local machine or download the notebook file `Heart_Failure.ipynb` directly.
2. Ensure that you have the necessary dependencies installed. You can refer to the `requirements.txt` file for the required libraries and their versions.
3. Open the notebook using Jupyter Notebook or any compatible environment.
4. Execute the cells in the notebook sequentially to replicate the project's results and explore the code and analysis.

### Results

After evaluating various ML models on the heart failure prediction task, we found that the Voting Classifier exhibited the highest performance. The Voting Classifier combines the predictions of multiple individual classifiers to make the final prediction. It leverages the strengths of different algorithms, resulting in improved predictive accuracy for heart failure cases.

The evaluation metrics, including recall and F-score, indicate the model's effectiveness in identifying heart failure instances. By utilizing this model, medical professionals can make more informed decisions and provide timely interventions to improve patient outcomes.

![shot](https://user-images.githubusercontent.com/96771321/214642905-926ca64b-68f3-4c04-aa42-89569c75bd1d.jpg)
