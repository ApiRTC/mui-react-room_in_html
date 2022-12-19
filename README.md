# Sample Http page with MaterialUI/ApiRTC/React Room integration

## Development guidelines

Clone this repo with --recurse-submodules:

`git clone --recurse-submodules git@github.com:ApiRTC/mui-react-room_in_html.git`

Then (Note that npm run build requires sudo access to npm link submodules):

```
cd mui-react-room_in_html
npm run install
npm run build
```

Finally run:

`npm run start`

## Run server with no cache details

This allows to modify the loaded script and get immediately update by refreshing the page. Otherwise you need to force
js script reload by entering it's full path url and hit refresh, for example http://127.0.0.1:8080/mui-react-room.production.min.js F5

`http-server -c-1`

For https:

`http-server -c-1 --ssl -C ./certs/selfsigned.crt -K ./certs/selfsigned.key`