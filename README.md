# Mkdocs-Material-PyMdown
Mkdocs image with Material theme and PyMdown extensions

## Useage

* Add Material theme and PyMdown config in your `mkdocs.yml`

* Mount the folder where your `mkdocs.yml` resides as a volume into /docs:

    `docker run --rm -it -p 8000:8000 -v ${PWD}:/docs fourleaftec/mkdocs-material-pymdown`
    
* Build documentation :

    `docker run --rm -it -p 8000:8000 -v ${PWD}:/docs fourleaftec/mkdocs-material-pymdown build`

* Run mkdocs with other command:

    `docker run --rm -it -p 8000:8000 -v ${PWD}:/docs fourleaftec/mkdocs-material-pymdown ${CMD}`
