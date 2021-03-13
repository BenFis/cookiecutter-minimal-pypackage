cookiecutter-minimal-pypackage
==============================

An opinionated, minimal [cookiecutter](https://github.com/audreyr/cookiecutter) template for Python packages, and some guidelines for Python packaging.

Usage (How to create a new package)
-----

    pip install cookiecutter
    
Change Directory to where the new package should be installed.    
    
    cookiecutter https://github.com/BenFis/cookiecutter-minimal-pypackage

Confirm or modify the package name, url, etc. 

-> A folder structure for the new package will be created

-> further modify the setup.py, requirement.txt, etc. ...

Create a new GitHub repo (e.g. torch_helper_toolbox) and push the folder to it: 

    git init
    git add .
    git commit -m "first commit"
    git remote add origin https://github.com/BenFis/torch_helper_toolbox.git
    git push -u origin master

Install it as development package:

    pip install -e ./package-name

Use magic to use the development package with Jupyter Notebooks:

    %load_ext autoreload
    %autoreload 2
