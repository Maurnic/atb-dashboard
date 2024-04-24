[![CodeQL](https://github.com/Maurnic/atb-dashboard/actions/workflows/codeql.yml/badge.svg?branch=master)](https://github.com/Maurnic/atb-dashboard/actions/workflows/codeql.yml)
# ATB-Dashboard
_A simple dashboard for retrieving ATBs public route info using the entur API._

## Getting Started

First, run some installation scripts:

```bash
npm clean install
# Then run the development server
npm run dev
```

## Linting
For linting purposes we use Trunk. It's a comprehensive package containing several linters.

**1. Install Trunk from vscode marketplace** 

Then you can run:

```bash
trunk check --all
trunk fmt
```

## Docker
We use docker to create runnable images of our website.

**Firstly, download the docker engine from:** [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)

Open the docker desktop daemon, and then run the following command from the root of our project

```bash
docker-compose up --build
```

## Python virtual environment

When working with the backend code of our project, you should use a virtual environment.


Open [http://localhost:3000](http://localhost:3000) with your browser to see the live website.


