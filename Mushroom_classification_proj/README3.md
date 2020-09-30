# Mushroom_Classification #

## Setup ##

* Windows

     * Python install
     
        Download latest from following URL https://www.python.org/downloads/
        
        Add python path to **environment variable**.
 
        
    * pip install
    
        Follow instructions in https://phoenixnap.com/kb/install-pip-windows
        Add path to Environment variable.
        Goto project folder and enter following command 
        
            pip install -r requirements.txt
        
* Ubuntu
    * Python install
    
            sudo apt install python3.7
        
            python3.7 --version
  
        **Sample Path**
        
            /usr/bin/ffmpeg
      
        
* The steps to install Jupyter notebook can be downloaded from here: https://jupyter.org/install

* Conda install 
     * Steps to install anaconda can be found here https://docs.anaconda.com/anaconda/install/



## Description ##

We use pandas, numpy, and sklearn in Python 3.7 to generate-
* A Random Forest classifier in order to determine mushrooms as poisonous or edible with 99.01% accuracy.
* A Logisitic Regression Model that predicts whether mushrooms are poisonous or edible with 94.91% accuracy.

### Input ###
* datasets_478_974_mushrooms.csv.csv
  
  The main dataset is available at https://www.kaggle.com/uciml/mushroom-classification
  
### Command to Run ###

Download as .py file and run the following on the command line
            
    python Mushroom_classification.py  