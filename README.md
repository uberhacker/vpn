# vpn
Simple bash shell script to start|stop a vpn session

# Installation:
```
$ git clone https://github.com/uberhacker/vpn.git
$ cd vpn
Use your favorite editor (eg. nano, vim, etc.) to edit vpn and add the following:
USER=[enter your user here]
PASS=[enter your password here]
AUTHGROUP=[enter your authentication group here]
URL=[enter your vpn server url here]
Save and exit.
$ chmod +x vpn
$ sudo cp vpn /usr/local/bin/ (or any directory defined in $PATH)
```
# Usage:
```
$ vpn start|stop
```
