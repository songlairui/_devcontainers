# \_ devcontainer s

> larry's devcontainer configuration for vscode

## Folders

### \_common

- sources.list // debian source

### node-dev

default node dev environment with zsh

build image:

```bash
cd _common
docker build -t node-dev:default -f ./node-dev/Dockerfile .
```
