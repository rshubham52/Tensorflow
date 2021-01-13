# Tensorflow
Instructions on How to install Tensorflow GPU version on Windows

Initially writing for self notes only. But others are also welcome to use this.

First just go through the tensorflow official page, see the others requirements like (Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017 and 2019). 


1) Install Conda. Conda is a package manager. Very efficient to handle all the version dependency stuff.
2) Inside Conda create a virtual environment.
NOTE: mytfvenev is my virtual environment name.
```
conda create --name mytfvenv
```

3) Activate this virtual environment.
```
conda activate mytfvenv
```

4) Installing tensorflow for GPU and CPU
```
conda install -c anaconda tensorflow-gpu
```
