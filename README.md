								**FlaskApp**
							This is a sample flask app using docker.

Getting started:
There are two ways to start this flask app, using docker image by just pulling the docker image from the registry and also by cloning the repository

Using docker 
o	Make sure you have the docker installed on your computer if not available click the link to download the tool https://www.docker.com/products/docker-desktop 
o	After the docker is installed try to pull the image 
command : docker pull kiran38/flaskapp
o	After the image is pulled try to run the image in a container by running  
command : docker run flaskapp:latest
o	After the image is running on your docker try to check the application is available on your local host computer http://localhost:5000/ in the browser or postman application. 
o	In order to check the swagger UI application http://localhost:5000/api/ui/ in your browser.


Using Github repository

o	Clone the repositoty using cmd : git clone https://github.com/Kiran-38/Flaskapp.git 
o	Activate virtual environment by getting into the flaskapp directory and activate the virtual environment with the name part1. There are different ways to do in different OS 
command:
Windows:  part1/Scripts/activate
	Linux: source part1/bin/activate	

o	After the virtual env is activated try to install the requirements.txt files 
command : pip install -r requirements.txt 
o	When the packages are installed try to run the server.py file
command : python server.py 

o	After the server is running on the computer try to check the application is available on your local host computer http://localhost:5000/ in the browser or postman application. 
o	In order to check the swagger UI application http://localhost:5000/api/ui/ in your browser.
