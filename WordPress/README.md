# Instructions
After launching VM with VMware login as one of the two users via ssh.

```bash
$ ssh USER@IPADDRESS
```
type yes when prompted to downoad RSA key.

## OS info

For Windows users download the ISO directly with link below and place it in the directory this README is in. OSX and Linux users can use the following commands from the directory.

```bash
# Mac OSX
$ curl http://mirror.pnl.gov/releases/14.04.3/ubuntu-14.04.3-desktop-amd64.iso
# Linux
$ wget http://mirror.pnl.gov/releases/14.04.3/ubuntu-14.04.3-desktop-amd64.iso
```

| Notes           |                          |
|-----------------|--------------------------|
| OS              | Ubuntu Server            |
| Version         | 14.04.3                  |
| ISO             | http://1.usa.gov/1KFFlLC |

### Logins

| **user** | **password** |
|----------|--------------|
| root     | jayhawks     |
| guy      | basketball   |

## MySQL
| Notes           |                       |
|-----------------|-----------------------|
| Version         | 5.5.44                |
| Vulnerabilities | http://bit.ly/1KFCNxb |
*could not find vulns for 5.5.44 so picked next highest version number*
### Logins

| **user**      | **password** |
|---------------|--------------|
| root          | pass         |
| wordpressuser | pass         |

To login run
```bash
$ mysql -u USERNAME -p
```
It will then prompt you for password input

## WordPress

| Notes           |                       |
|-----------------|-----------------------|
| Version         | 3.9                   |
| Vulnerabilities | http://bit.ly/1KFCnqB |

### Logins

| **user** | **password** |
|----------|--------------|
| admin    | pass         |

Get you VMs IP address via
```bash
$ ifconfig
```
and you will likely see
```bash
inet addr:192.168.0.10
```
Open up your browser and navigate to this IP and verify WordPress site is running. You can login from the homepage or go to http://IPADDRESS/wp-admin to access the admin panel


## Build Notes
- built by: Adam Mertz
- contact: adammertz at gmail com
