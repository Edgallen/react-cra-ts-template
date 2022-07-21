# React template
Ready to use CRA react template with typescript.

## Table of contents
1. [Installation](#Installation)
2. [Libraries](#Libraries)
3. [Tests](#Tests)
4. [Css modules](#Css-modules)
4. [Deploy](#Deploy)

### Installation

To start developing:

1. clone repo
   ```sh
   git clone https://github.com/Edgallen/react-burger
   ```
2. install packages
   ```sh
   npm install
   ```
3. start local server
   ```sh
   npm start
   ```
   
--[Back to top](#Table-of-contents)--

### Libraries

Installed libriaries:

* React
* Redux
* React-Router 6
* uuid

--[Back to top](#Table-of-contents)--

### Tests

Installed libriaries for tests:

* Jest
* Cypress

In order to open Cypress:

```sh
   npm run cypress:open
```

--[Back to top](#Table-of-contents)--

### Css modules

This template have ready to use css modules.

1. Import styles

```js
   import styles from './styles.css';
```
2. Add to an element

```js
   <h1 className={styles.name}>Hello world!</h1>;
```

--[Back to top](#Table-of-contents)--

### Deploy

In order to deploy to gh pages use those scripts:

1. Predeploy (will build your project)

```sh
   npm run predeploy
```
2. Deploy (will create gh-pages branch)

```sh
   npm run deploy
```

You can also modify "deploy-script" to deploy your project on linux server.

1. Change "login", "publicIp" and "/route"

```json
    "deploy-script": "npm run build && scp -r ./build/* login@publicIp:/route"
```

2. deploy

```sh
   npm run deploy-script
```

--[Back to top](#Table-of-contents)--