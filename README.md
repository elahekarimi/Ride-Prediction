# Ride Value Prediction - Jupyter Notebook

## Overview  
This project includes a Jupyter Notebook (`predict_ride_value.ipynb`) for predicting ride values using machine learning. It processes location-based data and applies multiple regression models.  

## Requirements  
Ensure you have Python installed (recommended: Python 3.8 or later). Required dependencies are listed in `requirements.txt`.  

## Setup Instructions  

### 1. Create and Activate a Virtual Environment  
Open a terminal and run:  

#### On macOS/Linux:  
```bash  
python3 -m venv env  
source env/bin/activate  
```  

#### On Windows (Command Prompt):  
```cmd  
python -m venv env  
env\Scripts\activate  
```  

### 2. Install Dependencies  
Once the virtual environment is activated, install the required packages:  
```bash  
pip install -r requirements.txt  
```  

### 3. Add Virtual Environment to Jupyter Notebook  
To use this environment in Jupyter, install the `ipykernel` package and add the kernel:  
```bash  
pip install ipykernel  
python -m ipykernel install --user --name=env --display-name "Python (env)"  
```  

### 4. Run Jupyter Notebook  
Launch Jupyter Notebook and open `predict_ride_value.ipynb`:  
```bash  
jupyter notebook  
```  

## Files in this Repository  
- `predict_ride_value.ipynb` - Jupyter Notebook for ride value prediction  
- `predict_ride_value.html` - Exported HTML version of the notebook  
- `estonia_addresses.csv` - Dataset containing location-based address data  
- `robotex5.csv` - Additional dataset for analysis  
- `requirements.txt` - List of required Python packages  

---  
Follow these steps, and you should be able to run the notebook successfully. 🚀  

