

# Power System Fault Detection and Classification using Machine Learning

A capstone project aimed at building a machine learning-based model to automatically detect and classify faults in a power distribution system using electrical measurement data.

## Problem Statement

Rapid and accurate fault identification in electrical grids is essential for ensuring system reliability and reducing downtime. This project focuses on developing a machine learning model that can classify different types of faults — such as line-to-ground, line-to-line, and three-phase faults — using electrical parameters like voltage and current phasors.

## Proposed Solution

We propose a supervised machine learning solution that:

* Processes historical fault data
* Classifies fault types using voltage, current, environmental, and component health indicators
* Is deployed on IBM Cloud for real-time predictions

### Key Components

* **Data Collection**: Fault dataset sourced from [Kaggle](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)
* **Data Preprocessing**: Handling missing values, outliers, and noise
* **Model Selection**: Algorithms like Random Forest, SVM, and Logistic Regression were evaluated
* **Deployment**: IBM Watsonx.ai Studio with IBM Cloud Object Storage
* **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, MAE, RMSE

## Algorithm & Deployment

* **Algorithm Used**: Random Forest Classifier (selected for high performance)
* **Input Features**:

  * Voltage & Current
  * Power Load
  * Temperature & Wind Speed
  * Weather Conditions
  * Maintenance Status
  * Component Health
  * Duration of Fault
* **Training**: Supervised Learning using labeled fault types
* **Deployment Platform**: IBM Watsonx.ai Studio with real-time data access via IBM Cloud Object Storage and API endpoints

## System Architecture

| Layer         | Tool/Tech                    |
| ------------- | ---------------------------- |
| Development   | IBM Watsonx.ai Studio        |
| Storage       | IBM Cloud Object Storage     |
| Deployment    | IBM Cloud                    |
| Visualization | IBM Watson Studio (optional) |

## Results

The trained model:

* Accurately identifies different types of faults in real-time
* Operates with high precision and recall across test datasets
* Reduces detection latency, aiding rapid response

## 🔚 Conclusion

The machine learning-based fault classification model significantly improves fault detection efficiency in power systems. Its deployment on IBM Watsonx.ai Studio ensures scalable, accessible, and real-time fault predictions for utility operators.

## Future Scope

* **IoT Integration**: Incorporating real-time sensor data from smart meters and PMUs
* **Predictive Maintenance**: Evolving the system to forecast potential failures
* **Advanced Models**: Experimentation with LSTM and Graph Neural Networks
* **Continuous Learning**: Automatic model retraining as new data becomes available

## References

* Dataset: [Kaggle - Power System Faults Dataset](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)
* IBM Cloud: [https://www.ibm.com/cloud](https://www.ibm.com/cloud)
* Fault Detection Literature:

  * [IEEE Paper on Fault Detection](https://ieeexplore.ieee.org/document/10306740)
  * [Elsevier Article on Fault Detection](https://www.sciencedirect.com/science/article/pii/S2352484724007807)

## Author

**Jayasri K**
College of Engineering, Guindy
Anna University
Capstone Project under IBM Education Program


