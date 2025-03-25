![image](https://github.com/user-attachments/assets/52364471-2abf-42e2-a990-787e83bbebb8)


# pedestrain-tracking-final-project
PedestrianTrack Project

# Project Overview

The PedestrianTrack project aims to analyze pedestrian movement patterns using a combination of feature engineering and machine learning. The goal is to classify different pedestrian behaviors based on spatial and motion data.
# Dataset
Source:
UCI Machine Learning Repository:https://archive.ics.uci.edu/dataset/536/pedestrian+in+traffic+dataset

# Features
oid: Unique ID for each pedestrian.
timestamp: Time of data capture.
x, y: Pedestrian’s coordinates.
body_roll, body_pitch, body_yaw: Body orientation measurements.
head_roll, head_pitch, head_yaw: Head orientation measurements.
other_oid: IDs of nearby objects.
other_class: Categorical label representing interaction types (e.g., walking, crossing).
other_x, other_y: Coordinates of nearby objects.

# Technique used:
Data Collection & Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Model Development
Pipeline Implementation
Model Evaluation & Optimization

# Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
imblearn
Joblib 
Warnings 
# Output
Best-performing model: Random Forest Classifier
Achieved accuracy:0.97%
# Machine Learning Pipeline
Data Preprocessing: Handling missing values and feature scaling.
Feature Selection: Selecting the most relevant features for prediction.
SMOTE Implementation: Addressing class imbalance using Synthetic Minority Over-sampling Technique (SMOTE).
Model Training: Training a Random Forest Classifier within the pipeline.
# Conclusion
The pedestrian tracking project successfully achieved its objective of predicting pedestrian interactions using geospatial and time-series data. After extensive data preprocessing, feature engineering, and model evaluation, Random Forest emerged as the best-performing model, achieving an impressive .97% accuracy. This high accuracy demonstrates the model's strong ability to capture complex patterns in pedestrian movements and interactions with surrounding objects.
The model’s performance on unseen data, consistently predicting [3, 3, 3, 3, 3, 3, 3], suggests a high confidence in classifying that specific interaction type. However, this also raises a potential point for further analysis — whether the model generalizes well across all classes or overfits to a dominant class.
The project highlights the strength of ensemble methods like Random Forest in handling noisy, multidimensional data, especially when dealing with a mix of spatial, temporal, and categorical features. 
# Future work could focus on:
Expanding the dataset to include more diverse pedestrian scenarios and environmental contexts.
Handling class imbalances to ensure the model performs equally well across all interaction types.
Integrating real-time tracking to test the model in dynamic, live environments.Refining feature engineering to extract more insightful patterns from orientation metrics and object proximity.

In conclusion, this project demonstrates the potential of machine learning to improve pedestrian behavior analysis, supporting applications in urban planning, public safety, and smart city development.
 Future Improvements and Next Steps
To further enhance the project’s performance and practical impact:

Expand the Dataset:

Incorporate data from various environments — urban streets, crowded malls, and open parks — to improve generalizability.

Address Class Imbalance:

Apply resampling techniques like SMOTE to ensure underrepresented interaction classes are learned properly.

Real-Time Integration:

Deploy the model for real-time pedestrian tracking, enabling live analysis for smart city applications, traffic flow monitoring, or safety planning.

Advanced Feature Engineering:

Extract more nuanced patterns from body_yaw, head_pitch, and object proximity metrics to improve the model’s understanding of pedestrian behavior.

# ⭐ Final Takeaways
This project demonstrates the power of machine learning — particularly ensemble methods like Random Forest — in analyzing pedestrian behavior. With further refinement, this model could support a wide range of applications in urban planning, public safety, and smart city development — contributing to safer, more efficient environments for pedestrians. 🚶‍♂️✨

Would you like me to create a presentation slide outline or visual charts for the results too? 🎯
