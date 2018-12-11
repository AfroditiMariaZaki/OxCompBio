# Oxford WT Python course material
## Materials for the Oxford Biochemistry WT Python course
### Authors: Marc Daemgen, Anna Duncan, Nicholas Michelarakis, Fiona Naughton, Naushad Velgy, William Glass and Irfan Alibay

Currently this repository holds the files for the python section of the course (to be held on Tuesday the 11th of December 2018).

#### Contents:

The Python_tutorial_python3.ipynb jupyter notebook contains the course instructions and is accompanied by the Python_tutorial_solutions_python3.ipynb notebook which contains the solutions.

#### Python requirements:
Python 3.6+, MDAnalysis (conda-forge channel), Numpy, Matplotlib, nglview (bioconda channel).

#### Known bugs: 
The nglview part of the notebook does not work in non-Linux environments (Windows & MacOS).

#### Getting started:

##### On a Linux machine:

1) Install anaconda python (https://www.anaconda.com/download/) for python 3.6+
2) Execute the setup-conda-linux.sh script which will automatically set up a python environment named `WTcourse`
3) Before starting the jupyter notebook activate the conda environment via: `source activate WTcourse`
   If you wish to close this environment do: `source deactivate`


##### Oxford Biochemistry VM machines:

Executing the setup-oxfordWT.sh bash script will automatically set up a local anaconda python 3.6 environment named `WTcourse` adding relevant exports to your .bashrc file.


