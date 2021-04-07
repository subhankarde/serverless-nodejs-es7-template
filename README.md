# Serverless Framework Template - ES6/ES7 Compatible

## This template will standardize

- Consistent folder structure across multiple projects.
- [serverless-bundle plugin](https://www.npmjs.com/package/serverless-bundle): Optimally packages your ES6 or TypeScript Node.js Lambda functions with sensible defaults so you don't have to maintain your own Webpack configs.
- [serverless-pseudo-parameters plugin](https://www.npmjs.com/package/serverless-pseudo-parameters): Allows you to take advantage of CloudFormation Pseudo Parameters.


## Getting started

```
sls create --name <YOUR_PROJECT_NAME> --template-url https://github.com/subhankarde/serverless-nodejs-es7-template.git
cd YOUR_PROJECT_NAME
npm install
```

The latest version of Webpack is not compatible. Please use the below version.

## Latest npm packages

```
npm i -g npm-check-updates
ncu -u
npm install
```

## Webpack version

```
npm uninstall webpack
npm install --save-dev webpack@4.46.0
```
