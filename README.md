

# Heart Disease Prediction Model
### This is the sample provided by the sir during Ardent training classes. Many of us was facing the problems due to version compatibility issue.
#### In this repo, you will find all the intructions required to run the code in your PC/Laptop.

## Roadmap

1. Uninstall all the python versions installed in your system.
2. Install the Python v3.10.10, because it is used in Google Colab also due to the compatibility issues. You can install the Windows Installer for Python v3.10.10 by clicking on this 🔗[link](https://www.python.org/ftp/python/3.10.10/python-3.10.10-amd64.exe).
3. After installing the Python, make sure it is working by typing 
```bash
python --version 
```
4. It should say the version of Python installed.
5. After installing the python, clone this repo by forking or just by downloading the zip. After downloading the zip, unzip the folder.
6. Now, run the following command to install the **Python virtual environment** in your system. This is an important step.
```bash
pip install virtualenv  
```
7. Create a virtual environment 
```bash
virtualenv vHeartDisease
```
8. Activate the Virtual environment. 
```bash
.\vHeartDisease\Scripts\activate
```
You will see that your virtual environment will get started.

9. Next you will have to install all the requirements. To do that run the following command.
```bash
pip install -r requirements.txt
```
10. Now you have successfully installed the virtual environment with all the required packages with their specific version without any errors.
11. Now you can run the app by writing the command:
```bash
flask run --debug
``` 
And the application will start to run on http://localhost:5000



