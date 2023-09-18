# psotnic
Basic Psotnic Configuration + IRCNet servers

## HUB:
```
wget https://l.nygus.org/psotnic.tar.gz
tar zxf psotnic.tar.gz
cd psotnic-0.2.14/bin/
echo "yourpassword" | ./psotnic -p
vim conf.bot1
./psotnic -c conf.hub1
./psotnic conf.hub1
rm -f conf.hub1.dec
```

## SLAVE:
```
wget https://l.nygus.org/psotnic.tar.gz
tar zxf psotnic.tar.gz
cd psotnic-0.2.14/bin/
vim conf.slave1
./psotnic -c conf.slave1
./psotnic conf.slave1
rm -f conf.slave1.dec
```
## HUB configuration

> to do

## Linking SLAVE

> to do
