# Reaction

React Java Script

## Init

```
npx create-react-app reaction
```

Creates boilerplate, seems to have many files...

```
reaction/
  |_ node_modules/ # contains npm dependencies, many files here...
  |_ public/ # immutable pages?
  |_ src/ # react/javascript?
  |
  |_ package.json
  |_ package-lock.json
  |_ README.md
```

Start github pages although not seeing a drop down toward `public`.

![](imgs/githubpages.png)


## Build

navigate to folder

```
cd reaction
npm run build 
```

Which creates a new `build` folder

```
cd build
find . 
```

```
build/
  |_ static/
  |  |_ css/
  |  |_ js/
  |  |_ media/
  |_ index.html
  |_ various files...
```

* View at: https://j23414.github.io/reaction/reaction/build/index.html

Which is initially blank, until we edit the package.json?

Yup: https://github.com/gitname/react-gh-pages#3-install-the-gh-pages-npm-package

```
npm install gh-pages --save-dev
```

and add some manual changes to packages.json
