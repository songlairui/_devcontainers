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
docker build -t songlairui/node-dev:npm -f ../node-dev/Dockerfile .
```

### node-dev_taobao

default node dev environment with zsh
with taobao registry ---- https://registry.npm.taobao.org/

build image:

```bash
cd _common
docker build -t songlairui/node-dev:taobao -f ../node-dev_taobao/Dockerfile .
```
