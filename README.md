# Mail-Sender
A python script which can send mails

## Requirements

`python3` - Installed on most modern linux distributions
If not Installed, can be installed using:
``` shell
# Debian, Ubuntu or other Debian based distros
sudo apt-get install python3
# Arch Linux
pacman -Syu python3
# Red-Hat based distributions
rpm install python3
```

`smtplib for python` - Google is your friend

## Usage
From terminal, give the script execution access by:

``` shell
chmod +x send
```

Now, the script can be run by :

``` shell
./send
```

Most of the options have proper documentation.
The from field can be filled as:

`Yash Srivastav<yashsriv@iitk.ac.in>`

to provide both name and email id for people to reply to you.

### Note
Currently, there is a bug in IIT Kanpur servers which allows
you to set any value for that field and it will be accepted.
