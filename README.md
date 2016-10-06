Node.js Material Starter Template
===

A quick and easy Node.js + Jade template project, using Material Design Lite.

##Usage
- Clone repository.
- Open a command prompt, navigate to the folder, and enter: npm install
- Next, run the app by entering: node app
- Browse to http://localhost:3000

##Preview:
![Screenshot](https://raw.githubusercontent.com/primaryobjects/Node.js-Material-Starter-Template/master/public/images/screenshot.png)

##Contents:

layout.jade
header.jade
footer.jade
links.jade
index.jade

##Editing Pages:

Edit views/index.jade to add your content. The default contents include:

```
extends layout

block content
  .mdl-grid
    .mdl-cell.mdl-cell--12-col
      h1 Program Name
      p Hello World
```

##Adding Components

The template is compatible with all [Material Design Lite](https://getmdl.io/components/index.html) UI components.

For example, to add a button to the page, edit index.jade and add the snippet:

```
button.mdl-button.mdl-js-button.mdl-button--raised.mdl-js-ripple-effect.mdl-button--accent
  | My Button
```

##Author
Kory Becker http://www.primaryobjects.com/kory-becker
