Project Documentation: LUCSS Website
====================================

 - **Description:** Meteor Degree Auditor Project
 - **Project Folder:** /var/www/auditor
 - **[Github Repo](https://github.com/LakeheadUComputerScienceSociety/degree-auditor)**

**Intro**

The actual repo exists one folder deeper inside /var/www/auditor/degree-auditor. Besides this, the project folder contains two shell scripts, start.sh and stop.sh. Both of these script files will be in the supplementary files folder in this repo. All the start and stop scripts do is start and stop the service that manages the meteor process. This service runs at startup, the config file for this is also in the supplementary files. The start and stop scripts must be ran with sudo, but you not need any root privilages to do so. They are uneditable for security and can be ran with sudo without a password.

**Pulling From Git**

Make sure you are in the degree-auditor folder, not the root project folder and you have stopped the meteor service. 
`git pull origin master`

**Building Site**

The site will build when starting the service

**Full Loop For Updating**

`cd /var/www/auditor`
`sudo ./stop.sh`
`cd /degree-auditor`
`git pull origin master`
`cd ..`
`sudo ./start.sh`