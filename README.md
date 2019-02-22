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

#CRUD: Read


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Does the website read category and item information from a database?|Website reads category and item information from a database.|


#CRUD: Create


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Does the website include a form allowing users to add new items and correctly processes these forms?|Website includes a form allowing users to add new items and correctly processes submitted forms.|


#CRUD: Update


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Does the website include a form to update a record in the database and correctly processes this form?|Website does include a form to edit/update a current record in the database table and correctly processes submitted forms.|


#CRUD: Delete


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Website does include a form to edit/update a current record in the database table and correctly processes submitted forms.|Website does include a function to delete a current record.|


#Authentication & Authorization


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Do create, delete, and update operations consider authorization status prior to execution?|Create, delete and update operations do consider authorization status prior to execution.|
|Does the website implement a third party authentication and authorization service?|Page implements a third-party authentication & authorization service (like Google Accounts or Mozilla Persona) instead of implementing its own authentication & authorization spec.|
|Is there a “login” and “logout” button/link in the website?|Make sure there is a 'Login' and 'Logout' button/link in the project. The aesthetics of this button/link is up to the discretion of the student.|


#Code Quality


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Is the code ready for personal review and is neatly formatted?|Code is ready for personal review and neatly formatted and compliant with the Python PEP 8 style guide.|


#Comments


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Are comments present and effectively explain longer code procedures?|Comments are present and effectively explain longer code procedures.|


#Documentation


|CRITERIA | MEETS SPECIFICATIONS|
|----------|---------------------|
|Is there a README file included detailing all steps required to successfully run the application?|README file includes details of all the steps required to successfully run the application.|

