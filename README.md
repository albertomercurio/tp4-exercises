# TP-IV Exercises

This repository contains numerical exercises on open quantum systems.

## Run Online — MATLAB Online & MyBinder

### MATLAB
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=matteosecli/tp4-exercises) Run the `.mlx` files in MATLAB Online.  
**Important:** you need a MathWorks account linked to a valid cloud license.
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matteosecli/jupyter-matlab/binder?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fmatteosecli%252Ftp4-exercises%26urlpath%3Dlab%252Ftree%252Ftp4-exercises%252F%26branch%3Dmain) Run the `.ipynb` files in Jupyter with the MATLAB kernel on myBinder.org, or use "Open MATLAB" and run the `.mlx` files.  
**Important:** you may have to manually run `cd tp4-exercises` in an empty Jupyter cell before running the notebook.  
**Warning:** it may take serveral minutes to launch the instance, plus more time to launch MATLAB the first time. MyBinder instances can be very slow and easily timeout. You need a MathWorks account linked to a valid cloud license.

### Octave
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matteosecli/jupyter-matlab/binder?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fmatteosecli%252Ftp4-exercises%26urlpath%3Dlab%252Ftree%252Ftp4-exercises%252F%26branch%3Dmain) Run the `.ipynb` files in Jupyter with the Octave kernel on myBinder.org.  
**Warning:**  MyBinder instances can be very slow and easily timeout.

### Julia
- [![Binder](https://mybinder.org/badge_logo.svg)](https://ovh.mybinder.org/v2/gh/matteosecli/jupyter-matlab/binder?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fmatteosecli%252Ftp4-exercises%26urlpath%3Dlab%252Ftree%252Ftp4-exercises%252F%26branch%3Dmain) Run the `-julia.ipynb` files in Jupyter with the Julia kernel on myBinder.org.  
**Warning:**  MyBinder instances can be very slow and easily timeout.

## Run Online — GitHub Codespaces

You can also use GitHub Codespaces runners if you have a GitHub account. Click on the button below to open the workspace (building will take quite some time):

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/matteosecli/tp4-exercises/tree/main)

Notes:
- The Julia kernel should work with no additional setup.
- The Octave kernel has to be manually selected under the "Jupyter kernels" section.
- The MATLAB kernel works only by re-launching the codespace with the "Jupyter Lab" editor after it has been built for the first time.

## Run Locally

### MATLAB
- Install MATLAB (depending on your system)
- Clone the repo via `git clone https://github.com/matteosecli/tp4-exercises.git` (preferred) or download a [zipped copy](https://github.com/matteosecli/tp4-exercises/archive/refs/heads/main.zip) and unzip it (discouraged)
- Open MATLAB in the folder containing the exercises
- Run the `.mlx` files
- Note: If you prefer to work with `.ipynb` files, you have to install the MATLAB/Jupyter integration first ([info](https://www.mathworks.com/products/reference-architectures/jupyter.html))

### Octave
- Install Octave (depending on your system)
- Clone the repo via `git clone https://github.com/matteosecli/tp4-exercises.git` (preferred) or download a [zipped copy](https://github.com/matteosecli/tp4-exercises/archive/refs/heads/main.zip) and unzip it (discouraged)
- Open Octave in the folder containing the exercises
- Run the `.m` files
- Note: If you prefer to work with `.ipynb` files, you have to install the Octave/Jupyter integration first ([info](https://github.com/Calysto/octave_kernel))

### Julia
- TODO
