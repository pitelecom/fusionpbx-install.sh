
FusionPBX Install
--------------------------------------
A quick install guide & scripts for installing FusionPBX. It is recommended to start with a minimal install of the operating system. Notes on further tweaking your configuration are at end of the file.


### CentOS
CentOS operating system is a requirement for some companies. Don't expect video mixing to work. It will likely be a year or more for video mixing dependencies to be updated enough to work in CentOS.

```sh
git clone https://github.com/pitelecom/fusionpbx-install.sh.git
cd ./fusionpbx-install.sh/centos && ./install.sh
```


## Security Considerations
Fail2ban is installed and pre-configured for all operating systems this repository works on besides Windows, but the default settings may not be ideal depending on your needs. Please take a look at the jail file (/etc/fail2ban/jail.local on Debian/Devuan) to configure it to suit your application and security model!


