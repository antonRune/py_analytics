#python analytics

To install the required modules - enter in terminal
```commandline
pip install -r requirements.txt
```

To run jupyter notebook - enter in terminal:
```commandline
jupyter notebook
```
---
## alternative

install anaconda on your computer and create a new environment
```commandline
conda create --name env_name python=3
```
activate your environment
```commandline
conda activate env_name
```
now you ready to work

---
#conda commands
deactivation environment
```commandline
conda deactivate
```

environments list
```commandline
conda info --envs
```

install packages in environment
```commandline
conda install --name env_name package_name
```

update conda
```commandline
conda update -n base -c defaults conda
```