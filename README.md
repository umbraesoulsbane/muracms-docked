# Dockerized project for MuraCMS
### muracms-docked

This is a skeleton project for developing with MuraCMS (https://www.getmura.com/). Based off of https://github.com/blueriver/docker-muracms. 

**Note:** This application has not been hardened or vulnerability tested and is not intended for production use.

## Folder Structure
**/secrets**
- Centralized place for passwords.

**/srv**
- Custom configs for MuraCMS and Lucee Logs. Sets password for Lucee Admin to csxcsx for developer access if needed.
- Contains Dockerfile for copying Lucee/Tomcat configuration files.

**/www**
- Web Root
- Mura Custom files and themes
