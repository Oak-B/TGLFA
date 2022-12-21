# TGLFA
This is the supplementary file and PyTorch implementation for the paper entitled “Two-Stream Graph Convolutional Network-Incorporated Latent Feature Analysis”.

## TGLFA-Supplementary File
Additional tables and figures are put into this file and cited by the paper.

## TGLFA-Codes
This is the PyTorch implementation for the paper entitled "Two-Stream Graph Convolutional Network- Incorporated Latent Feature Analysis".

### Enviroment Requirement
We implement all the experiments in Python 3.7, except that the compressed sparse matrix parallel program is written with CUDA C and compiled with CUDA 11.1. All empirical tests are uniformly deployed on a server with a 2.4-GHz Intel Xeon 4214R CPU, four NVIDIA RTX 3090 GPUs, and 128-GB RAM.

`pip install -r requirements.txt`

### Dataset
Two real [QoS data collected by the WS-Dream system](https://wsdream.github.io/dataset/wsdream_dataset1.html) are applied in our experiments, which are the largest publicly-available QoS datasets and widely adopted in prior studies. 

### Run
Please tune the hyper parameters in `run.py` and run it.

### Others
Please see more information in the manuscript.
