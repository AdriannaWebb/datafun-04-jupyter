# datafun-04-jupyter

Project 4 uses a combination of Python and Markdown
to create an initial data story in a Jupyter Notebook.
The project includes a project virtual environment with
popular libraries for data analytics including pandas, matplotlib, and seaborn,
and introduces a common process for starting exploratory data analysis projects.

Below are instructions on how to install and run this project locally.

## How to Install and Run the Project

## 1. Clone the Repository

First, clone the repository to your local machine:

```
git clone https://github.com/AdriannaWebb/datafun-04-jupyter.git
cd datafun-04-jupyter

Create a file in the root folder of your repo (same level as the README.md) named requirements.txt with the following content. 

jupyterlab 
numpy 
pandas
matplotlib 
seaborn 
scipy

## Install the packages 

install the packages listed in the requirements file with this command:

py -m pip install -r requirements.txt

2. Create a Virtual Environment
Create and activate a virtual environment using the following commands:

For macOS/Linux:

bash
Copy code
python3 -m venv .venv
source .venv/bin/activate

## 3. Create the requirements.txt File
Ensure that a requirements.txt file is present in the root folder of your repo (same level as the README.md). It should contain the following packages:

Copy code
jupyterlab
numpy
pandas
matplotlib
seaborn
scipy

## 4. Install the Required Packages
After activating your virtual environment, install the packages listed in the requirements.txt file using this command:


python3 -m pip install -r requirements.txt

## 5. Run JupyterLab

Once all the required packages are installed, run the following command to start JupyterLab:


jupyter lab

This will open JupyterLab in your browser, allowing you to run your notebooks.

## 6. Deactivate the Virtual Environment
Once you're finished working, deactivate the virtual environment using:

deactivate '''
