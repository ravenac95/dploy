dploy
=====

Dploy both server (dcontrol) and client is an attempt to create a better
deployment system for python web applications. The entire project will be
Open Source. The idea is to get something along the lines of an open source 
PaaS, it's just up to you to make it more or less automated.

Planned Usage (Work-in-progress)
--------------------------------

dploy's commands are inspired by the usage found in git. dploy can be 
configured for any number of remote zones. So you can deploy your code to 
different remote zones. The purpose of this is so that you can deploy your
code to different environments like testing/staging/production.

At the moment, dploy is dependent on git. It doesn't have to be your main vcs,
but at the moment it greatly simplifies the workflow and allows dploy's 
server, dcontrol to track the changes in your software. 
