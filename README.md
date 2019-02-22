FSND-Project-Item Catalogue
This project is a flask application which provides  provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.
#To test this you need to have vagrant installed on your machine. #Steps to download vagrant and run tool

1.Download and install Vagrant(https://www.vagrantup.com/) and VirtualBox(https://www.virtualbox.org/).
2.Download/Clone the VM configuration from https://github.com/udacity/fullstack-nanodegree-vm . 
the path where you have downloaded/clone will be used in next steps 
3.clone this project into the /vagrant/ (created in step 2) 

#Running the Item Catalogue falsk server

*Open shell prompt(use gitbash in windows)

#Installing & Configuring VM

cd ../vagrant vagrant up

#Logging into machine

vagrant ssh

#Creating DB.

python database_setup.py

#Run the program

python application.py

# this application will run in python 2.7. this is not compatible for python3

#Flask application navigations are provided in screenshots.pdf attached here

#Comments


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Are comments present and effectively explain longer code procedures?|Comments are present and effectively explain longer code procedures.|


# This porject confirms criteria defined here https://review.udacity.com/#!/rubrics/2008/view
