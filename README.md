# s3-utility-notebooks

Jupyter notebooks examples for s3 uploads and downloads

## Developing

```bash
# install venv
sudo apt install python3-venv

# make virtual env
python3 -m venv .venv

# source env
source .venv/bin/activate

# install dependencies
pip install -r ./requirements.txt
```

### Run jupyterlab server

```bash
# run jupyterlab server with specific port
jupyter lab --port=8888
```

### Run voila server

```bash
# run voila server
voila --no-browser --port=8866
```

### Run jupyterlab server with docker

```bash
# build docker image
docker build -t s3-utility-notebooks .

# run docker container
docker run -it --rm -p 8888:8888 s3-utility-notebooks
```
