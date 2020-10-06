# YGroup-Challenge

## Requirements

Download a recent version of Python3 from https://www.python.org/download/releases/3.0/

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the libraries.

Once you have installed Python3 and pip,clone this project with 
```console
git clone https://github.com/AlejandroBuenoPrieto/YGroup-Challenge
```

Then you can use pip to install the requirements:
```console
cd YGroup-Challenge/
pip install -r requirements.txt
```

Obtain the dataset:
- Download all files from https://www.kaggle.com/aubertsigouin/biximtl
- Unzip the downloaded file
- Place files in YGroup-Challenge/Data

## Usage

In order to enable widgets in the notebook:
```console
jupyter nbextension enable --py widgetsnbextension
```

Finally, run the notebook with:
```console
jupyter notebook
```