# vscode-cloud
Dump to load vscode server in Ubuntu Azure Server


Hello there! With this repo, you can upload all necessary files to activate a vscode server with simple steps. 

This repo contains the following extensions and configs:

* Python 

* R 

* Rmarkdown

* Github extension

All you need is to set a docker environment following the next steps...


Update the apt-get and install docker, python, radian, git and R
```
sudo apt-get update
sudo apt install docker.io 
sudo apt install git
```
Download all files needed to install vscode-server from this repo. Creds to @gitpod-io for Docker files
```

```



sudo apt install python3-pip
pip3 install -U radian
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
sudo add-apt-repository 'deb https://cloud.r-project.org/bin/linux/ubuntu focal-cran40/'
sudo apt-get update
sudo apt-get install r-base
Install in R, languageserver. This must be installed in order to use R in vscode
```
R 
install.packages("languageserver")
install.packages("httpgd")
```

Download all files needed to install vscode-server from this repo. Creds to @gitpod-io for Docker files


