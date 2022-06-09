### Notes on Command Lines

#### Device

Show info of device
```
uname -a
```

Show ubuntu version
```
lsb_release -a
```
#### python
Show python version
```
python –version
```
or
```
python3 –version
```

#### pip
Show all python package
```
pip list
```

Show specific python package
```
pip show <packageName>
```
or
```
pip list | grep <packageName>
```
or
```
pip list | findstr "<packageName>"
```

#### Anaconda
Update Anaconda
```
conda update conda
```
Show a list of all installed packages using conda
```
conda list
```
Show conda environment
```
echo $CONDA_DEFAULT_ENV 
```
Show conda environment enformation
```
conda info
```
