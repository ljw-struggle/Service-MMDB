# Python API Package of Single-cell Multi-omics DataBase

## Introduction

pymmdb is a python package that provides the interface to access the data in [MMDB](https://mmdb.piaqia.com).

## Installation

```shell
# 1.Clone the source code from github
$ git clone https://github.com/ljw-struggle/pymmdb.git
$ cd pymmdb

# 2. Create a conda environment and activate it.
conda env create -n pymmdb --file env.yml
conda activate pymmdb

# 3. Install pymmdb as a dependency or third-party package with pip.
python setup.py install # or python setup.py develop or pip install -e .
```

## Usage

```python
import pymmdb
mmdb = pymmdb.MMDB() # Create a MMDB object
dataset_list = mmdb.list_dataset() # Get the list of datasets
adataset = mmdb.load_dataset('Dataset1') # Load a specific dataset
```

Please refer to [📘Documentation and Tutorials](https://pymmdb.readthedocs.io/en/latest/) for more details.

## Cite

XXXXX, XXXXX, XXXXX, XXXXX, XXXXX, XXXXX, XXXXX, XXXXX, MMDB: a comprehensive resource and knowledgebase for multi-omics data at the single-cell resolution, XXXXXXX, 2024
