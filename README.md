# Lagos State House Pricing Model


## Project description 
The proposed project, titled "Lagos State House Pricing Modle" seeks to address a pressing issue within the Lagos real estate market. This project is pivotal as it aims to provide an AI-driven solution for precisely predicting building prices. By doing so, it empowers buyers, sellers, and real estate professionals with data-driven insights to make informed decisions. The primary challenge at hand is the unpredictable nature of building prices in Lagos, Nigeria. The real estate market is subject to various factors, making it arduous for stakeholders to accurately estimate property values. As Ayodele and Olaleye (2022) emphasized, this complexity makes precise predictions a formidable task.

Currently, there is no comprehensive AI-based solution tailored for predicting building prices in Lagos. Traditional methods, including manual appraisal and historical data analysis, fall short in providing the accuracy and efficiency that AI can offer. Our proposed project represents an innovative approach to addressing this issue. Our project follows the established Data Science/Machine Learning (DS/ML) pipeline, including Data Sourcing, Data Cleaning and Preparation, ML Model Development, Model Evaluation, and Model Deployment.

1.	Data Sourcing:
•	Collected historical building price data from the Kaggle Housing Prices in Lagos, Nigeria dataset, which includes comprehensive information on location, size, features, and past sale prices (Kaggle Housing Prices in Lagos, Nigeria Dataset).
2.	Data Cleaning and Prep:
•	Carefully cleaned, formatted, and preprocessed the dataset to ensure its suitability for model training.
3.	ML Model Development:
•	Utilized a range of machine learning algorithms, including decision trees, and neural networks. The choice of these algorithms is based on their suitability for capturing the complex relationship between property features and market dynamics in Lagos.
4.	Model Evaluation:
•	Assessed the model's accuracy, reliability, and overall effectiveness using metrics like mean squared error and R-squared.
5. Model Deployment:
•	The project was deployed locally, and the source codes have been added to this repository


## Getting Started 
The project uses a Flask web framework, a machine learning model stored using Pickle, and it is recommended to use the Python Anaconda interpreter for pre-installed dependencies, This repo also contains a `requirement.txt` file specifying the necessary dependencies.

Prerequisites
• Anaconda installed on your machine
• Git installed on your machine

### Clone the Repository
### Create a virtual environment
1. ``` conda create --name your_env_name python=3.8 ```

2. Activate the virtual environment
   ``` conda activate your_env_name ```
### Install dependencies
1. Make sure you're in the directory containing `requirement.txt`
2. Install dependencies from `requirement.txt` using pip:
   ``` pip install -r requirements.txt ```

### Run the Flask Application
1. Ensure you're in the directory contain the `main.py` file
2. Run the flask application:
   ``` python main.py ```
   This command will start the development server, and you should see output indicating that the server is running.
3. Open a web browser and navigate to http://127.0.0.1:[port number]/ to view the running Flask application.


## Acknowledgments
We would like to express our gratitude to the following individuals who have contributed to or inspired this project:

Theo Peter: Thank you for your dedication and valuable contributions to the project. Your expertise and teamwork have greatly enriched the development process.

Babalola Elisha: Your hard work and creativity have been instrumental in the success of this project. We appreciate your commitment to excellence and collaborative spirit.

Team Mentor Emefe: Special thanks to our mentor, Emefe, for providing guidance, support, and valuable insights throughout the development of the project. Your mentorship has been crucial to our growth and success.

We would like to extend our heartfelt appreciation to the entire AI Saturday Family for their unwavering guidance, world-class materials, and the enriching cohort course that has played a pivotal role in our project's development. 

We also extend our appreciation to the open-source community and the following libraries and resources that have played a significant role in shaping and enhancing our project:

Flask: The lightweight and powerful web framework for Python that forms the backbone of our web application.

Pickle: The Python module used for serializing and deserializing the machine learning model, contributing to the functionality of our project.

GitHub: The platform that hosts our project and facilitates collaboration among team members.

We acknowledge and thank everyone who has been a part of this journey, directly or indirectly, contributing to the success of our project.

## Contact
Theo Peter;
  email: theonipeter@gmail.com
  mobile number: +234 805 730 3017
Babalola Elisha
  email: elitebabson@gmail.com
  mobile number: 08032223140


