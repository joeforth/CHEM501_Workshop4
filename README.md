# CHEM501_Workshop4
In this workshop, we'll learn how to store and structure data in a database using SQL and SQLite.

As well as two jupyter notebooks containing workshop contents, you'll find an Excel spreadsheet containing a list of compounds that we'll look at during the workshop.

## Setting up your Computer
You'll need to install the following modules to do this workshop:

1. ipython-sql
2. sqlite
3. pandas
4. openpyxl

There are two options to install these:

### Create a conda environment
Run the following in your Terminal / Anaconda Prompt:

```bash
conda create -n chem501_w4
conda activate chem501_w4
conda install python ipython-sql sqlite pandas openpyxl
```

### Install via pip
Clone the git repo to an appropriate directory and run the following:

```bash
cd chem501_w4
pip install requirements.txt
```
