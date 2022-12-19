# Sample Http with react

## Run server with no cache

This allows to modify the loaded script and get immediately update by refreshing the page. Otherwise you need to force
js script reload by entering it's full path url and hit refresh, for example http://127.0.0.1:8080/mui-react-room.production.min.js F5

`http-server -c-1`

For https:

`http-server -c-1 --ssl -C /home/kmoyse/private/selfsigned.crt -K /home/kmoyse/private/selfsigned.key`