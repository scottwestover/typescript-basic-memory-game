# TypeScript Basic Memory Game.

A basic Memory Game that is implemented in TypeScript that can be extended to work with any JavaScript framework. If you are interested in learning more about the code that is implemented, you can read more about this code on my blog here: [Creating A Memory Game In TypeScript](https://scottwestover.github.io/post/2020/06/creating-a-memory-game-in-typescript/).

Here are some examples of how the class can be extended to work with different JavaScript frameworks:
  - Phaser: Coming Soon...
  - Kontra: Coming Soon...

![License](https://img.shields.io/badge/license-MIT-green)

## Requirements

[Node.js](https://nodejs.org) and [Yarn](https://yarnpkg.com/) are required to install dependencies and run scripts via `yarn`.

[Parcel](https://parceljs.org/getting_started.html) is required to bundle and serve the web application. You can install Parcel by running the following command: `yarn global add parcel-bundler`.

## Available Commands

| Command | Description |
|---------|-------------|
| `yarn install --frozen-lockfile` | Install project dependencies |
| `yarn start` | Build project and open web server running project |
| `yarn build` | Builds code bundle for production |

## Writing Code

After cloning the repo, run `yarn install --frozen-lockfile` from your project directory. Then, you can start the local development
server by running `yarn start`.

After starting the development server with `yarn start`, you can edit any files in the `src` folder
and parcel will automatically recompile and reload your server (available at `http://localhost:8080`
by default).

## Deploying Code

After you run the `yarn build` command, your code will be built into a single bundle located at
`dist/bundle.min.js` along with any other assets you project depended.

If you put the contents of the `dist` folder in a publicly-accessible location (say something like `http://myserver.com`),
you should be able to open `http://myserver.com/index.html` and play your game.

## Customizing Template

### ESLint

This template uses `typescript-eslint` for linting, and it has been setup to extend the [airbnb](https://github.com/airbnb/javascript) style guide. To modify these settings, you will need to update the `.eslintrc.js` file with your plugins, rules, etc.

### Static Assets

Any static assets like images or audio files should be placed in the `public` folder. It'll then be served at http://localhost:8080/images/test.png
