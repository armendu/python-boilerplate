# Python Boilerplate Application

## Getting started
This application serves as a simple boilerplate for creating a Python application. It contains:
* A ```main.py``` file in ```src``` folder, that serves as the entry point for the application. 
* A ```requirements.txt``` file to define the libraries that are going to be used in the python app (Right now only ```logzero``` is set, and other libraries can be added if needed)
* The MIT License

## Requirements
* Python v3.8 (not sure about other versions)
* Pip

## Setting up a virtualenv
To setup a virtualenv follow these steps:
* Open a terminal in the root of the project
* Run ```pip3 install -U pip virtualenv``` or ```pip install -U pip virtualenv``` based on the installation of pip (this command installs virtualenv globally)
* Run ```virtualenv --system-site-packages -p python3 ./venv``` OR
```virtualenv --system-site-packages -p python ./venv``` based on the python version/installation that you are using
* Activate the virtualenv using the ```./venv/Scripts/activate``` command (Note: If the following message shows up:
```You must source this script: $ source ./venv/Scripts/activate```
Then just run ```source ./venv/Scripts/activate``` and it should work.)
* Install the packages located in the ```requirements.txt``` file using the following command: ```pip install -r requirements.txt```
* Run the app using: ```python src/main.py```

### Note:
User guide on how to freeze requirements: https://pip.pypa.io/en/stable/user_guide/#requirements-files

## License
This project is license under the MIT License.