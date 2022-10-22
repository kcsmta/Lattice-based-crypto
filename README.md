# Lattice-based-crypto

We use:
- Ubuntu 18.04 
- Python 3.6 
- Visual Studio Code

## Create a virtual environment for jupyter notebooks
Step 1: Create a virtual enviroment (named vevn)
```
$ python3 -m venv venv 
```
Step 2: Active the virtual enviroment
```
$ source venv/bin/activate 
```
Step 3: From the inside the virtual enviroment, install ipykernel 
```
(venv) $ pip install ipykernel
```

Step 4: Install a new kernel. 
```
(venv) $ ipython kernel install --user --name=Lattice-based-crypto
```
After this step, all ipython files inside folder `Lattice-based-crypto` will take run inside virtual enviroment. Note: chose the virtual environment for jupyter notebooks's kernel by click the icon on the top right corner in Visual Studio code.

![](/resources/figures/install.png)

## Install requirements
```
(venv) $ pip install numpy
```

## Working on github
```
(venv) $ git add --all -- ':!venv'
```