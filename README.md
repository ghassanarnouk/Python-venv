# Python-venv

Instructions on how to activate and install packages in a virtual python environment

## Creating .venv 

1. Clone the git repository from GitHub
2. Navigate inside the git directory  
3. Run the following command `python -m venv .venv`
4. Activate the virtual environemnt by running the following command `source .venv/bin/activate`
5. The virtual environemnt can be deactivated by running `deactivate` anywhere within the directory
6. To install a specific package:
    1. Ensure the virtual environment is activated
    2. Run the following command `pip install <package-name>`
7. If a `requirements.txt` is present within the git repository
    1. Ensure the virtual environment is activated
    2. Run the following command `pip install -r requirements.txt`
8. The virtual environemnt is created and all required packages are installed.

## More .venv info 

For more information regarding the creation of virtual environments in Python, visit the following [link](https://docs.python.org/3/library/venv.html)