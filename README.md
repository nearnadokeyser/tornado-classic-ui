# Tornado Cash Classic UI

> UI for non-custodial Ethereum Privacy solution

## Building locally

- Install [Node.js](https://nodejs.org) version 14
    - If you are using [nvm](https://github.com/creationix/nvm#installation) (recommended) running `nvm use` will automatically choose the right node version for you.
- Install [Yarn](https://yarnpkg.com/en/docs/install)
- Install dependencies: `yarn`
- Copy the `.env.example` file to `.env`
    - Replace environment variables with your own personal.
- Build the project to the `./dist/` folder with `yarn generate`.

## Development builds

To start a development build (e.g. with logging and file watching) run `yarn dev`.

## Deploy on IPFS

- Make sure you set `PINATA_API_KEY` and `PINATA_SECRET_API_KEY` environment variables in `.env`
- To deploy a production build run `yarn deploy-ipfs`.

## Architecture

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).