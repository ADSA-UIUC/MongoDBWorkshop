# MongoDBWorkshop - Introduction to NoSQL and MongoDB
Code used in the ADSA NoSQL/MongoDB Workshop

## Downloading and installing MongoDB

### Windows
Download the installer from the [MongoDB website](https://www.mongodb.org/downloads#production). The version you'll want is `Windows 64-bit 2008 R2+`. Start and continue with the installation as instructed.

### Mac
1. Install Homebrew by copy-pasting this command into the terminal:

    `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

2. Then install MongoDB using `brew install mongodb`.

### Linux
Follow the instructions on the [MongoDB website](http://docs.mongodb.org/master/tutorial/install-mongodb-on-ubuntu/?_ga=1.17431161.1373552459.1443139119#install-mongodb).

## Downloading and installing MiniConda
1. Follow the instructions to install MiniConda on the [Conda website](http://conda.pydata.org/docs/install/quick.html#quick-install).
2. Create a conda environment by copy pasting this into the terminal:

    conda create --name adsa ipython-notebook

3. Activate the environment by typing `source activate adsa` (Mac/Linux) or `activate adsa` (Windows).
4. Start the iPython Notebook by browsing into the directory you downloaded this Workshop's files and run `ipython notebook`.

## Installing PyMongo
Install PyMongo from the conda package directory by typing into the terminal:

    conda install pymongo

If this installation gives you issues, Google `install pip` and download and install that. And then type into the terminal:

    pip install pymongo
