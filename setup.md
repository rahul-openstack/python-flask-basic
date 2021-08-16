
References: https://code.visualstudio.com/docs/python/tutorial-flask

Step 1: 
py -m venv env

Step 2: 
Command Palette or (Ctrl+Shift+P)). Then select the Python: Select Interpreter command:

Step 3: 
From the list, select the virtual environment in your project folder that starts with ./env or .\env:

Step 4: 
python -m pip install --upgrade pip

Step 5: 
python -m pip install flask

Step 6: 
Open Powershell in Admin Mode-> 
    get-ExecutionPolicy

If value is Restricted, then use the command
    set-executionpolicy remotesigned

Reference: https://www.stanleyulili.com/powershell/solution-to-running-scripts-is-disabled-on-this-system-error-on-powershell/



Step 7: 
VS Code activates the environment automatically when you use Terminal: Create New Integrated Terminal.


Step 8: 
Add the app.py file 

Step 9:
python -m flask run


Step 10: 
