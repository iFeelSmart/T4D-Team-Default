# Tools4Dev Team - Default

## Presentation

This repository is a part of Tools4Dev environnement. In fact, it migh be the most important for all you will implement in your Tools4Dev Setup. 
This repository is a template. you need to duplicate this repository in a private git server because this is where you will be able to add all your custom functions depending on your servers, ci, url, devices, users etc. 

## Manifest

It will containt a very important file called manifest.xml. Which is an index about what are repositories that Tools4Dev will need to work properly in your own environment. 
For Example during Tools4Dev setup if you do not specify any custom manifest.xml file it will use Team-Default manifest's file and clone all "Default" and opensource repositories that will be important as Tools4Dev Default configuration. 

But if you already are in a company that own a custom and private manifest.xml you will be able to declare it during Tools4Dev installation and installation script will clone all your custom/private repositories instead ! 