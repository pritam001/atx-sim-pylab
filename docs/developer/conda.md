# Conda documentation

### 1. Install Pip
https://www.shellhacks.com/python-install-pip-mac-ubuntu-centos/
### 2. Install Anaconda
##### Linux
`wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh`

`bash ./Miniconda3-latest-Linux-x86_64.sh`

##### MacOS
`brew cask install anaconda`

`export PATH="/usr/local/anaconda3/bin:$PATH"`

##### Create conda virtual env
`conda create -n atx-sim-pylab python=3.8`

```
#
# To activate this environment, use
#
#     $ conda activate atx-sim-pylab
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```

##### Run conda virtual env
`conda activate atx-sim-pylab`


