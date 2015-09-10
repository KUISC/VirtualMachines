# This repo contains directions for VMs created for practice

## Note to Windows Users
If you are on a Windows machine that is fine all the client boxes at competitions are Windows outside of one or two. Tragically your only solution is to use PuTTY. There are very few commands you will need to execute on your local machine anyway. Once connected to a remote box we will be using Unix based commands. Also Windows server management is often done via Remote Desktop so you will be in a familiar environment. The [following is a quick tutorial](https://mediatemple.net/community/products/dv/204404604/using-ssh-in-putty-) on how to SSH into a remote server with PuTTY. Also you will need to download [7zip](http://www.7-zip.org/) to extract the tarball.

## 1. Download and Install VMWare
Virtual Machines can be used on either VMWare Fusion (Mac) or Workstation (Windows). They can be downloaded for free by logging into your EECS account [here](http://www.eecs.ku.edu/current_students). Then clicking on the `Downloads` link on the left has side. From there you click `VMWare` which takes you to an online store where you can download the software.

## 2. Clone the repo and download tarball into it
Clone repo to your local machine using
```bash
$ git clone https://github.com/KUInfoSecClub/VirtualMachines.git
```

We will host a temporary web server so you can download the tarball containing the machine. If you are a Windows user you will need to save the file into the appropriate directory. Unix based systems can just run the command noted below.

#### Web Server
To host a temporary web server run the following command from the directory you wish to share.
```bash
# Python 2
$ python -m SimpleHTTPServer

# Python 3
$ python3 -m http.server
```

#### Unix
```bash
$ tar -zxvf TARBALLNAME.tar.gz
```
