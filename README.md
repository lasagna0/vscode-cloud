# vscode-cloud
Dump to load vscode server in AWS Linux 


Hello there! With this repo, you will have a easy guide of how to setup a vscode server.

This repo contains installation of the following extensions and configs:

* Python 

* R 

* Rmarkdown

* Github extension

All you need is to set a docker environment following the next steps...


Update the apt-get and install docker, python, radian, git and R
```
sudo yum update
sudo yum install docker.io 
sudo yum install git
```
Download all files needed to install vscode-server from this repo. Creds to @gitpod-io for Docker files
```
git clone "https://github.com/lasagna0/vscode-cloud.git"
```

Then run your instance of with the following code, this should be avaliable in `your-ip:3000'
```
cd vscode-cloud
chmod +x ./run.sh
screen -L ./run.sh
```
Change

Then inside vscode instance, run
```
pip3 install -U radian
sudo yum R4
```
Then inside R console
```
install.packages("languageserver")
install.packages("httpgd")
install.packages("rmarkdown")

```

And done!
