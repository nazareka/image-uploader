﻿# image-uploader
 
to run the program enter

docker-compose up -d --build

docker-compose exec web-backend python manage.py migrate 

makes tables in the database and creates 3 plans - Basic, Premium, Enterprise, and Admin user with Admin_password and with Basic plan

