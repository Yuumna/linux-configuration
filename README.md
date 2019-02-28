# Linux Server Configuration Project


### info 
- IP : 188.166.163.58
- ssh port : 2200
- PAGE : http://188.166.163.58.xip.io/

### SUMMRY
- created `grader` user 
- added `grader` to the sudoers file 
- configured ngnix server to run from port 80 
- created a service for my app `itemcat`
- updated packeges 
- installed `flask` , `sqlalchemy`, .. etc
- you can access the server by typing `ssh grader@188.166.163.58 -p 2200  -i ~/.ssh/id_rsa`

### refrences
[sudo access](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux_OpenStack_Platform/2/html/Getting_Started_Guide/ch02s03.html)\
[How to deploy a flask application](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uswgi-and-nginx-on-ubuntu-18-04)
[nginx docs](http://nginx.org/en/docs/)
