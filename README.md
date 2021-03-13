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

Install it as development package:

    pip install -e ./package-name
