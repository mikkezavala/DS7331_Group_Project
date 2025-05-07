# DS7331 Project: Phishing Dataset
This repository contains a dataset related to phishing detection. The dataset is used for machine learning models to classify phishing websites based on different features.

## Group Members
  - Hayoung Cheon
  - Steven Cox
  - Erika Dupond
  - Miguel Zavala

## Dataset

The dataset used in this project is available at the following link:

[Phishing Dataset (CSV)](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset))

## Google Colab Notebook

To run the project and see the results in an interactive environment, you can open the notebook in Google Colab:

[Open the Colab Notebook](https://colab.research.google.com/drive/19aZeZbDxK7XpHXjkaB4My-tdJ-PJg97M?usp=sharing)


### Optional Configuration

Use Poetry to manage dependencies and virtual environments. I recommend [pyenv](https://github.com/pyenv/pyenv)

This will be useful during any python dev. this is mostly once, if you have Poetry and Pyenv you can skip all up to install dependencies

#### Pre-requisites

##### Install PyEnv

Follow guide above in case not mac.

```shell
$brew install pyenv
```

##### Download and install [pipx](https://pipx.pypa.io/stable/installation/)

There is also similar steps in the link for Windows and Linux

```shell
$brew install pipx
$pipx ensurepath
```

##### Install [Poetry](https://python-poetry.org/docs/)
```shell
$pipx install poetry
```
##### Install a python version (.toml) file has a required version

This will install the virtualenv and the python dependencies.


```shell
$poetry install
```
 