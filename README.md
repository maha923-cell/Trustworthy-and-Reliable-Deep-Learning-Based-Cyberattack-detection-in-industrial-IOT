# Trustworthy-and-Reliable-Deep-Learning-Based-Cyberattack-detection-in-industrial-IOT
 Project Overview
This project proposes a cyberattack detection mechanism for Supervisory Control and Data Acquisition (SCADA)-based Industrial Internet of Things (IIoT) networks. The solution utilizes a combination of deep learning and ensemble learning models to identify cyber threats in real-time. The detection system is based on Pyramidal Recurrent Units (PRU) and Decision Trees (DT) to enhance accuracy and reliability.

The project aims to address security vulnerabilities in IIoT networks by integrating novel detection mechanisms that improve the trustworthiness, privacy, security, and resilience of these networks, which are often exposed to cyber threats.

Abstract
In the modern era, SCADA-based IIoT networks are increasingly being integrated into industrial environments to improve operational efficiency and resource management. However, this integration introduces significant security challenges. Traditional security mechanisms fall short in safeguarding these networks due to protocol differences, limited update options, and outdated security measures.

To address this, we propose a novel approach that combines deep learning techniques, specifically Pyramidal Recurrent Units (PRUs), with traditional Decision Trees (DT) in an ensemble model to accurately detect cyberattacks. Our proposed mechanism aims to increase the trust and security of IIoT networks by leveraging a SCADA-based attack detection model.

System Components and Modules
The project is divided into the following key modules:

Service Provider:

Manages and serves the IIoT network's data for detection.
Train and Test Data:

Prepares and splits data into training and testing datasets to train the machine learning models.
Remote User:

Interface for remote users (e.g., admins, engineers) to interact with the system.
Prediction:

The heart of the system, where the deep learning model predicts cyberattack events based on the incoming IIoT data.
Graphic Analysis:

A graphical interface for visualizing prediction accuracy, attack types, and other key performance metrics.
Hardware and Software Requirements
Operating System: Windows 11 64-bit
Programming Language: Python
Frontend: HTML, CSS (for creating web interfaces)
Backend: MySQL (for database management)
Tools: XAMPP (for local server setup)
Existing System
SCADA-based IIoT networks consist of various field devices like sensors, actuators, and intelligent electronic devices connected to an enterprise network. This integration allows industries to improve production and resource efficiency but introduces vulnerabilities. These vulnerabilities expose the networks to cyberattacks, which compromise the security and trustworthiness of the entire industrial system.

Proposed System
The proposed solution integrates an ensemble detection mechanism combining Pyramidal Recurrent Units (PRUs) and Decision Trees (DT). This ensemble model effectively detects cyberattacks in IIoT networks and is scalable for large industrial networks. The system's ability to interoperate with other detection engines makes it highly adaptable and expandable to wider industrial environments.

Key Features:
Deep Learning-based Attack Detection: Utilizes PRU and DT for accurate detection of cyber threats.
Ensemble Learning: Combines different machine learning models for a more reliable detection mechanism.
SCADA Integration: Tailored for SCADA-based IIoT networks, ensuring relevant threat detection.
User Interface: Provides detailed logs and analysis of cyberattack predictions.
Accuracy Visualization: Graphical representation of model performance and prediction results.
Output Screens
Login Page: A secure login interface for users to access the system.
Model Accuracy: Displays the accuracy of the prediction model over time.
Accuracy Graph: A visual representation of model performance during training and testing.
Cyber Attack Prediction Details: Detailed information on detected attacks, their type, and system response.
Technologies Used:
Python: Used for machine learning, deep learning model training, and backend development.
MySQL: Database management for storing user data, attack logs, and model results.
HTML/CSS: For creating a user-friendly frontend interface.
XAMPP: Used for setting up a local server for backend services.
TensorFlow/Keras: For implementing and training the deep learning models (PRU).
Scikit-learn: For integrating Decision Trees and other traditional machine learning models.
