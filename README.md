# E-Commerce Project For Baby Tools
### TECHNOLOGIES
- Python
- Django
- Venv

## Project Setup
Clone the project with git

    $ git clone https://github.com/Joe-Degs/Django-E-Commerce

Create a virtual environment in the project directory

    $ python3 -m pip venv .venv
    $ source .venv/bin/activate

Install project dependencies

    $ python3 -m pip install -r requirements.txt

## Building The Project
This project is setup to build docker images and push them to docker hub automatically on a new release. There is an actions CI/CD
workflow and Dockerfile for accomplishing those specific goals.

### Building Locally
Build docker images of this project locally with

    $ docker build -t joedegs/django-e-commerce:latest -f Dockerfile .

### Releasing new Images
Pushing to the branch `master` or pushing a tag with the [semver](https://semver.org) versioning scheme will trigger a build and push to the docker hub repository [joedegs/django-e-commerce](https://hub.docker.com/r/joedegs/django-e-commerce)

### Getting new Images from DockerHub
Download latest images from docker hub with,

    $ docker pull joedegs/django-e-commerce

### Running the project
After building a local docker image or downloading one from docker hub, run the project by executing the following commands

    $ docker run -d -p 8000:8000 joedegs/django-e-commerce

### Photos

##### Home Page with login
<img alt="" src="https://github.com/MET-DEV/Django-E-Commerce/blob/master/project_images/capture_20220323080815407.jpg"></img>
##### Home Page with filter
<img alt="" src="https://github.com/MET-DEV/Django-E-Commerce/blob/master/project_images/capture_20220323080840305.jpg"></img>
##### Product Detail Page
<img alt="" src="https://github.com/MET-DEV/Django-E-Commerce/blob/master/project_images/capture_20220323080934541.jpg"></img>

##### Home Page with no login
<img alt="" src="https://github.com/MET-DEV/Django-E-Commerce/blob/master/project_images/capture_20220323080953570.jpg"></img>


##### Register Page
<img alt="" src="https://github.com/MET-DEV/Django-E-Commerce/blob/master/project_images/capture_20220323081016022.jpg"></img>


##### Login Page
<img alt="" src="https://github.com/MET-DEV/Django-E-Commerce/blob/master/project_images/capture_20220323081044867.jpg"></img>
