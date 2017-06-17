# Udacity-FSND-Project3.2
Catalog App

Prepare Vagrant environment
1.1 Install VirtualBox

Download and instrall the platform package for your current operating system via: https://www.virtualbox.org/wiki/Downloads

1.2 Install Vagrant

Download and install the Vagrant software via: https://www.vagrantup.com/downloads.html

1.3 Download FSND VM configuration

Either download and unzip the FSND VM configuration file from: https://d17h27t6h515a5.cloudfront.net/topher/2017/May/59125904_fsnd-virtual-machine/fsnd-virtual-machine.zip or clone the repo: https://github.com/udacity/fullstack-nanodegree-vm

In your terminal, navigate to the folder where configration files are located. Change directory to "vagrant" and start the virtual machine by runnning command "vagrant up".

Once the VM configration is complete, log in your VM by command "vagrant ssh".

1.4 Install Catalog App
Download the zip file of this repository and unzip the files and folders to your working directory.

1.5 Initialize database

Run python database_setup.py to initialize database for this catalog app.

1.6 Run the app

Run python project.py to start web app server. Navigate to localhost:5000 to visit the catalog. By using the app, you can create a list of universities and the countries they are located.
