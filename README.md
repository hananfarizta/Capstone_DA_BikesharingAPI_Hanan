# Capstone API

In most cases when we are running a business, there are a lot of data stakeholder outside our company. The problem is that we need to provide the access in a way that they will not break our security rules or concerns. One way to solve that is by creating an API for the database. In this project, we will introduce you on how python is used for data transaction management using Flask API.

**Usecase**: Bikeshare App\
Have you ever rent a bike for faster mobility in town? In the past few years, this business once become a phenomenom. In Indonesia, there are lots of similar services, for example, the Jakarta government's "GOWES" bike sharing service that launcehd in July 2020.

For the user perspective, the general journey is denoted as follows:

- User scan the bike located at some bike station, sending the data to database as the intent of "start riding"
- Once user has reached its destination station, he/she put back the bike, sending the data again to the database as the intent of "finished riding"

For each activity, there are data transactions between user and database. And how do you think each user's phone communicate with the server for storing and receiving the data? Using API ofcourse!

We will later create a simplified version of the API service which handles data transactions and analysis.

# Installation

## Prerequisites

- **Python** with **Jupyter Notebook**, installed with **required libraries**
- **Visual Studio Code (VSCode)**: Recommended for writing application scripts
- **TablePlus**: Recommended for easy database access and exploration
- **Postman**: Optional for easy API testing

## Running the Application

_Copy this command on your terminal or git bash_

- Clone project from github:

```bash
https://github.com/hananfarizta/Capstone_DA_BikesharingAPI_Hanan.git
```

- Open Folder:

```bash
cd Capstone_DA_BikesharingAPI_Hanan
```

- Create new virtual environment with:

```bash
conda create --name your_virtual_env python=3.10
```

- Check virtual environment

```bash
conda env list
```

- Activate the new virtual environment:

```bash
conda activate your_virtual_env
```

- Install requirements.txt:

```bash
pip install -r requirements.txt
```

- Open Jupyter Notebook:

```bash
jupyter notebook
```

- Open VS Code and run:

```bash
python app.py
```
