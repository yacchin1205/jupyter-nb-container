# jupyter-nb-container

Dockerfile for building the container installed Jupyter Notebook.

# How to install

Use `docker build` command.

# How to use

Use `docker run` command.

1. Since the Jupyter notebook in the container listening on port 8888, map port 8888 in the container to some port on the host
2. If you would like to keep the notebooks on the host, mount a data volume in /var/lib/notebook (in the container)
