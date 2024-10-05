# nim-endpoint-samples
short and simple code examples that access various nvidia-hosted NIMs in NGC from a jupyter notebook

this readme covers three primary topics:
* client setup instructions
* enumeration and explanation of models included
* common errors encountered

## client setup instructions
summarily, the steps required to install and setup the required environment to run this locally are:
1. install anaconda3
2. clone this repo (or download the three required files: the .ipynb notebook, .py key file, and .txt environment file)
3. create an environment with the necessary packages
4. obtain an nvidia NGC API key

### step by step instructions to perform these tasks
1. install anaconda
   - windows installation (https://docs.anaconda.com/anaconda/install/windows/)
   - macOS install (https://docs.anaconda.com/anaconda/install/mac-os/)
   - linux install (https://docs.anaconda.com/anaconda/install/linux/)
   - after you install anaconda3, you will have several programs such as the anaconda prompt and anaconda navigator.  when you select and run the anaconda prompt, it will open a command window with `(base)` on the left, indicating that you are now using the `base` conda environment with the default set of python3 packages. at that command line you can run the single command (in step 3 below) to set up a second environment that will contain the necessary packages or just install each of the required packages manually from the command line. 
2. obtain necessary files (using ***either*** of these options below)
   - click in the upper right to download and put all three files `nim_demo.ipynb`, `config.py` and `nim_demo_env.txt` into the same folder, OR
   - run command `git clone https://github.com/kamccall/nim-endpoint-samples/` (requires installation of git bash)
3. create a new anaconda environment (run ***both*** of the commands below)
   - run command `conda create --name nim_demo --file nim_demo_env.txt` (creates a new anaconda environment that contains all necessary packages)
   - run command `conda activate nim_demo` (makes the new `nim_demo` environment the active anaconda environment) 
4. obtain an nvidia NGC API key
   - login to (https://catalog.ngc.nvidia.com/)
   - in the upper right corner, click on <your login name>, and then select `Setup` from the menu
   - in the upper section **Keys/Secrets**, click on the green box `Generate API Key`
   - in the upper right, click on the green box `+ Generate API Key`
   - after you **CONFIRM** that you wish to generate a key, immediately **COPY** and **SAVE** that key somewhere! (text file, onenote, somewhere!)
   - open the `config.py` file and fill in the blank with the new generated API key using the guidance in the comments in the file
   - **SAVE** the `config.py` file and close it

## models supported in current version



## common errors encountered



