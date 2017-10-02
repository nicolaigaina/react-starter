# React Starter Kit
### Install
```
yarn install
```
##### Command Setup
In the project directory, you can run:
```
yarn start or yarn build
```
Runs the app in the development mode.
Open http://localhost:9000 to view it in the browser.

The page will reload if you make edits.
```
yarn build:prod
```
Builds the app for production to the app folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified.
Your app is ready to be deployed!

### Dynamic copyright/project banners

The package.json includes the dependencies for the project as well as information about the project. Entries here will be dynamically appended to the top of generated `.css` and` .js` files, by default it ships with FastShell's banner:

#### Scaffolding
```
ReactStarterKit
├── README.md
├── node_modules
├── webpack.config.js
├── postcss.config.js
├── package.json
├── .gitignore
├── app
│   ├── assets
│   │   ├── css
│   │   ├── img
│   │   └── js
│   ├── favicon.ico
│   └── index.html
│   
└── src
    └── app
    │    ├── components
    │    └── utils
    └── scss
    │    ├── mixins
    │    ├── modules
    │    ├── partials
    │    ├── vendor
    │    └── style.scss
    └── index.js
    └── favicon.ico
```
