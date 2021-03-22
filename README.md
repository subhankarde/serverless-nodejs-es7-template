# Serverless Framework Template - ES6/ES7 Compatible

## This template will standardize

- Folder structure across multiple projects.
- [serverless-pseudo-parameters plugin](https://www.npmjs.com/package/serverless-pseudo-parameters): Allows you to take advantage of CloudFormation Pseudo Parameters.
- [serverless-bundle plugin](https://www.npmjs.com/package/serverless-pseudo-parameters): Optimally packages your ES6 or TypeScript Node.js Lambda functions with sensible defaults so you don't have to maintain your own Webpack configs.

## Getting started

```
sls create --name YOUR_PROJECT_NAME --template-url https://github.com/subhankarde/serverless-nodejs-es7-template.git
cd YOUR_PROJECT_NAME
npm install
```

The original template from Codingly.io was awesome. I updated serverless.yaml to get rid of Serverless deprecation warnings. The latest version of Webpack is not compatible. Please use the below version.

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