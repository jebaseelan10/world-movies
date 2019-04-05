# world-movies

## Fork it, then Clone (from your forked repo)

Clone the world-movies repository

Navigate to that directory
```
cd world-movies
```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### To start...
```
git checkout dev
```

### Install [Cypress](https://www.cypress.io/)
```
npm install --save-dev cypress
```

##### Add below lines in scripts section of `package.json` file
```
"cypress:open": "cypress open"
```
```
"cypress:run": "cypress run"
```

### Run cypress test with normal browser
```
npm run cypress:open
```

### Run cypress test with headless browser
```
npm run cypress:run
```

[Cypress Api](https://docs.cypress.io/api/api/table-of-contents.html)

### Branch naming convention
| Name | Description |
| --- | --- |
| dev | Basic working app |
| dev-2 | Cypress setup |
| dev-3 | Login page test cases |
| dev-4 | Home page test cases |
| dev-5 | Footer component test cases |
| dev-6 | Login test cases with error scenarios |

PS: Once checkout in `dev` branch no need to switch branches for linear flow... 

