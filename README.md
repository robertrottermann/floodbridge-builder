# floodbridge-builder (fbb)
a tool set to build flectra and odoo sites

## Features

flood-bridge-builder or fbb for short bases on a set of tools that I (robert rottermann) built during the last two years.  
I created them to reflect the environment we where using to create plone sites at the time when we started using odoo. 
This odoo only base version, called odoo-instances can be found [here](https://gitlab.redcor.ch/open-source/odoo_instances/tree/master)

fbb allows to create and manage all aspects of a site both locally and remotely.  
The idea is to mantain a list of site descriptions which can be used to recreate a site with all relevant base data, modules serversettings and such. Each server description controlls
- Information about the site owner (main company)
- Branches
- mail servers
- users and their mail settings
- apache or nginx settings
- certificates
- docker container
- ..

* locally:
    - define sites descriptins used to create sites with all
    - create locally running developement sites using an
      identical setup like the life server
- remotely:
    - maintain docker containers
    - maintain backups
    - maintain nginx or apache
    - maintain email accounts

## [Structure](install/INSTALL.md)
### Installation
### The site description file
### Local commands
### Remote commands
### Docker handling
### Support commands


