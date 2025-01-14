# Plant Growth Data Classification 🌱

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [License](#license)
  * [Credits](#credits)

## Demo
Link: [https://plantgrowthclassifier.app](https://plantgrowthclassifier.app)

[![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLR5XHKiLDj74n4Wuh8z9sfqmlsOa9CZlzTg&s)](lik)

## Overview
The **Plant Growth Data Classification** project predicts the growth milestones of plants based on environmental and management factors such as soil type, sunlight hours, water frequency, fertilizer type, temperature, and humidity. By analyzing these factors, the project provides insights into optimal agricultural practices and greenhouse management.

## Motivation
The growing need to optimize agricultural practices inspired this project. Understanding how environmental factors influence plant growth can help farmers and researchers improve crop yield and sustainability. The idea took shape during exploratory research on plant growth and deep learning applications.

## Technical Aspect
This project has two components:
1. **Model Training**:
   - Trained a classification model using machine learning and deep learning techniques (e.g., Random Forest, Neural Networks).
   - Handled categorical features using one-hot encoding and scaled numerical features.

2. **Application Deployment**:
   - Built a Flask web application for real-time predictions.
   - Integrated interactive visualizations to display predictions and insights.


## Installation
The Code is written in Python 3.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

# To clone the repository

```bash

gh repo clone Creator-Turbo/Dog-vs-cat-clf-

```
# Install dependencies: (all lib)
```bash
pip install -r requirements.txt
```



## Run
To train the Deep leaning models:
 To run the Flask web app locally
```bash
python app.py

```
# Deployment on Render

## To deploy the Flask web app on Render:
Push your code to GitHub.<br>
Go to Render and create a new web service.<br>
Connect your GitHub repository to Render.<br>
Set up the environment variables if required (e.g., API keys, database credentials).<br>
Deploy and your app will be live!



## Directory Tree 
```
Plant Growth Data Classification
├── venv/                        # Virtual environment directory
├── deep learning                # Placeholder file for deep learning script
├── plant_growth_data.csv        # Dataset containing plant growth data
├── PlantGrowthClf.ipynb         # Jupyter notebook for classification work
├── README.md                    # Readme file describing the project
├── report.html
                                 # Report file (possibly from EDA or profiling)
```

## To Do




## Bug / Feature Request
If you encounter any bugs or want to request a new feature, please open an issue on GitHub. We welcome contributions!




## Technologies Used
Python 3.10<br> 
scikit-learn<br>
TensorFlow <br>
Flask (for web app development)  <br>
Render (for hosting and deployment)  <br>
pandas (for data manipulation) <br>
numpy (for numerical operations)  <br>
matplotlib (for visualizations) <br>



![](https://forthebadge.com/images/badges/made-with-python.svg)


[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/260px-Scikit_learn_logo_small.svg.png" width=170>](https://pandas.pydata.org/docs/)
[<img target="_blank" src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*RWkQ0Fziw792xa0S" width=170>](https://pandas.pydata.org/docs/)
  [<img target="_blank" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDzf1RMK1iHKjAswDiqbFB8f3by6mLO89eir-Q4LJioPuq9yOrhvpw2d3Ms1u8NLlzsMQ&usqp=CAU" width=280>](https://matplotlib.org/stable/index.html) 
 [<img target="_blank" src="https://icon2.cleanpng.com/20180829/okc/kisspng-flask-python-web-framework-representational-state-flask-stickker-1713946755581.webp" width=170>](https://flask.palletsprojects.com/en/stable/) 
 [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/512px-NumPy_logo_2020.svg.png" width=200>](https://aws.amazon.com/s3/) 







## Team
This project was developed by:

- [GitHub](https://github.com/Creator-Turbo)  
- [LinkedIn](https://www.linkedin.com/in/bablu-kumar-pandey-313764286/)
* **Personal Website**: [My Portfolio](https://creator-turbo.github.io/Creator-Turbo-Portfolio-website/)




## Credits

Special thanks to the contributors of the tensorflow library for their fantastic machine learning tools.




## To inprove this model 
