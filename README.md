etherpad-docker
===============

This is a Docker image which is nothing more than the basic test Etherpad setup as described on https://github.com/ether/etherpad-lite that runs on the Raspberry Pi.

It's not (currently) on the docker hub, so you'll have to build it yourself with:

`git clone git://github.com/ether/etherpad-docker.git && cd etherpad-docker`

Then edit the settings.json to your liking and run:

`docker build -t <YOUR_USERNAME>/etherpad-docker .`

To run Etherpad on port 80, run:

`docker run -d -p 80:9001 <YOUR_USERNAME>/etherpad-docker`

