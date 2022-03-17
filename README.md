# GWireguard
GUI with Zenity for Wireguard VPN

## Pre Requisites
Tests in POP OS 20.04 and 20.10

Packages Needed: 
- zenity
- git

### Prepare:
```bash
apt install zenity git -y
```

# How to Use
For use you can exec the follow commands:
1. Download the repository:
```bash
git clone git@github.com:nilsonvieira/gwireguard.git
```
2. Enter in directory and perm configure file
```bash
cd gwireguard ; chmod o+x configure
```
3. Exec config file
```bash
./configure
```
4. In the end execute the command:
```bash
gwire
```
> NOTES: \
The desktop icon dont work in gwire version 0.2

