# Simple web app for  Docker Demo from https://app.pluralsight.com/course-player?clipId=a6546335-a18b-433d-abcb-728b70c288a0

Exposes web server on port `8080` as per `./app.js`

See `Dockerfile` for more details

**The app is maintained approximately once per year so may contain vulnerbilities.**

commands used:<br>
//build the docker image of existing app when inside that repo:<br>
docker image build -t aashwin200/psweb-image .<br>
//  see the build image<br>
docker image ls aashwinbhushal200/aashwin200<br>
//tag it<br>
docker tag aashwin200/psweb-image:latest aashwinbhushal200/aashwin200:myfirstimage9thDec<br>
//push it<br>
Docker push aashwinbhushal200/aashwin200:myfirstimage9thDec<br>
