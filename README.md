# Vehicle Classification using ML
**Vehicle Classification** has emerged as an important field of study because of its importance in traffic management, surveillance, security systems, etc. GPS enabled location trackers can store the location history of terrestrial vehicles via satellite. This data can further be used for various analytical purposes. ***One such purpose is determining the class of vehicles.***

## Aim
The prime objective of this project is to determine, as accurately as possible, the class of vehicles in the given dataset through various machine learning techniques.

## Index
- [Directory structure](#directory-structure-index)
- [Tech used](#tech-used-index)
- [Dev setup](#dev-setup-index)
- [Python packages](#python-packages-index)
- [How to run](#how-to-run-index)
- [Testing and Results](#testing-and-results-index)
- [Credits](#credits-index)


## Directory structure [[Index](#index)]
```bash
.
├── GPS_Vehicular_Classification.ipynb
├── README.md
├── ReadMe.pdf
└── Vehicle_Classification_using_GPS_Data.pdf
```

- [GPS_Vehicular_Classification.ipynb](GPS_Vehicular_Classification.ipynb) contains the complete code which is divided into following four sections:
  - **Mounting necessary files:** Run this code to have the environment set up with all the necessary files.
  - **Importing necessary prerequisites:** Run this piece of code to import the necessary libraries and download the dependencies.
  - **Preprocessing:** Run this piece of code preprocess the data. Please refer to the code for block-by-block details. Also, please note that ceratin changes to the names of the files may be required as per the situation.
  - **Training:** Run this code for training the model on the preprocessed data. Again, please refer to the comments of the code for more details.

## Tech used [[Index](#index)]
- python3.8
- conda
- Jupyter notebook

## Dev setup [[Index](#index)]
- Install python either [from source or from PPA](https://tech.serhatteker.com/post/2019-12/how-to-install-python38-on-ubuntu/). Here's how to install python3.8 using PPA:
  ```bash
  sudo apt update
  sudo apt install software-properties-common
  sudo add-apt-repository ppa:deadsnakes/ppa
  sudo apt update
  sudo apt install python3.8
  ```
  Check installation by running `python3.8 --version`. You should get `Python 3.8.1` as output.

- To install conda (You can also refer to [SO](https://stackoverflow.com/questions/28852841/install-anaconda-on-ubuntu-or-linux-via-command-line) or [Conda Docs](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)):
  - First choose the version that you would like to download by going to [this](https://repo.anaconda.com/archive/). We recommend you to download the latest version. At the time of writing this readme, `Anaconda3-2020.11-Linux-x86_64.sh` is the latest version available. Now, run the following commands: 
    ```bash
    wget -c https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh
    bash Anaconda3-2020.11-Linux-x86_64.sh
    ```
    **Note that you can replace `Anaconda3-2020.11-Linux-x86_64.sh` with the your own choice in the above commands.**
  
  - To make the changes take effect, close and then re-open your terminal window.
  - To test your installation: in your terminal window or Anaconda Prompt, run the command `conda list`. A list of installed packages appears if it has been installed correctly.

- To [install jupyter lab](https://jupyter.org/install) use:
  ```bash
  pip install jupyterlab
  ```

## Python packages [[Index](#index)]
The code has dependency on following python packages:
- scikit-learn (`conda install -c anaconda scikit-learn`)
- xgboost (`conda install -c conda-forge xgboost`)
- matplotlib (`conda install -c conda-forge matplotlib`)
- glob (`sudo pip install glob2`)
- keras (`conda install -c anaconda scikit-learn`)
- pyproj (`conda install -c conda-forge pyproj`)
- pandas (`conda install -c anaconda pandas`)
- numpy (`conda install -c anaconda numpy`)

If there are any other packages which we have missed, they can also be downloaded using `conda install -c anaconda <package-name>`.

## How to run [[Index](#index)]
The code can be run by any of the two ways:
1. Using Jupyter Notebook: Press `Shift + Enter` to run the cell. Follow for each cell.
2. Using command line: Use `./src` command. The command will finish silently (No Prompts).
**We recommend to use method 1, since progress can be tracked as prompt messages are displayed by the code.**

## Testing and Results [[Index](#index)]
We have prepared a complete [document](Vehicle_Classification_using_GPS_Data.pdf) giving information of the dataset used, traning methods, testing and validation and conclusion.

## Credits [[Index](#index)]
I hereby acknowledge the contribution of [Swadesh Vaibhav](https://github.com/swadesh-vaibhav) in this project.
