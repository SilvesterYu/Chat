## Notes on Command Lines

### Device

Show info of device
```
uname -a
```

Show ubuntu version
```
lsb_release -a
```
(a note to myself) when the tutorials say use
```
source ~/.bashrc
```
Instead I should use
```
source ~/.zshrc
```
When I use export, it is essentially adding the line into the ~/.zshrc file. I can see it with 
```
nano ~/.zshrc
```

### python
Show python version
```
python –version
```
or
```
python3 –version
```

### pip
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
To automatically generate the requirements.txt (still requires manual checking, does not guarantee 100% correctness)
```
pip install pipreqs
```
```
pipreqs </path/to/project>
```
If you have requirements.txt, to install the requirements
```
pip install -r requirements.txt
```

### Anaconda
[Set up Conda environment on linux](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html
)

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
### General

Print working directory
```
pwd
```
Open the current folder in graphical output
```
xdg-open ./
```

