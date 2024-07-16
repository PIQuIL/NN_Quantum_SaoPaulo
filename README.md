# Neural networks in quantum many-body physics

![banner](imgs/banner.jpg "banner")

Professors. J. F. Carrasquilla and R. G. Melko

Tutorials to accompany the lectures.

This repository contains the notebooks accompanying the paper: [arxiv:2101.11099](https://arxiv.org/abs/2101.11099).


Run the following command to install the correct versions of all necessary packages:
```
pip install numpy matplotlib "tensorflow>=2.0,<3.0" "torch>=1.2,<2.1" qucumber
```

If you prefer, it is possible to use a virtual environment to run the tutorials. 

Instructions for running the code (one option)

Assuming a python installtion, create a virtual environment: 
```
python -m venv ~/SP
```
Activate the environment: 
```
source ~/SP/bin/activate
```
Install the necessary packages to run the code: 
```
pip install numpy matplotlib "tensorflow>=2.0,<3.0" "torch>=1.2,<2.1" qucumber  
pip install jupyterlab 
```
Clone the repository
```
git clone https://github.com/PIQuIL/NN_Quantum_SaoPaulo.git
```
Run jupyter lab
```
jupyter lab 
```
open the tutorials from your browser/jupyter

1_Supervised_Rydberg.ipynb 2_QST_Rydberg.ipynb        3_VMC_Rydberg.ipynb

