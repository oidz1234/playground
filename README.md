# playground
this is the repo for Mark and Chas provisioning script

soon to install docker 


TODO:

Maybe seperate the scripts

Use a curses based menu system so you can pick and chose what you want 
- this is done, need to find out where to actually put the scripts
- then we need to make sure that all the if statments and varibales are changed
  to accept arguments from the dialog



Some way to change the user when installing the authenticator to the user that
was created during earlier part of the script


Can this do auto provision of linux kernel 

Debugging:

docker run -i -t ubuntu /bin/bash
apt-get update -y && apt-get install curl dialog -y


docker run -i -t centos /bin/bash

