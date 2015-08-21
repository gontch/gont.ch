# gont.ch-site
the gont.ch site

This provides a server sering the gont.ch ontology. By default the serve listens to port 8080 and the URI prefix `https://gont.ch/` is replaced with `http://localhost:8080/`.

## Requirements

You need to have [docker](https://docker.com/) installed.

## Building

    docker build -t gont .
    
## Running

    docker run --rm -p 8080:8080 gont
    
To verify that things are running point your browser to `http://localhost:8080/Municipality`.