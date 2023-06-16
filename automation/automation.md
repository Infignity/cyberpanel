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

## Install dependencies

```commandline
yum install -y curl
yum install -y git
```

## Clone our custom cyberpanel git repo
```commandline
git clone https://github.com/Infignity/cyberpanel.git
```

## Execute cyberpanel.sh file
```commandline
cd cyberpanel/
sh ./cyberpanel.sh
```
