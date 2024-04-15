# TechExcellenceAdvDataScience-DeepLearningDigitRecognizer

## Assignment
Tech Excellence Advanced Data Science Group Project 2 

## Project Authors
Tim Tieng, Arvind Krishnan

## Environement Setup
1. **Pyenv Installation** - We confirmed as a group that we have the package 'pyenv', 'virtualenv' installed locally to our machines. This allows us to make setup virtual environments to manage this project
2. **Project Folder Creation** - Additionally, we made sure that we have the same folder structure for project 2. We ensured that we have the following directories present/created on our local machines: Config, Data, Notebooks. This can be updated as the project progresses.
3. **Virtual Environment Creation** - As a team, we confirmed to work on a stable version of Python **Python 3.10.13**. To accomplish this, we ran the following commands:

        # For pyenv-enabled machines
        pyenv install 3.10.13
        pyenv virtualenv 3.10.13 TechEx_Project2
        pyenv activate TechEx_Project2

        # For Conda Environments
        conda create -n TechEx_Project2 python= 3.10.13
        conda activate TechEx_Project2
        
4. **Package Installation** - To ensure both local machines have all the required packages, we created a "requirements" text file that was added to our "Config" folder. This text file has the package names required to compelte this project. To install the packages outlined in the **pip_requirements.txt** file, we rand the following command in our local terminals within the "Config" folder:
        
        pip install -r pip_requirements.txt

## MLFlow
MLflow is an open-source platform for managing the end-to-end machine learning lifecycle. It offers tools to help with experiment tracking, reproducibility, model packaging, and deployment.  For this project, the group attempted to leverage MLFlow for determining and tracking the optimized parameters for two models used in this project. 

Key components of MLflow include:

1. **Tracking**: Record and query experiments to track metrics and parameters.
2. **Projects**: Package data science code in a reusable and reproducible format.
3. **Models**: Manage and deploy machine learning models in various environments.
4. **Registry**: Store, version, and share machine learning models.
5. **UI**: Web interface for visualizing and comparing experiment results
