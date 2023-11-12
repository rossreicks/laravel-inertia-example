# Laravel Example Project

This project was generated to be a starting point for a [Laravel](https://laravel.com/) project.

This project is using: @inertiajs/react to provide a react front end, and laravel as the backend.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/)
- [VS Code](https://code.visualstudio.com/)

### Installing

1. Clone the repository
2. Make sure Docker is running
3. Open vscode and make sure to have the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension installed
4. Open the project in vscode as a dev containers project
5. yarn install
6. yarn dev

## Why a dev container?

By providing a dev container, we can have docker pull down all the required versions of the underlying backend dependencies.

We still run a vite server for the front end (using yarn dev) to get live reloading and improve our developer experience, but the backend is running in a docker container.

The Dev container is responsible for running the laravel server, the database, and the redis server.

I don't see how this will work without php and composer installed on the host machine, but we will see..
