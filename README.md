# TMDB Searcher

A small movie browser built on the [TMDb API](https://www.themoviedb.org/documentation/api). Discover popular movies, search by title, and view movie details.

> [!WARNING]
> **This repository is archived.** It is no longer maintained, and its dependencies (React 16, webpack 3, react-router 4, node-sass 4) are outdated. It is kept for reference only.

## Features

- Discover movies
- Search movies by title
- Movie detail pages

## Tech stack

- React 16, React Router, Redux, Redux-Saga
- Immutable.js
- Webpack 3, Babel 6, Sass
- ESLint (Airbnb config)

## Getting started

Requires an old Node.js version that `node-sass@4` supports (Node 8–10 era) and [Yarn](https://yarnpkg.com/).

```sh
yarn install
yarn start      # dev server (webpack-dev-server)
yarn build      # production build
```

The TMDb API key is configured in `src/api/tmdb/config.js`. Replace it with your own key from TMDb before running the app.

## Project structure

```
config/   webpack configuration (base, dev, prod)
src/
  actions/ reducers/ sagas/ store/   Redux state management
  api/tmdb/                          TMDb API endpoints
  scenes/                            Layout, List, Detail views
  models/ constants/ utils/ styles/
```
