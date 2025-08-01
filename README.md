#🧠 Mental Health Consequence Prediction using AutoAI

This repository contains a Jupyter Notebook that uses IBM Watsonx AutoAI to train machine learning models that predict mental health consequences in the workplace, based on demographic, professional, and psychological survey data.

✅ This notebook leverages the ibm-watsonx-ai package with Python 3.11 to automate model training, comparison, and evaluation — no manual tuning required

#📋 Dataset Overview

This project is based on a mental health survey dataset containing responses from individuals across various countries and work environments. The target variable for prediction is:

mental_health_consequence
(Will there be negative consequences if the respondent discusses a mental health issue at work?)

#🧾 Input Features

Column Name	               Description
Timestamp	                 Date and time of the response
Age                    	   Age of the respondent
Gender	                   Gender identity
Country	                   Country of residence
State	                     U.S. state (if applicable)
Self_employed	             Whether the respondent is self-employed
Family_history	           Family history of mental illness
Treatment	                 Whether they have sought treatment for mental health
Work_interfere         	   How mental health affects work performance
No_employees	             Company size
Remote_work	               Whether they work remotely
Tech_company          	   Whether they work in a tech company
Benefits              	   Whether mental health benefits are provided
Care_options	             Availability of mental health care options
Wellness_program	         Workplace wellness programs
Seek_help	                 Ease of accessing mental health support
Anonymity	                 Anonymity provided by the company
Leave	                     Policies for mental health-related leave
Phys_health_consequence	   Physical health consequence for discussing issues
Coworkers	                 Comfort level discussing mental health with coworkers
Supervisor	               Comfort level discussing with supervisor
Mental_health_interview	   Comfort in discussing mental health in interviews
Phys_health_interview	     Comfort in discussing physical health in interviews
Mental_vs_physical	       Perceived importance: mental vs physical health
Obs_consequence	           Observed consequences of discussing mental health
Comments	                 Open-text comments (excluded from training)

#🎯 Project Goals

The objective of this notebook is to:

✅ Load and explore mental health survey data
✅ Preprocess data for model training
✅ Use IBM Watsonx AutoAI to automatically train models
✅ Compare model performance
✅ Predict mental_health_consequence for new/unseen survey responses

#🛠️ Requirements

->Python 3.11
->ibm-watsonx-ai package
->IBM Cloud account with Watsonx credentials

#🔍 Example Use Case

This notebook helps predict if individuals believe discussing mental health at work may lead to negative consequences — a valuable insight for HR teams, wellness program designers, and mental health advocates in the workplace.

#📄 License
This project is licensed under the MIT License.

3🙏 Acknowledgments
Thanks to the open mental health survey contributors and IBM Watsonx for enabling fast, low-code AutoML experimentation.
