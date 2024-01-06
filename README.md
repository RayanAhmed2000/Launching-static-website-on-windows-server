# Launching-static-website-on-windows-server
This repo contains steps to launch a website on windows server

# Pre requisites
- launch a windows server
- RDP into the server

# Webserver installation
- Open Server Manager
- Add roles and features
- next
- role based feature installation
- select server from pool
- make sure your server is selected
- next
- Select Webserver IIS
- Add feature
- next -> next -> next and install


# Creating Webpage
- Open This PC
- inetpub
- wwwroot
- delete 2 files IIS and other
- create a new text document and open it
- put the html code
- Save as
- index.html
- All files
- Now hit public IP of server
- Website will be visible
