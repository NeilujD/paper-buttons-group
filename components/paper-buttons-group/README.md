[![Build Status](https://travis-ci.org/NeilujD/paper-buttons-group.svg?branch=develop)](https://travis-ci.org/NeilujD/paper-buttons-group)

[Demo and API Docs](https://neilujd.github.io/paper-buttons-group)

# \<paper-buttons-group\>

## Example

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../paper-button/paper-button.html">
    <link rel="import" href="paper-buttons-group.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-buttons-group selected="0">
  <paper-button>CHOICE 1</paper-button>
  <paper-button>CHOICE 2</paper-button>
  <paper-button>CHOICE 3</paper-button>
</paper-buttons-group>
```

A button group with `paper-button` style

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
