Project Documentation: LUCSS Website
====================================

**Description:** The main entry point for lucss.ca. Contains a wealth of information.
**Project Folder:** /var/www/LUCSSWebsite
**[Github Repo](https://github.com/LakeheadUComputerScienceSociety/LUCSSWebsite)**

**Pulling From Git**
`git pull origin master`

**Building Site**
`sudo mkdocs build`
This does *not* require you to be a sudoer or have any actual root access. The script is set to not require a password to run as root and the script and it's dependencies cannot be changed for security

**Full Loop For Updating**
`cd /var/www/LUCSSWebsite`
`git pull origin master`
`sudo mkdocs build`


