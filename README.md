# Kadibo_booking
A vehicle reservation system

#Final Plp Project 2
The system can be used by anyone and further modified to allow reservation of vehicles online. Payment method can be integrated and receipt received whenever one pays.

#How to run it
Download this zip file and unzip in your local folder.
Make sure you have python and pip in your os.

python3 -m pip install virtualenv -run if using linux
python3 -m virtualenv myenv


Open the folder in terminal.
Activate virtual environment 
source myenv/bin/activate

Install django
python3 -m pip install django

Make migration
python3 manage.py migrate

Create super user account
python3 manage.py createsuperuser


Run the project.
python3 manage.py runserver

#All the best
