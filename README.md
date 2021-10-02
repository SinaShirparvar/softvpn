SoftEther-vpn
=========

Installing Docker with ansible and Running sample container [SoftEtherVPN Container with Ansible (OpenVpn, L2TP, softether)]

Requirements
------------
Support matrix:
-Linux ubuntu 18.04 or 20.04
-Ansible 2.11.4
-Python 3.8
-Virtual Environment (env) to prevent conflicting linux system-site-packages while running ansible playbooks.

Start Running plabooks
---------------------
```
$ git clone https://github.com/SinaShirparvar/softvpn.git
```
Move play.yml to current directory, then runnig softvpn role.
```
$ mv softvpn/play.yml ../
```

```
$ ansilbe-playbook play.yml
```


