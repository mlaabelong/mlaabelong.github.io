---
layout: page
title: Prelims
permalink: /Prelims/
---

## **Module 1:** Understanding DevOps culture
# **Hands-on Activity 2: Install and configure your repository in remote Git in GitHub**

# **Procedure**

1. Create an account in Github

	Username should be your given initials and last name followed by -tip (e.g. ajcanlas-tip)

	Use your TIP email address for this (if you already linked your email with GitHub create a seperate one)

	Verify your account in your email in GitHub.

2. Create a repository with your username (in my case it is ajcanlas-tip) without any files; and it should be public.

3. In your Alpine VM clone the repository you just created in my case this is my url [https://github.com/ajcanlas-tip/ajcanlas-tip.git](https://github.com/ajcanlas-tip/ajcanlas-tip.git)

4. Create a profile with markdown this is a [cheat sheat](google.com) in a "READEME.md" file

	READEME.md should have the following:

	1. Your full name

	2. Year Level

	3. Interest

	4. Email Address

	5. Computer Specs (CPU/Ram size/Disk type and size)

5. To add it to your profile add the README.md file commit it then push it in the repository (to push a repository use git _push -u origin master_)

	Commands:

	__git add READEME.md__

	__git commit -m "First commit"__

	__git push -u origin master__

6. Fork this repository [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git)

7. Clone your newly forked repository with _git clone_ _https://github.com/< your username >/sysad2-12021.git_ and go in the repository directory

8. Make a new branch named "activity2" using _git branch activity 2 and git checkout activity2_

9. Make a new new remote upstream with git

10. Create a directory with your username, create a directory name "activity2" add the previous README.md file as HA2.md

	Command used:
	
	1. mkdir < your username>

	2. mkdir activity2

	3. cp <path of your README.md file> HA2.md

11. add, commit and push it to your activity2 branch

	Command used:

	1. _git add HA2.md_

	2. _git commit -s n "activity2"_

	3. _git push -u origin upstream_

12. Request a pull request for the master branch in [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git) and activity2 branch of your forked repository

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/activity2](https://github.com/mlaabelong/sysad2-12021/tree/activity2)

# **Quiz 1.3: Git**

# **Procedure**

1. Fork this repository https://github.com/ajcanlas-tip/syad2-12021.git

2. Create a branch for your development

3. Create a directory with your student number

4. Create a file named "README.md", and the content in "README.md" is a Markdown version of your info like this [page](google.com)

5. Then create a pull request and put your forked repo in the only question of this quiz (Note answer this quiz as well as create a pull request)

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/Quizzes](https://github.com/mlaabelong/sysad2-12021/tree/Quizzes)

## **Module 2:** Leveraging Infrastructure as Code using Ansible

# **Hands-on Activity 3: Ansible Basics**

# **Procedure**

Setup is Alpine and Ubuntu VMs are connected via a local network, in my case

Alpine VM, IP is 192.168.122.117 (Or Any VM that has Git installed)

Ubuntu VM,IP is 192.168.122.125 and hostname should be ubuntu-<your student number> (e.g. ubuntu-1110670)

1. Fork the instructor repository and clone the repository.

2. Create a new branch called "activity3" and checkout in that branch.

3. Create a directory with your username as its name and go inside of it, and create a directory called "activity3" and go inside it.

4. Install Ansible via apk in your Alpine VM.

5. To check if you installed Ansible correctly check the python version it in Ansible version command would reflect python 3.

6. First, create a configuration file named "ansible.cfg", Ansible checks per-directory thus you can have multiple configurations in a system depending on your configuration file in the current directory.

7. Next, populate the ansible.cfg file with basic information such as inventory, host verification, and your default remote user.

8. Next, create your first inventory file with Ubuntu IP on it.

9. Then try to connect using "ping" module via adhoc command

10. Now use "shell" module to check the user via bash commands. (check for the user, hostname, and id)

11. And we can use the "copy" module to create a file with a certain file with the content or copy from your local VM to your remote VM.

12. For more modules, you can check this link (Links to an external site.) of the module index.

13. You can also check the description of the module using ansible-doc 

14. Also, you can group your inventory via the grouping feature of Ansible.

15. Add commit push and create a PR.

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/activity3](https://github.com/mlaabelong/sysad2-12021/tree/activity3)

# **Hands-on Activity 4: Ansible Playbooks**

# **Procedure**

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2. Clone your newly forked repository. 

3. Make a new branch named "activity4" from master branch using git branch activity4 and git checkout activity4

Note: To Prevent Conflicts Create a directory with your username as its name and go inside of it, and create a directory called "activity4" and go inside it.

4. Make a new new remote upstream with git remote add upstream https://github.com/ajcanlas-tip/sysad2-12021.git

5. Create a playbook that install java via package manager , and install boto,ansible,and openstack py packages using pip in both Ubuntu and Centos.

7. add,commit and push it to your activity4 branch

8. Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git  and activity4 branch of your forked repository.

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/activity4](https://github.com/mlaabelong/sysad2-12021/tree/activity4)

# **Hands-on Activity 5: Implement Ansible roles in playbooks**

# **Procedure**

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2. Clone your newly forked repository. 

3. Make a new branch named "activity5" from master branch using git branch activity5 and git checkout activity5

Note: To Prevent Conflicts Create a directory with your username as its name and go inside of it, and create a directory called "activity5" and go inside it.

4. Make a new new remote upstream with git remote add upstream https://github.com/ajcanlas-tip/sysad2-12021.git

5. Optimize the playbook in Hands-on Activity 4: Ansible Playbooks

7. add,commit and push it to your activity5 branch

8. Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git  and activity5 branch of your forked repository.

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/activity5](https://github.com/mlaabelong/sysad2-12021/tree/activity5)

# **Quiz 2.1: Ansible**

# **Procedure**

1. Create a directory named "quiz21" in your student number directory in Quiz 1.3/

2. Create a markdown file named "README.md" in the newly created directory with the following contents:

	1. How to create an Ansible Configuration.

	2. How to create an Ansible Inventory.

	3. How to create an Ad-hoc Ansible command with setup and shell module.

3. Then create a Pull request and put your forked repo in the only question of this quiz (Note answer this quiz as well as create a pull request).

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/Quiz2.1](https://github.com/mlaabelong/sysad2-12021/tree/Quiz2.1)

# **Quiz 2.2. Ansible Playbooks**

# **Procedure**

1. Create a directory named "quiz22" in your student number directory in Quiz 1.3

2. Create a markdown file named "README.md" in the newly created directory with the directory summary.

3. Transform this [procedure](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04) (Links to an external site.) as a playbook.

4. Then create a Pull request and put your forked repo in the only question of this quiz (Note answer this quiz as well as create a pull request).

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/Quiz2.2](https://github.com/mlaabelong/sysad2-12021/tree/Quiz2.2)

# **Quiz 2.3. Ansible Roles**

# **Procedure**

1. Create a directory named "quiz23" in your student number directory in Quiz 1.3

2. Create a markdown file named "README.md" in the newly created directory with the directory summary.

3. Optimize Quiz 2.2 with roles.

4. Then create a Pull request and put your forked repo in the only question of this quiz (Note answer this quiz as well as create a pull request).

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/Quiz2.3](https://github.com/mlaabelong/sysad2-12021/tree/Quiz2.3)

# **Hands-on Prelim Exam**

# **Procedure**

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git (Links to an external site.)

2. Clone your new repository in your VM https://github.com/< your username >/sysad2-12021.git

3. Create a branch named "prelim-exam" and checkout in that branch. 

4. Create an Ansible playbook that does the following with an input of a config.yaml file

	Role 1 (python):

		1. Installs the latest python3 and pip3

		2. use pip3 as default pip 

		3. use python3 as default python 

	Role 2 (Java)

		1. Install Java open-jdk

	Role 3 (Change motd)

		1. Create Motd containing the text defined by a variable defined in config.yaml file and if there is no variable input the default motd is "Ansible Managed node by (your user name)"

	Role 4 (Create user)

		1. Create a user with a variable defined in config.yaml

5. push and commit your prelim-exam branch in the VM (no need for ansible.cfg and inventory upon pushing)

6. request a pull request from that branch in GitHub

7. For your prelim exam to be counted, please paste your repository link as an answer in this exam.

# **Output**

[https://github.com/mlaabelong/sysad2-12021/tree/prelim-exam](https://github.com/mlaabelong/sysad2-12021/tree/prelim-exam)

