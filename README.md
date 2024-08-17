# **Automated Super Mario Agent Using Reinforcement Learning**

## **Project Overview**

This project aims to develop an automated super mario agent leveraging reinforcement learning (RL) techniques. Specifically, we implement and compare two advanced RL algorithms: **Deep Q-Network (DQN)** and **Proximal Policy Optimization (PPO)**. The objective is to train the model that can play mario game effectively.

## **Getting Started**

### **Prerequisites**

Ensure you have Python 3.7+ installed on your system. Install the required packages using `pip`:

### **Setting Up the Project**

##### **1. Clone the Repository:**

   ```bash
   git clone https://github.com/visptl098/RL_Final_Project.git
   cd RL_Final_Project
   ``` 

##### **2. Create a virtual environment, run the following commands from the root folder:**
* Initialize a virtual environment: `python -m venv venv`
* Activate the virtual environment:
- Linux or Mac: source `./venv/bin/activate`
- Windows Powershell: `.\venv\Scripts\Activate.ps1`
* Install the Python packages: `pip install -r requirements.txt`
* Install ipykernel: `python -m ipykernel install --user --name=venv --display-name=venv`

##### **2. To run the code**
* Run the `DQN_Mario/dqn_mario.ipynb` file with selecting the `venv` kernel
* Then Run the `PPO_Mario/Mario.ipynb` file with selecting the `venv` kernel