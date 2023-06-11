# E-Commerce Project For Baby Tools
### TECHNOLOGIES
- Python
- Django
- Venv

## Building Project
This project is setup to build docker images and push them to docker hub automatically on a new release. There is an actions
workflow and Dockerfile that take care of it.

### Building Locally
Build docker images of this project locally with

    $ docker build -t django-ecommerce:latest -f Dockerfile .

### Releasing new Images
Pushing to the branch `master` or pushing a tag with the [semver](https://semver.org) versioning scheme will trigger a build and push to the docker hub repository [joedegs/django-e-commerce](https://hub.docker.com/r/joedegs/django-e-commerce)

### Getting new Images from DockerHub
Download latest images from django using

    $ docker pull joedegs/django-e-commerce 

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
