# Configuration Files

You may run the following commands to copy the files from the container to /home/conf thus making a local copy there that you can customize as needed. The Dockerfile will run commands to copy these custom files (if they exist) from this local folder to the proper locations in the container at runtime.

- cp /usr/local/tomcat/conf/catalina.properties /home/conf
- cp /usr/local/tomcat/conf/server.xml /home/conf
- cp /usr/local/tomcat/conf/web.xml /home/conf
- cp /opt/lucee/server/lucee-server/context/lucee-server.xml /home/conf
- cp /opt/lucee/web/lucee-web.xml.cfm /home/conf

Passwords for Lucee Admins are encrypted in the config files. It is recommended to use the Lucee Web UI to update passwords before copying the files locally.
