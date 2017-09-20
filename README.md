# challenge
Technical Challenge - Automate the installation and configuration of a nginx web server using the automation toolkit of your choice (puppet, chef , salt , ansible)
# Requirements
The nginx server should:
a) serve requests over port 8000
b) create a web page with content defined  by a template format. 
c) Please explicitly state all assumptions (e.g. Only runs on RHEL6)

# Success
Your solution should:
i) ensure that the required configuration is completed reliably when all the steps are completed
ii) ensure that subsequent applications of the solution do not cause failures or repeat redundant configuration tasks

Please perform this exercise on one of the following operating systems, CentOS, Ubuntu(16.04, 17.04). 
You can complete this exercise using your choice of automation tool or language.

# Assumptions
1.  Your deployment machine has python version 2.7+ and ansible version > 2.3 installed.
  1. The server to host is Ubuntu version 16.04 and has python version 2.7+ installed.
2. You already have access to the server via ssh with root or sudoer rights. with root or sudoer rights.

# Setup
Clone this project to your local that will be used to deploy to via Ansible
```
git clone git@github.com:kosmoit/challenge.git
``` 
