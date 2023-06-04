# eslint-config

Reusable eslint rules configuration

How to use 

Install it over npm
`npm install @tim-mhn/eslint-config`

Add it in your eslint file 
```
// .eslintrc.js
module.exports = {
  ...,
  extends: "@tim-mhn", <-- add this line. 
  parserOptions: {
    ...,
    tsconfigRootDir: __dirname,
  },
  ...
};
```
