![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/k3jph/torch-diffeq)
![Docker Pulls](https://img.shields.io/docker/pulls/k3jph/torch-diffeq)
![Docker Image Version (latest semver)](https://img.shields.io/docker/v/k3jph/torch-diffeq?sort=semver)
[![DOI](https://zenodo.org/badge/367334926.svg)](https://zenodo.org/badge/latestdoi/367334926)

# TorchCDE Dockerfile

[Docker](http://docker.com) container to use [Pyomo](http://www.pyomo.org/) with
[GLPK](https://www.gnu.org/software/glpk/) and [COIN-OR](https://www.coin-or.org/).

## Usage

### Install

Pull `k3jph/python-optimization` from the Docker repository:

    docker pull k3jph/python-optimization

Or build `k3jph/python-optimization` from source:

    git clone https://github.com/k3jph/python-optimization.git
    docker build -t k3jph/python-optimization .

## Services

This is for [Open Science Grid's Singularity](https://support.opensciencegrid.org/support/solutions/articles/12000024676-docker-and-singularity-containers) containers, so no services
are provided.


## Volumes

Volume          | Description
----------------|-------------
`/srv`          | The location of the application root
`/cvmfs`        | The OSG's CVMFS storage system
