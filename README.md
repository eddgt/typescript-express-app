# TypeScript and Express example

## How to init and create the app helloworld Rest

## Install TypeScript
```js
 npm i -g typescript
```

## See ts version
```js
 tsc --version
```

## Convert .ts to .js
```js
 tsc app.ts 
```

## Open file in VSCode (VSCode preinstalled required)
```js
 code app.ts
``` 

## compile app in ts in current path
```js
 tsc
``` 

## init node app
```js
 npm init
``` 

## install libs
```js
 npm i express
 npm i -D typescript ts-node nodemon @types/node @types/express
``` 


## start app in Dev
1. add on scripts in packages.json 

    "scripts": {
        "start": "npm dist/app.js",
        "dev": "nodemon src/app.ts",
        "build": "tsc -p .",
        "test": "echo \"Error: no test specified\" && exit 1"
    },

2. start in dev mode
```js
 npm run dev
``` 

3. go to http://localhost:5000/

 you will get "Hello" message