# Data-driven-motion-planning-using-various-machine-learning-algorithms

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

## Introduction

This project aims to implement a machine learning model to solve a specific problem. The model will be trained on a labeled dataset and tested on unseen data to evaluate its performance.

## Personnel

* **Bharadwaj Chukkala** `<br>`
  UID: 118341705 `<br>`
  Bharadwaj Chukkala is currently a Master's student in Robotics at the University of Maryland, College Park, MD (Batch of 2023). His interests include Machine Learning, Perception and Path Planning.`<br>`
  [![Contact](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](bchukkal@umd.edu)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bharadwaj-chukkala/)
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bharadwaj-chukkala)

## Contents

```
|--bchukkal_final_project_report.docx
|--LICENSE
|--README.md
|--resources.docx
|--tree.txt
|   
|--data
   |---test_data
   |---train_data
```

## Requirements/Dependencies

To run this project, you will need the following:

- [Python 3.6+](https://www.python.org/downloads/)
- TensorFlow `python3 -m pip install tensorflow`
- Scikit Learn `pip install -U scikit-learn`
- [Training Data](https://drive.google.com/drive/folders/1IgiPMaMyktjIa9qH-5qqSjwFuew9TiPW)
- [Test Data](https://drive.google.com/drive/folders/1IhVbX1VwAQf4WzamN8m81sNQTABDWw5y)

## Setup

1. Clone this repository to your local machine
   ```
   git clone https://github.com/bharadwaj-chukkala/Data-driven-motion-planning-using-various-machine-learning-algorithms.git
   cd Data-driven-motion-planning-using-various-machine-learning-algorithms
   ```
2. Install the required libraries using `pip install`
3. Download the dataset and place it in the `data` directory, there are already existing datasets present in the repository which you can choose to change.

## Instructions

#### Training the Model

1. Open the `train.py` file and specify the path to the dataset
2. Run the training script using `python train.py`
3. 

#### Testing the Model

Once the model is trained, you can use it to make predictions on new data. To do this, open the `predict.py` file and specify the path to the model and the input data. Then run the script using `python predict.py`.

## Results

The performance of the trained model will be evaluated using metrics such as accuracy, precision, and recall.

#### Figures

* Cross-correlation heat map
* Standard deviation chart of laser
* $E_{in}$ vs $Epochs$
  * Linear Regression
  * Deep Neural Network
* Learning Curves
* Hyperparameter Tuning
* Regularization

## Conclusion

In this project, we implemented a machine learning model to solve a specific problem. The model was trained on a labeled dataset and its performance was evaluated on unseen data. The results show that the model performs well on the given task.

Thank you for using this project.
