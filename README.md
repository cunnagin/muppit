# muppit
GUI Dashboard for mupx Server

Allows users to monitor a mupx server (running multiple meteor apps via mupx/Docker containers) and try's to make some of the mupx command line management achievable through a GUI.

The dashboard is a 'card' summary of currently running apps. Each card has basic information on the web app (it's name, Port number, Docker container ID, etc...) and provides a screenshot of the running app.

* First set up an operation mupx server with Meteor and nginx also installed on the host server
* install this app as a meteor app running on the host
* nginx is used to reverse proxy to the Dockerized web apps ("http(s)//<mupx server hostname>/<web app name>")

