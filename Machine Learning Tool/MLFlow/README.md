#  Install MLFlow with UI 
## Requirement 
* Anaconda ENV **OR** 
* Miniconda ENV **OR**
* Python ENV  
* Ubuntu 22.04
### I Use Miniconda for install MLFlow on Ubuntu 22.04

## Quick command line install
#
    sudo apt update 
# 
    wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh 
# 
    bash ~/miniconda3/miniconda.sh 
# 
    rm -rf Miniconda3-latest-Linux-x86_64.sh 

#### suppose conda base not open or conda command not work use below command 
# 
    bash 

## Create conda environment 
#
    conda create -n mlflow python=3.11 -y 
# 
    conda activate mlflow 
### Install MLFlow using pip command 
#
    pip install mlflow 
#### Now access mlflow ui for anywhere 
#
    mlflow ui --host 0.0.0.0 
#### you can mention your own port 
#
    mlflow ui --host 0.0.0.0 --port 5000
#### 5000 is a default port for mlflow 
#                   Thank You 
