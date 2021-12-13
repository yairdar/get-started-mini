# get-started-mini

> Setup Dev Environment For Humans

## Obtatin

curl http://upath-http-to/nameid-token/version/latest/get-started.sh.tar.gz | tar xfv -


## Composing Enviroment From Sratch

Given a machine, with OS, which is currently linux ubuntu 20.04,
we describe composition in 3 stages, to make it easiable and fast
reprodusable, along with keeping hands-on dev freedom experience.


## Stage 0. Install Base OsTools.

Bash and PATH are our first interop language.
Here we add 3 more basic tools, that give that
interop language, structural and lexical advandatages.

- [[ `task` - structural organization of commands]]
- [[ `yq`   - query in tasks, k8s, argo, json]]
- [[ `mc`   - storage resolver with multi uri-protocols]]

We assume that we also have

- bash
- curl wget
- git

> Run next ensure operator to make shure all basic resolvers are installed

- `./task.ensure-base-os-tools.sh install-all`

> You can see the code is bellow

> And Then install custom dev tools

- `./task.ensure-base-dev-space.sh.yml install-all`

> You can see the code is bellow


## Stage 1. Install Logical Preset

Heavy Installations, which includes big datablobs.
Or heave computational costs like small network that costs alot.

- task setup-fat-dev-tensorflow
- task setup-slim-prod-clojure
- task setup-dev-clj-conda

## Stage 2. Compose Custom Parts

Second layer dependancies usually less in size
and there install is significantly faster than the others

- task add-pack-pyspark
- task add-pack-pytorch
- task add-blob-dataset-213

## Use This Repo 

### as Fork and Use as Root Repo


### Reference with reposet



