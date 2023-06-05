# Deploying Web Server with Ansible Jinja Templates

To get the source code for this lab, you can follow the steps below

---
## Install git

Open git scm (you can install it in the linux terminal, or install git on other platforms here [Download](https://git-scm.com/downloads) )

![This is an image](./images/git-bash.png)

Type the command git clone "repository link" to get the source code to your local computer
```
$ git clone https://github.com/zaxrmdn/DeployNginx-JinjaAnsible.git
```

Check if the code is already in local storage

![This is an image](./images/code-exists.png)

---
## Open Resource Lab

Go to the directory code
![This is an image](./images/carbon-(10).png)


The files looks like this below
![This is an image](./images/carbon-(11).png)

Dan coba jalankan playbook seperti berikut untuk mencobanya
```
$ ansible-playbook -i inventory playbook/web-pub.yml
```
