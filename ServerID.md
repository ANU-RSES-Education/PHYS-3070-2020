# Release ID for Jupyterhub

Editing this file triggers a (re)install of the jupyterhub installation.
If the jupyterhub is already installed, it will be refreshed but not forcibly 
upgraded (that needs to be managed from the console). 

There will be errors if the github secrets have not been set up 

 - **IP Address:** 128.199.88.192
 - **Hostname:** https://phys3070.rses.geoscience.education
 - **Release ID:** 0.1.0
 - **Droplet Name:** ubuntu-phys-3070-2020
 
 ## Comments
   
Rebuilt droplet / test the installer workflow 
  - Running Ubuntu 19
  - Use hostname rather than IP in secrets
  - 1Gb memory does not seem to be enough to install and rebuild TLJH - resizing to 2Gb
  
