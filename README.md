# Curl-error-snap
This repo is for solving the problem: curl: (23) Failure writing output to destination

Cause:
Due to conflit between the snap and apt in Unix based system for me .

Solution:
removing the snap version curl
and using the apt version.

cmds:

sudo snap remove curl 

sudo apt-get install curl





