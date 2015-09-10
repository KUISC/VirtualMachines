# Instructions
After launching VM with VMware login as one of the two users.
- built by: Adam Mertz
- contact: adammertz at gmail com

## OS info
Version : Ubuntu Server 14.04.3

| **user** | **password** |
|----------|--------------|
| root     | jayhawks     |
| guy      | basketball   |

## MySQL
Version : 5.5.44

| **user**      | **password** |
|---------------|--------------|
| root          | jayhawks     |
| wordpressuser | pass         |

To login run
```bash
$ mysql -u USERNAME -p
```
It will then prompt you for a password

## WordPress
Version : 3.2

| **user** | **password** |
|----------|--------------|
| admin    | admin        |

Get you VMs IP address via
```bash
$ ifconfig
```
and you will likely see
```bash
inet addr:192.168.0.10
```
Open up your browser and navigate to this IP and verify WordPress site is running.
