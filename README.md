# Udacity 730 - Deep Learning

This repo contains my assignment solutions for the UD370 Deep Learning course: https://classroom.udacity.com/courses/ud730

## Usage

For my workflow, I use PyCharm Pro + the official docker container.


## PyCharm setup

This will only work with the professional edition of PyCharm.

1. Install PyCharm Pro.
2. Import the notebook.
3. In project settings, click on "Add Remote" and select Docker.
4. Use the docker container 

## Docker setup

The Tensorflow container can be run like this:

```bash
docker run -p 8888:8888 --name tensorflow-udacity -it gcr.io/tensorflow/udacity-assignments:1.0.0
```