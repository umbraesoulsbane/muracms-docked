# Configuration Files

You may run the following copy commands to copy the files in the container to /home/conf thus making a local copy here that you can customize as needed. These will be copied from the local folder to the container at runtime.

- cp /usr/local/tomcat/conf/catalina.properties /home/conf
- cp /usr/local/tomcat/conf/server.xml /home/conf
- cp /usr/local/tomcat/conf/web.xml /home/conf
- cp /opt/lucee/server/lucee-server/context/lucee-server.xml /home/conf
- cp /opt/lucee/web/lucee-web.xml.cfm /home/conf

Passwords for Lucee Admins are encrypted in the config files. Use the Web UI to update passwords before copying the files locally.
