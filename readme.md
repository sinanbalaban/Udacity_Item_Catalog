### Item Catalog Project ###

# About
This is an application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.
Project name is Item Catalog. You can login via Facebook. When login is made, authorizations are obtained.
This program uses third party authorization with Facebook. Some of the technologies used in this app are Flask, Bootsrap and SQLite.

# To get started
I recommend the user use a virtual machine to ensure they are using the same environment that this project was developed on, running on your computer. You can download Vagrant and VirtualBox to install and manage your virtual machine. Use vagrant up to bring the virtual machine online and vagrant ssh to login.

# Requirements
[Link for Python 3] (https://www.python.org/downloads/) - Code is using version 3.8.3
[For Vagrant installation] (https://www.vagrantup.com/) - A virtual media creator and manager
[VirtualBox for the virtual machine] (https://www.virtualbox.org/) - An open source virtualization product.
[Git] (https://git-scm.com/) - Open source version control system

# How to run the program? Follow the steps below:

1 Download and install Vagrant and VirtualBox.
2 You can clone `https://github.com/udacity/fullstack-nanodegree-vm`. It is a configured vagrant file.
3 Clone this repo into the `catalog/` directory found in the Vagrant directory
4 Open your terminal (my terminal is Git Bash), Go to vagrant location directory and start the virtual machine with `vagrant up` command in this directory.
5 Use `vagrant ssh` command for login, after the virtual machine is loaded.
6 Run this command for requirements `sudo pip install -r requirements.txt`
7 Create database schema of project. You will use `python database_setup.py` command.
8 Run application with `python app.py` from within its directory
9 Go to `http://localhost:5000/` from your browser for access

Thanks