<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>


## Description

This repository is a starter project built using the NestJS framework, written in TypeScript. The project serves as a foundation for building scalable server-side applications with NestJS, following best practices for modular architecture and development

## Prerequisites
Tools installed:

- [Node.js](https://nodejs.org/) (version 20.x or higher recommended)
- [Yarn](https://yarnpkg.com/getting-started/install) (for package management)
- [Docker Desktop](https://www.docker.com/products/docker-desktop) (for containerized services)

## Dev Installation
1. **Clone the repository**:


   Clone the repository using the command below and navigate to the project directory:

```bash
    git clone <repository-url>
    cd <project-directory>
```

2. **Set up environment variables**:


    Copy the file ```.env.template``` and rename it to ```.env.```
    

3. **Install dependencies**:


    Run the following command to install the required packages:

```bash
    $ yarn install
```

4. **Start Docker containers**:


    Ensure that Docker Desktop is running, then start the containers using docker-compose:

``` bash
    $ docker-compose up -d
```

## Running the app

```bash
    # development watch mode
    $ yarn run start:dev

    # production mode
    $ yarn run start:prod
```

## This endpoint will allow you to interact with your GraphQL API, test queries, and mutations.

```
    http://localhost:3000/graphql
```