# DataClass

##### 1. Install Python Virtual Environments:

```
conda create -n PythonData python=3.7 anaconda -y
pip install ipykernel
conda install nb_conda_kernels -y
```

##### 2. Python library gmaps

```
conda install -c conda-forge gmaps -y
OR
jupyter nbextension enable --py --sys-prefix widgetsnbextension
pip install gmaps
jupyter nbextension enable --py --sys-prefix gmaps
```

##### 3. SQLite database using SQLAlchemy

```
pip install sqlalchemy
```

Check that you have SQLite installed
In your terminal/Git Bash, run: sqlite3 --version
If sqlite is NOT installed, run: conda install -c anaconda sqlite

