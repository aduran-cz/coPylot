# Widgets
_Widgets_ is a UI software, providing  paramater input and control for the Pisces lightsheet microscope.

The UI is started up by running **widgets/PiscesInputParameterWidget.py**. It depends on PyQt5 and Python 3.7, which can be installed using the requiremets.txt file in a Python 3.7 Conda  environment. 

## Prerequisites
Install Anaconda: https://www.anaconda.com/distribution/

## Installation

### Clone Widgets Repository
```
git clone https://github.com/royerlab/widgets.git
```

### Create Conda Environment and Install Dependencies
```
conda create -n widgets python=3.7
conda activate widgets
pip install -r requirements.txt
```