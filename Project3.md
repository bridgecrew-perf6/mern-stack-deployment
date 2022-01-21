# Project 3

**Backend Configuration**
___

updating ubuntu

` $ sudo apt update`

![](images/updateubuntu1.png)

upgrading ubuntu

` $ sudo apt upgrade`

![](images/ubuntuupgrade2.png)

getting nodejs location from ubuntu repositories

` $ curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`

![](images/nodejslocation3.png)

installing nodejs & npm on the server

` $ sudo apt-get install -y nodejs`

verifying node installation

` $ node -v`

verifying npm installation

` $ npm -v`

![](images/installnverify4.png)

application code setup

creating a new directory for the todo project

` $ mkdir Todo`

verifying todo directory

` $ ls`

changing directory to newly created one

` $ cd Todo`

![](images/nwdirnchdir5.png)

initializing project so package.json will be created

` $ npm init`

![](images/npminit6.png)

confirmation

![](images/confirmation7.png)

installing expressjs

` $ npm install express`

creating index.js file

` $ touch index.js`

installing dotenv module

` $ npm install dotenv`

opening index.js file 

` $ vim index.js`

![](images/express2vim8.png)

inside index.js

![](images/barebones9.png)

testing to see if server works - it should work on port 5000

` $ node index.js`

![](images/nodeconf10.png)

