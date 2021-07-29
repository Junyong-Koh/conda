# conda

## Basic

### check version

```
conda --version
```

### update

```
conda update conda
```

### make virtual environment

```
conda create --name(-n) environment_name package_name
```

### check virual environment list

```
conda info --envs
```

### activate & deavtivate environment

activate

window
```
activate environment_name
```

mac
```
conda activate environment_name
```

deactivate

window
```
deactivate environment_name
```

mac
```
conda deactivate environment_name
```

### install package

```
conda install package_name
```

### check package list

```
conda list
```

### remove environment

at base
```
conda remove --name(-n) environment_name --all(-a)
```

### remove cache

```
conda clean --all(-a)
```

