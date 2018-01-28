How To:
-----
add this entry to your hosts files: `127.0.0.1 wordpress.local.com ghost.local.com`

to start use: `docker-compose up -d`

access via web browser:

http://wordpress.local.com <br>
http://ghost.local.com


Notes:
----
Commaned used to create self-signed certificate:
```
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout selfsigned.key -out selfsigned.crt
```
