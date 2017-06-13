# cyrest-challenge
## Introduction

Challenge 2017: http://nrnb.org/competition-2017.html  
`cyREST API`: https://idekerlab.github.io/cyREST/
`py2cytoscape`: https://github.com/idekerlab/py2cytoscape

## Dependencies
### cytoscape
`cytoscape>=3.5.1`  
`cy3sbml>=v0.2.2`
### python
see `requirements.txt`

## Installation
### virtual environment
To run the analysis and create the image a python virtual environment should be created.
```
# clone repository
git clone https://github.com/matthiaskoenig/cyrest-challenge.git
cd cyrest-challenge

# setup virtual environment
mkvirtualenv cyrest-challenge
(cyrest-challenge) pip install -r requirements.txt
```

### use virtual environment as jupyter kernel
```
# install kernel for ipython
(cyrest-challenge) python -m ipykernel install --user --name=cyrest-challenge

# start jupyter notbook
jupyter notebook

# select notebook for model (cyrest-challenge.ipynb) and run notbook with the cyrest-challenge kernel
Kernel -> Change kernel -> cyrest-challenge
Kernel -> Restart & Run All
```


