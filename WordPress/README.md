# Instructions
After launching VM with VMware login as one of the two users via ssh

```bash
$ ssh USER@IPADDRESS
```
type yes when prompted to downoad RSA key

## OS info

| Notes           |                       |
|-----------------|-----------------------|
| OS              | Ubuntu Server         |
| Version         | 14.04.3               |

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
Open up your browser and navigate to this IP and verify WordPress site is running. You can login from the homepage or go to http://IPADDRES/wp-admin to access the admin panel


## Build Notes
- built by: Adam Mertz
- contact: adammertz at gmail com
