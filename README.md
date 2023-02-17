# Deploy a Python Django App on Section Tutorial

![workflow status](https://github.com/section/go-tutorial/actions/workflows/workflows.yaml/badge.svg)

This repo holds the sample code for usage with the tutorials hosted on Section.io's documentations.

Refer to [Tutorials/Django](https://www.section.io/docs/tutorials/frameworks/django/) for detailed instructions on deploying to Section.

# Build and push Python Django image
```
USER=section
IMAGENAME=my-django-app
TAG=0.0.1

docker build . --tag ghcr.io/$USER/$IMAGENAME:$TAG
docker push ghcr.io/$USER/$IMAGENAME:$TAG
```
