# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Repo specific instructions:

- `npm start` - this will boot up docusaurus service, will open up browser at http://localhost:3000
- `npm run build` - bundles site into static files for production
- `npm run serve` - serves built website locally
- `npm run deploy` - publishes website into github pages

Served pages:
- http://localhost:3000/react-page
- http://localhost:3000/markdown-page
- http://localhost:3000/docs/hello
- http://localhost:3000/blog/greetings

## Installation

```bash
yarn
```

## Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```bash
USE_SSH=true yarn deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
