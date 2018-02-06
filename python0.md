 
# Introduction to Python
## Part 0: Installing Python, Anaconda, and other Dependancies
Hosted by and maintained by the [Statistics Undergrad Student Association (SUSA)](https://susa.berkeley.edu).

# Installing Python & Anaconda
## For Mac
1. Visit [the Anaconda website](https://www.anaconda.com/download/) and click the Mac icon. Install the Python 3.6 version of Anaconda.
2. Run the downloaded .pkg file, and begin to step through the installation process. On the `Destination Select` stage, highlight `Install for me only` before continuing. 
3. When finished, Anaconda, Python, pip, and other Python libraries will be installed on your machine. To test your installation, navigate to the `anaconda3` folder, usually found by typing the following into your Terminal and pressing Enter:
```bash
cd ~/anaconda3/
```
Then, run the conda command in the `/bin/` folder by typing the following into your Terminal and pressing Enter:
```bash
./bin/conda list
```
If a list of packages is displayed on your screen, Anaconda installed successfully!
5. If Anaconda installed successfully, you'll want to add Anaconda commands to what's called your PATH. This allows you to run Anaconda commands, like `conda`, `pip`, and `ipython` without navigating to your Anaconda installation folder first. To refresh your path, and therefore add Anaconda to it, type the following into your Terminal:
```bash
source ~/.bash_profile
```
4. Next, we'll need to install iPython so that you can view iPython notebooks, such as those hosted in the SUSA Crash Courses repository.
First, run the following conda commands in your Terminal:
```bash
conda update conda
conda update ipython
conda update jupyter
```
5. You should now be able to launch and interact with iPython notebook files. To do so, navigate to the directory containing iPython files with:
```bash
cd /your/ipython/directory/here
```
and then run
```bash
jupyter notebook
```