# Jupyterlab-Docker

## Introduction

A quantitative JupyterLab environment in docker with zsh shell installed.

## Install

### Option 1: Pull the image from Docker hub

```bash
docker pull edifierplus/jupyterlab
```

### Option 2: Clone and build from Github repository

```bash
git clone git@github.com:edifierplus/jupyterlab-docker.git
cd jupyterlab-docker
docker-compose build
```

## Run

### Option 1: From Docker image

```bash
docker run -p 8888:8888 -v ./jupyterlab:/root/jupyterlab --name jl jupyterlab
```

### Option 2: From Docker Compose

```bash
docker-compose start
```

## Contribute

N/A
