# Virtual Envrionment in Python

In python, virtual envrionments provides a way to isolate packages from the global Python environment. It really helps in maintaining different python versions for different projects. 

There are few ways how we can create virtual envrionment in Python:


## Using `python` command

```
python -m venv [venv_name]

// To activate the virtual envrionment
source [venv_name]/bin/activate OR . [venv_name]/bin/activate


// To diactivate the virtual envrionment
deactivate
```

## using `conda` (anacoda) command

```
conda create -p [venv_name] python==[python_version]

// To activate the virtual envrionment
conda activate [venv_name]/


// To diactivate the virtual envrionment
conda deactivate
```