# cyrest-challenge
## Introduction
This repository contains the python workflow for the Cytoscape v3.5 CyREST Challenge.

For more information and cyrest API see:
* `Challenge 2017`: http://nrnb.org/competition-2017.html  
* `cyREST API`: https://idekerlab.github.io/cyREST/  
* `cyREST examples`: https://github.com/idekerlab/cy-rest-python  
* `py2cytoscape`: https://github.com/idekerlab/py2cytoscape

## Submission
The snapshot from the following dynamic visualization of the Repressilator was submitted 
to the python category. 

<img src="./results/cytoscape-repressilator.gif" width="500"></img>

The workflow for creation is described and documented in the following Jupyter Notebook  
https://github.com/matthiaskoenig/cyrest-challenge/blob/master/cyrest-challenge.ipynb
 
## Installation
In the following section the setup of the python environment for executing the workflow is described.

### Virtual environment
The simplest way to run the cyrest workflow is via cloning the repository and setting up a python virtual environment. 
The virtual environment is used to execute the workflow notebook.
The requirements for execution listed in
see [`./requirements.txt`](https://github.com/matthiaskoenig/cyrest-challenge/blob/master/requirements.txt).
```
# clone repository
git clone https://github.com/matthiaskoenig/cyrest-challenge.git
cd cyrest-challenge

# setup virtual environment
mkvirtualenv cyrest-challenge
(cyrest-challenge) pip install -r requirements.txt
```

### Use virtual environment as jupyter kernel
```
# install kernel for ipython
(cyrest-challenge) python -m ipykernel install --user --name=cyrest-challenge

# Run notbook with the cyrest-challenge kernel
jupyter notebook cyrest-challenge.ipynb
Kernel -> Change kernel -> cyrest-challenge
Kernel -> Restart
```

## Run Workflow
To run the workflow open Cytoscape and run all cells in the notebook.

&copy; 2017 Matthias König.