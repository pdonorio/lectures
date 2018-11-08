
# lectures

Latest lessons/talks I share


## notebooks setup

You can play there with the [official jupyter docker images](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-base-notebook), e.g.

```bash
$ docker run --rm -it -p 8888:8888 \
    -v (pwd)/notebooks:/home/jovyan/lectures \
    -w /home/jovyan/lectures \
    jupyter/base-notebook
```

Then open:

http://localhost:8888
