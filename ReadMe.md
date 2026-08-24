# Start here
- [Download Python from here ](https://www.python.org/downloads/)
- We create **virtual environment** with the aim of isolating your python projects. There other techniques of isolationg your projects:
    - Docker
    - Kubernetes

## creating a virtual Environment: 
- create folder > open the folder on visual studio
- open terminal via visual studio
- run this: `python -m venv env` , kindly note `env` is the name of your environment
- to activate the environment:
    - on windows: 
        - approach one:
            - open `command prompt` on vs code
            - navigate to envrionment folder i.e `env` > open the `Scripts`
            - find `activate.bat` file 
            - click...hold and drag to the terminal space
            - press enter

        - approach 2: 
            - open `command prompt` on vs code
            - run this: `.\env\Scripts\activate.bat` 
            - press enter

    - for linux/ macos:
            - open terminal on vs code
            - run: `source env/bin/activate`

## Finally:
- Create a `.gitignore` file : it makes sure that you only version control what is meant to be version controlled


- install `scikit-learn`: `pip install -U scikit-learn` (make sure your environment is activated)

- install seaborn: `pip install seaborn`


## Useful links:
[Scatter plot with seaborn](https://seaborn.pydata.org/tutorial/relational.html)