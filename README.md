# GENTRL-SOMs
Training GENTRL model with self-organizing map.

# Installation
Install rdkit with conda.
```
conda create -c rdkit -n my-rdkit-env rdkit
```
Then activate the new environment.
```
conda activate my-rdkit-env
```
Install GENTRL and MOSES.
```
git clone https://github.com/icyray/GENTRL.git
git clone https://github.com/molecularsets/moses.git
cd GENTRL && python setup.py install && cd .. 
cd moses && python setup.py install && cd ..
```
Install [susi](https://github.com/felixriese/susi) to train SOMs.
```
pip install susi
```

# How to use
Run notebook in the following order: 
**Train_SOM ➡️ GENTRL_with_SOM ➡️ Sampling ➡️ Benchmarking**

# Credits
[neelr/LeishNN](https://github.com/neelr/LeishNN)  
[sebastiandro/gentrl-benchmark](https://github.com/sebastiandro/gentrl-benchmark)
