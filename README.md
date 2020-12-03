## Clone this project

1. If you are in Windows, open `Git Bash`. If you are in Mac, open `Terminal`.
2. Run code `git clone https://github.com.cnpmjs.org/Crayon-ShinChan/ids-project.git`.
3. Enter your username and password of Github to start clone.

## Creating Python environment for this project

At the first time:

1. Install [Anaconda](https://docs.anaconda.com/anaconda/install/) in your computer.
2. If you are in Windows, open `Anaconda Prompt`. If you are in Mac, open `Terminal`.
3. Use `cd` command to enter the project folder, i.e. the folder where the `workflow.ipynb` file is located.
4. Run `conda env create -f ./env/ids-kuiliang.yml` to create an environment from `ids-kuiliang.yml`
5. Activate the environment by `conda activate ids-kuiliang`.
6. Run code `jupyter notebook`.
7. Find `workflow.ipynb` and open it.

Next time you can use two simple commands to access this environment and `workflow.ipynb`

1. `conda activate ids-kuiliang`.
2. `jupyter notebook`.
