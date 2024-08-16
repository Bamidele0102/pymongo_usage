# This repository is a lab for using Python to access MongoDB using pymongo driver

- Access the MongoDB database from Python with the pymongo driver

- Perform basic operations such as selecting, inserting and listing using Python

- Create a Python program to run the MongoDB operations

## Install the pymongo driver

We need the pymongo driver to be installed in order to access the mongodb database from Python.

Run the below command on the terminal.

```bash
1 python3 -m pip install pymongo
```
If the above command results in error /usr/bin/python3: No module named pip. We first need to install pip (PIP is a package manager for Python packages, or modules). And then install pymongo.

```bash
1 curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
2 python3 get-pip.py
3 python3 get-pip.py
```

The below command installs the Python mongodb driver.

```bash
python3 -m pip install pymongo
```

## Start the server

```bash
start_mongo
```

## Execute the files with below

```bash
python3 filename.py
```
