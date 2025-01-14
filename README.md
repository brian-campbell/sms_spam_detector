# AI Bootcamp - SMS Spam Detector - Module 21 Challenge

## Table of Contents
*  [**Overview**](#overview)
*  [**Background**](#background)
*  [**Files**](#files)
*  [**Technical Requirements**](#technical-requirements)
*  [**Run the code**](#run-the-code)
*  [**Requirements and Solution**](#requirements-and-solution)

## Overview
This repository contains the source code for the OSU AI Bootcamp data sourcing challenge for Module 21. This challenge focuses on using AI/ML techniques to predict if a message is spam or not.

## Background
This challenge refactors code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, a Gradio app is developed to host the application. This app enabling users to test text messages. The application provides feedback to users, indicating whether the text is classified as spam or not, based on the model's performance.

## Files
This repository contains four files:
*  gradio_sms_text_classification.ipynb - this file is the final solution for the project. It is a Jupyter Notebook. It contains all the required code to solve for the challenge based on specified requirements.
*  gradio_sms_text_classification_orig.ipynb - this is the orginal file provided by the class. It is only here for reference purposes and is not part of the final solution.
*  sms_text_classification_solution.ipynb - this is the original file that contains the code for the SMS text classification solution that was refactored and included in the final solution file `gradio_sms_text_classification.ipynb.` No changes were made to this file.
*  sms_text_classification_solution_orig.ipynb - this file is the same as `sms_text_classification_solution.ipynb.` It was added to the project when the repository was originally created. It serves no purpose and is an artifact that could be removed.

The directory `Resources` contains a file `SMSSpamCollection.csv` that is the data input for the Challenge.

## Technical Requirements
The code for the Challenge is in `gradio_sms_text_classification.ipynb.` This file is a Jupyter Notebook and requires an appropriate jupyter, pandas, prophet, and python tooling installed. This can include environmental containers such a anaconda, etc. It can also be executed inside of an IDE such as Visual Studio Code. The code requires python 3.10 or greater.


## Run the code
Assuming a python interpreter is installed and is at least version 3.10 or greater, the jupyter notebook runtime, and the prophet framework from Meta/Facebook, the program can be executed by calling the jupyter notebook runtime in the directory: E.g., $> jupyter notebook. Once the notebook is running you run each code fragment individually or click on the "Run All" button. It can also be run in Google's Collab.

Alternatively it can be executed from within and IDE if the IDE is configured to run python code and is at least 3.10 compatible and a jupyter notebook runtime is installed.

The jupyter notebook requires the `gradio` framework along with several modules from `sklearn.` The jupyter notebook uses `pip` to install gradio.


## Requirements and Solution
The solution to the challenge meets all the specified requirements:
1. An SMS Classificaiton Function is created
2. An SMS Prediction Function is created
3. A Gradio App is created that uses the Prediction and Classification functions to take text input from a user, user the prediction function to predict if the text is spam or not, and display the result to the user.

The Challenged provided 4 text messages to test the application. The images below show how the solution performs against those 4 text messages.

![Screenshot 2024-10-03 at 6 33 13 PM](https://github.com/user-attachments/assets/056705db-18dd-4cdf-a7bb-663e6ce5f8fa)
![Screenshot 2024-10-03 at 6 34 18 PM](https://github.com/user-attachments/assets/6661d567-57d2-4e97-aa0d-2eaf0d927dc2)
![Screenshot 2024-10-03 at 6 35 18 PM](https://github.com/user-attachments/assets/2ef60538-066e-47cb-831a-046fd546b7b5)
![Screenshot 2024-10-03 at 6 31 37 PM](https://github.com/user-attachments/assets/d1f3b572-0d27-4aa7-b4e5-87c9dc9cd325)
