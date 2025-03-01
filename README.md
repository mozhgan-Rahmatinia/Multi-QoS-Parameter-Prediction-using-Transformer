# Enhancing NTMA with Simultaneous Multi-QoS Parameter Prediction using Transformer-Based Deep Learning

This repository contains the code for the research article titled "Enhancing NTMA with Simultaneous Multi-QoS Parameter Prediction using Transformer-Based Deep Learning". The project leverages a customized Transformer-based model to enable simultaneous prediction of multiple key Quality of Service (QoS) parameters, improving proactive network management and optimizing network resource allocation.

The article is accessible via the DOI: 10.1109/IST64061.2024.10843472 and can be found online at the following address: [https://ieeexplore.ieee.org/abstract/document/10843472](https://ieeexplore.ieee.org/abstract/document/10843472).


# Model Architecture 
![1- Network AI_short_enable drawio](https://github.com/user-attachments/assets/629865ec-557e-40fc-a209-5727fd32f034)


# Getting Started
Requirements
This code builds upon the original Transformer code available on [GitHub_Link](https://github.com/thuml/Autoformer), with modifications to suit our specific use case for QoS parameter prediction. Ensure you have the necessary dependencies installed as outlined in requirements.txt.


# Running the Code
Google Colab Setup:

The project is designed to run in a Jupyter Notebook environment (transformer_QoS.ipynb) on Google Colab.
This setup includes integration with Google Drive for easy data access and storage.
If running on your local system, you may remove or modify the Google Drive connection commands to suit your file path setup.
Execution:

Open transformer_QoS.ipynb in Google Colab.
Make sure to connect to Google Drive if you wish to save results there.
Run the cells to train the model and generate predictions.
Output:

Model results will be saved in two main directories:
result: Contains model checkpoints and interim data.
test_result: Stores final prediction results for analysis.

