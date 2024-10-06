#  Let's create a simple Python web application for calculator using Flask, package it into a Docker image, push it to your GitHub repository, and then run a container from that image.

#Command to create an image
docker build -t flask-calculator-app .
#Command to create a docker container
docker run -d -p 5000:5000 --name my-calculator-app flask-calculator-app

Open your web browser and navigate to http://localhost:5000. You should see the calculator interface where you can input two numbers and select an operation.
