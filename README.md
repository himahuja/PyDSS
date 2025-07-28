# Welcome to the pydss Repository fork!

I use the following installation instructions

## Installation
Recommendation: Install PyDSS in an Anaconda virtual environment. Specific dependent packages like shapely will only install successfully on Windows with conda.

Here is an example conda command:

`$ conda create -n pydss python=3.9`

Install shapely with conda. pip, particularly on Windows, often fails to install its dependent libraries.

`$ conda install shapely`

Install the latest supported PyDSS version with this command:

`$ pip install nrel-pydss`

Alternatively, to get the lastest code from the master branch:

```
$ git clone https://github.com/NREL/PyDSS
$ pip install -e PyDSS
```

Confirm the installation with this command. It should print the available commands:

`$ pydss --help`

**PyDSS** is a high level python interface for **OpenDSS** and provides the following functionalities

Documentation on installation, setup and examples can be found here https://nrel.github.io/PyDSS/index.html

