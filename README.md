# s6-rc services

My s6-rc services targeted for using with Artix Linux + s6-init
 
## Services
 
 Currently, there are three services in the repository
 
 1. mbpfan : This service is a port of systemd mbpfan service in mbpfan package.
 2. mac-suspend-fix : This service is a fix for the instant wake-up problem after Macbook suspended.
 3. mongodb : This service is a port of systemd mongodb service from Arch linux's AUR.
 
## Installation
 
 1. Copy desired services to /etc/s6/sv
 2. Update service database with the command below.

```sh
sudo /usr/share/libalpm/scripts/s6-rc-db-update-hook
```
