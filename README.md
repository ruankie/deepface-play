[![GitHub last commit](https://img.shields.io/github/last-commit/ruankie/poetry-py-template)](https://github.com/ruankie/poetry-py-template/commits/main)

# deepface-play

## Description

Playing around with [`deepface`](https://github.com/serengil/deepface/tree/master).

## Setup

Set up environment with correct Python version and dependencies
```shell
pyenv install 3.11.2
pyenv global 3.11.2
sudo apt-get update && sudo apt-get install ffmpeg libsm6 libxext6  -y
pip install -r requirements.txt
```

## Usage
0. (Optional) Get sample test images [here](https://github.com/serengil/deepface/tree/master/tests/dataset)
1. Browse notebooks at `notebooks/`

## TODO
- [ ] Find a way to make this work better with Poetry or Conda
- [ ] Make scriptsin `src` visible to dev env
