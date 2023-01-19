# Network-Intrusion-Detection

This project is focused on developing a model for real-time network intrusion detection using machine learning techniques. The dataset used for this project consists of a wide variety of intrusions simulated in a military network environment.

The dataset was provided and it was created to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks.

A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labeled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.

For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features). The class variable has two categories:

    Normal
    Anomalous

The goal of this project is to train a model using this dataset to detect network intrusions in real-time. The model will be trained using various machine learning algorithms and the best performing model will be selected for deployment.

The project includes the following steps:

    Data Exploration
    Data Cleaning
    Feature Engineering
    Model Training
    Model Evaluation
    Model Deployment

The code is written in Python and the libraries used are pandas, numpy, sklearn, and others.

To run the code, you need to have Python and the necessary libraries installed on your machine. The code can be run using Jupyter notebook or any other IDE.

This project can be useful for network administrators and security experts to detect and prevent network intrusions in real-time.
