# react-redux-saga-antd-starter

A React + Redux + Redux Actions + Redux Saga + Ant-Design frontend boilerplate.

```
#### Setup
```bash
# install dependencies
npm install (or npm install)

# serve with hot reload at localhost:8080
yarn start (or npm start)

```
```
## Scripts

- `yarn start (or npm start)`: Starts the application on development mode
- `yarn lint (or npm run lint)`: Run lint once
- `yarn lint:watch (or npm run lint:watch)`: Run tests in lint mode
- `yarn build (or npm run build)`: Build project to production
- `yarn clean (or npm run clean)`: Run clean dist

```
## Dependences

- [x] Ant-Design
- [x] Babel
- [x] ESLint (Airbnb)
- [x] LESS
- [x] PostCSS
- [x] React
- [x] React Router
- [x] React Router Redux
- [x] Redux
- [x] Redux Actions
- [x] Redux Saga

## Generated File Tree

```bash
.
├── src                    # Source directory
    ├── store              # Schems and flux data
        ├── actions
        ├── sagas
        ├── configure-store.js        
        └── reducers.js
    ├── views              # UI components
        ├── components
        └── containers
    ├── www
        └── index.html     # HTML for entry file
    ├── application.js     # Provider file
    ├── constants.js       # Constants
    ├── index.js           # Enry file
    └── theme.js           # Theme configuration for Antd
├── .editorconfig          #
├── .eslintrc              # Eslint config
├── .gitignore             #
├── .babelrc               # Babel config
└── package.json           #
```
Open `http://localhost:3000` in your browser.
