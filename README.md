# daa_philly_2015
Materials for the DAA Philly Symposium 2015 talk "Analyzing the Philadelphia Data Science Scene with Python"

To view this material online in non-interative mode, see [here](http://nbviewer.ipython.org/github/mdbecker/daa_philly_2015/blob/master/DataPhilly_Analysis.ipynb).

## Setup instructions
To run this interactively you'll need Python installed with a bunch of packages. The easiest way to install these packages is to use the Anaconda Python distribution.

### Install Anaconda
Download and install [anaconda](http://docs.continuum.io/anaconda/install)

### Create environment
From the commandline run the following:

#### Linux/OS X
```bash
conda create -y -n daa_demo python=2.7 pip notebook pandas requests scikit-learn matplotlib seaborn
source activate daa_demo
jupyter notebook
```

#### Windows
```bash
conda create -y -n daa_demo python=2.7 pip notebook pandas requests scikit-learn matplotlib seaborn
activate daa_demo
jupyter notebook
```

### Using the notebook
At this point you should have a browser window open with jupyter notebook running. If you started jupyter in the directory with ``DataPhilly_Analysis.ipynb``, you should see it in the main menu and be able to click on it.

## Troubleshooting

* For help with anaconda see the docs [here](http://conda.pydata.org/docs/using/using.html).
* For help with using Jupyter Notebook see the docs [here](https://jupyter.readthedocs.org/en/latest/install.html).
