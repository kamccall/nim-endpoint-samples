# nim-endpoint-samples
short and simple code examples that access various nvidia-hosted NIMs in NGC from a jupyter notebook

this readme covers three primary topics:
* client setup instructions
* enumeration and explanation of models included
* common errors encountered

## client setup instructions
summarily, the steps required to install and setup the required environment to run this locally are:
1. install anaconda3
2. clone this repo (or download the three required files: the .ipynb notebook, .py key file, and .yaml environment file)
3. create an environment with the necessary packages
4. obtain an nvidia NGC API key

### step by step instructions to perform these tasks
1. install anaconda
   - windows installation (https://docs.anaconda.com/anaconda/install/windows/)
   - macOS install (https://docs.anaconda.com/anaconda/install/mac-os/)
   - linux install (https://docs.anaconda.com/anaconda/install/linux/)
   - after you install anaconda3, you will have several programs such as the anaconda prompt and anaconda navigator.  when you select and run the anaconda prompt, it will open a command window with `(base)` on the left, indicating that you are now using the `base` conda environment with the default set of python3 packages. at that command line you can run the single command (in step 3 below) to set up a second environment that will contain the necessary packages or just install each of the required packages manually from the command line. 
2. obtain necessary files (using either of these options below)
   - click in the upper right to download and put all three files `nim-demo.ipynb`, `config.py` and `nv-nim-demo.yaml` into the same folder, or
   - run command `git clone https://github.com/kamccall/nim-endpoint-samples/`
3. create a new anaconda environment
   - run command `command here` 



## models supported in current version



## common errors encountered



