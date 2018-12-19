# DL_1819
Deep Learning Course, University of Twente

## DL_1819: Deep Learning - From Theory to Practice <br> Christoph Brune
   
<br>
<br>
   
## Python notebooks of the course

[Jypyter Online Repository - Binder](https://mybinder.org/v2/gh/ChristophBrune/DL_1819/master)

[3 Tutorial: Introduction to Python, MLP and Backpropagation](https://github.com/ChristophBrune/DL_1819/tree/master/codes/1_tutorial)

[9 Tutorial: CNN and RNN](https://github.com/ChristophBrune/DL_1819/tree/master/codes/9_tutorial)

[12 Tutorial: VAEs and GANs](https://github.com/ChristophBrune/DL_1819/tree/master/codes/12_tutorial)

<br>

## Local Python installation
<br>

Follow the following instructions to install Miniconda and create a Python environment for the course:

1. Download the Python 3.6 installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. Note for Windows: If you don't know if your operating system is 32-bit or 64-bit, then open Settings-System-About-System type to find out your xx-bit system.
   * Windows: Double-click on the `Miniconda3-latest-MacOSX-x86_64.exe` file. 
   * macOS: Run `bash Miniconda3-latest-MacOSX-x86_64.sh` in your terminal.
   * Linux: Run `bash Miniconda3-latest-Linux-x86_64.sh` in your terminal.
1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Install git: `conda install git`.
1. Download the GitHub repository of the course: `git clone https://github.com/ChristophBrune/DL_1819`.
1. Go to folder DL_1819 with `cd DL_1819`, and create a Python virtual environment with the packages required for the course: `conda env create -f environment.yml`. Note that the environment installation may take some time.  


   Notes: <br>
      The installed conda packages can be listed with `conda list`.<br>
      Some useful Conda commands are `pwd`, `cd`, `ls -al`, `rm -r -f folder/`<br>
      Add a python library to the Python environment: `conda install -n DL_1819 numpy` (for example)<br>
      Read [Conda command lines for packages and environments]<br>
      Read [managing Conda environments]

[managing Conda environments]: conda/conda_environments.pdf

[Conda command lines for packages and environments]: conda/conda_cheatsheet.pdf




<br> 
<br> 

## Running local Python notebooks 
<br>


1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Activate the environment. Windows: `activate deeplearn_course`, macOS, Linux: `source activate deeplearn_course`.
1. Download the python notebooks by direct downloads from the next section or with GitHub with the command `git pull`. 
1. Start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Go to the exercise folder, for example `DL_1819/codes/1_tutorial/lab01_python`.


	Notes:<br> 
      Windows: Folder DL_1819 is located at `C:\Users\user_name\DL_1819`. MacOS, Linux: `/Users/user_name/DL_1819`.<br>







[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://anaconda.org
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org


<br>
<br>



