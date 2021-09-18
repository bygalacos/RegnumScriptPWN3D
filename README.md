# RegnumScriptPWN3D

Releasing all files that Regnum Script uses & downloads.

Basicly using this script will compromise your system & data, due to encrypted bash code and you have to login as root to run script. Yeah even your passwd could be changeable ;)

##### NOTE THAT: 

This repository is entire clone of Regnum Script script&file servers. 

You can clone everything except README.md to use script without any connection to Regnum Script servers.
 
#### Redirect sc.regnum.ga to YOURIP or YOURSITE and be sure directory structure is correct with my repo. Put all files at / on webserver.

#### They still changing your hosts file to remove their block but im sure you will find a way (like i do).

ALERT: All files does lot of sensitive info (of yours) transfer with sc.regnum.ga . Redirect them to be %100 safe. 

## Whats going on ??

Simple, they check ur data and geolocate you. Even restrict your IP for no reason.

Log of Regnum Script :

```
curl -s sc.regnum.ga/locked.txt
curl -N -4 -s --head --request GET sc.regnum.ga/locked.txt
grep 200 OK
clear
curl -s -N -4 --data islem=reklamurl&laverip=0.0.0.0 https://sc.masterts3.ga/regnum_post.php
grep reklamgoster
clear
curl -s --head --request GET sc.regnum.ga/surum/v4.1.txt
grep 200 OK
sleep 1
curl -N -4 -s --head --request POST sc.regnum.ga/scdosya/
grep 200 OK
```

# COURTESY OF BYGALACOS


## License
I dont have any, like they dont...
