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

![](/resources/figures/install.png)

## Install requirements
```
(venv) $ pip install numpy
```

## Working on github
1. (To check git status)
```
(venv) $ git status
```

2. Add all files (except `venv` folder) from `working directory` to `staging area`:
```
(venv) $ git add --all -- . ':!venv/*'
```
3. Commit files in `staging` to `localrepo`:
```
(venv) $ git commit -m 'comment somthing'
```
4. If you do any change in github, e.g. delete, add a file/folder, remember to push the github repo:
```
(venv) $ git pull
```
5. Push changes to the github repo:
```
(venv) $ git push
```