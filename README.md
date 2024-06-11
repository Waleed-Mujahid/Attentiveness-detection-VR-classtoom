# Attentiveness Detection in a Metaverse Classroom

For my final year project, I worked on developing a Machine Learning model to detect the attentiveness of students in a Metaverse classroom using sensory data from Meta Quest 2. We created our own dataset by conducting a [Continuous Performance Test (CPT)](https://www.sciencedirect.com/science/article/pii/S0747563216300759)  inside the VR classroom. Our final model achieved a 21.92% mean absolute percentage error.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies and Libraries Used](#technologies-and-libraries-used)
- [Methodologies and Techniques Applied](#methodologies-and-techniques-applied)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The objective of this project was to leverage machine learning techniques to assess the attentiveness of students in a virtual reality classroom environment. Using sensory data from Meta Quest 2, we conducted experiments and developed a model to predict attentiveness levels accurately.

## Dataset

We collected data by performing a Continuous Performance Test (CPT) within the VR classroom environment. The dataset consists of various sensory inputs recorded during the tests.

## Technologies and Libraries Used

The project utilizes the following technologies and libraries:

- **Programming Languages**: Python
- **Data Processing and Analysis**:
  - pandas
  - numpy
  - scipy
- **Machine Learning and Deep Learning**:
  - scikit-learn
  - TensorFlow
  - Keras
  - statsmodels
- **Visualization**:
  - matplotlib
  - seaborn

## Methodologies and Techniques Applied

The project followed these key methodologies and techniques:

1. **Data Collection**:
   - Conducted Continuous Performance Tests (CPT) within the VR classroom.
   - Recorded sensory data from Meta Quest 2.

2. **Data Pre-processing**:
   - Cleaned and pre-processed the sensory data.
   - Extracted relevant features from the raw sensory data.

3. **Model Development**:
   - Implemented various machine learning models, including Support Vector Machines (SVM) and Neural Networks.
   - Built a Sequential model using Keras with layers including Dense and Dropout.

4. **Model Evaluation**:
   - Evaluated models using metrics such as accuracy, F1 score, and mean absolute percentage error (MAPE).
   - Achieved a final MAPE of 21.92%.

## Installation

To run this project, you will need to install the following dependencies:

```bash
pip install pandas numpy scipy seaborn matplotlib scikit-learn tensorflow keras statsmodels
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/metaverse-classroom-attentiveness.git
cd metaverse-classroom-attentiveness
```

2. Run the Jupyter notebooks to process data and train models:

```bash
jupyter notebook
```

3. Open and execute the notebooks in the following order:
   - `parse.ipynb`
   - `analysis.ipynb`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.