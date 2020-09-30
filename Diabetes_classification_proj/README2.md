# Diabetes_Classifier #

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
* A KNN classifier in order to determine whether patients have diabetes or not with 78.81% accuracy using the following factors -
    * Glucose Level
    * Blood Pressure
    * BMI
    * Skin Thickness
    * Age
    * Insulin Level
* We determine for which which value of K the model is optimized and apply it accordingly.

### Input ###
* datasets_228_482_diabetes.csv
  
  The main dataset is available at https://www.kaggle.com/uciml/pima-indians-diabetes-database
  
### Command to Run ###

Download as .py file and run the following on the command line
            
    python Diabetes_classifier.py  