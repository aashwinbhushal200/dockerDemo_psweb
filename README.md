# Simple web app for  Docker Deep Dive book

Exposes web server on port `8080` as per `./app.js`

See `Dockerfile` for more details



**The app is maintained approximately once per year so may contain vulnerbilities.**
commands used:
//build the docker image of existing app when inside that repo:
docker image build -t nigel/psweb-image .
//  see the build image
 docker image ls nigel/psweb-image
