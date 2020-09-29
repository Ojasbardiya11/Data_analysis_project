# Ref_score_project

Setup

Windows

Python install

Download latest from following URL https://www.python.org/downloads/

Add python path to environment variable.

pip install

Follow instructions in https://phoenixnap.com/kb/install-pip-windows Add path to Environment variable. Goto project folder and enter following command

  pip install -r requirements.txt
Ubuntu

Python install

  sudo apt install python3.7

  python3.7 --version
Sample Path

  /usr/bin/ffmpeg
The steps to install Jupyter notebook can be downloaded from here: https://jupyter.org/install

Aim: Use available data to evaluate customers into Promoters, Passives or Detractors by modelling a score analogous to NPS (Net Promoter Score)

Both basic and advanced data insights are provided with the available data to better understand customer performance across various parameters.

We generate the Ref Score using the following models-
* Random Forest
* Multiple Regression
* K-Nearest Neighbors

Taking the model which provides the highest accuracy, we then use that to evaluate other customers and classify them accordingly.


