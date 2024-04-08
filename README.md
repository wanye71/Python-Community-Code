# Python Community Code
1. git remote add (remote repo)
2. git fetch
3. git pull origin main (remote branch)

# Table of Contents
## Installing pip
1. [Install pip](#install-pip)
2. [Upgrade pip](#upgrade-pip)
## Install system packages
3. [Install ptpython](#install-ptpython)
## Virtual Environments
4. [Create Virtual Environments](#create-virtual-environments)

### Install pip
```console
py -m ensurepip --upgrade
```

### Upgrade pip
```console
pip install --upgrade pip
```

### Install Repls
#### PtPython
```console
pip install ptpython
```
#### Bpython
```console
pip install bpython
```

## Create Virtual Environments
### With venv
```console
python -m venv example_venv
```
***Turn virtual environment on Windows***
```console
source /Scripts/activate
```
***Turn virtual environment on Linux***
```console
source /bin/activate
```

1. python3 -m ptpython
2. pip3 install -r requirements.txt
3. which ptpython
4. source env/bin/activate