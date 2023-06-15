# cyberpanel-ansible
Scripts to automate setting up cyberpanel

## Switch to root user

```commandline
sudo su -
```

## Update package index in centos
```commandline
yum update
yum upgrade -y
```

## Clone our custom cyberpanel git repo
```commandline
git clone git@github.com:Infignity/cyberpanel.git
```

## Execute install.sh file
```commandline
cd cyberpanel/
sh ./install.sh
```
