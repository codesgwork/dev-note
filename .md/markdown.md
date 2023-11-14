## Contents

```JSON
{
  "name": "css-scssprojects",
  "version": "1.0.0",
  "description": "- Config - font - contents - button, a, forms, autoWidth",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/skyGwork/css-scssProjects.git"
  },
  "keywords": [],
  "author": "webphin",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/skyGwork/css-scssProjects/issues"
  },
  "homepage": "https://github.com/skyGwork/css-scssProjects#readme"
}
```


## Image

![alt](https://cldup.com/dTxpPi9lDf.thumb.png)

[![alt](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.

- Type some Markdown on the left
- See HTML in the rights
- ✨Magic ✨

## Lists

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

## Text flag

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable

> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

## Link

Dillinger uses a number of open source projects to work properly:

- [AngularJs](https://angularjs.org/) - HTML enhanced for web apps!

- [Express] - fast node.js network app framework [@tjholowaychuk]

And of course Dillinger itself is open source with a [public repository][dill]
on GitHub.

## CODE

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Table

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin           | README                                    |
| ---------------- | ----------------------------------------- |
| Dropbox          | [plugins/dropbox/README.md][pldb]         |
| GitHub           | [plugins/github/README.md][plgh]          |
| Google Drive     | [plugins/googledrive/README.md][plgd]     |
| OneDrive         | [plugins/onedrive/README.md][plod]        |
| Medium           | [plugins/medium/README.md][plme]          |
| Google Analytics | [plugins/googleanalytics/README.md][plga] |
