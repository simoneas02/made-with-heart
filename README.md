# made-with-love

> <:purple_heart: /> A Polymer element for show your love!.

[![Travis CI Status](https://travis-ci.org/simoneas02/made-with-heart.svg?branch=master)](https://travis-ci.org/simoneas02/made-with-heart)
![bower](https://img.shields.io/bower/v/made-with-heart.svg)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/simoneas02/made-with-heart)

## How to install and use:

**0 -** install the basic dependencies

- [NodeJS](https://nodejs.org/en/)
- [Bower](https://www.npmjs.com/package/bower)

**1 -** Install the element using [Bower](http://bower.io/):

```sh
$ bower install made-with-heart --save
```

**2 -** Import the element:

```html
<link rel="import" href="bower_components/made-with-heart/made-with-heart.html">
```

**3 -** Start using it!

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="made-with-heart.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<made-with-heart href="https://simoneas02.github.io/">Simone Amorim</made-with-heart>
```

## Properties

Property  | Type        | Default   | Description
---       | ---         | :---:       | ---
`href`    | *String*    | `#`       | Hiper link reference

## Styling

The following custom properties and mixins are available for styling:

Custom property               | Default  | Description
---                           | :---:    | ---
--made-with-heart-text-color  | #000     | Text color
--made-with-heart-text        | {}       | Text style
--made-with-heart-color       | #6309a0  | Heart color
--made-with-heart-size        | 10px     | Heart size

## Browser Support

Using the [webcomponents.js](https://github.com/WebComponents/webcomponentsjs):

 ![Chrome](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/chrome/chrome_48x48.png) | ![Opera](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/opera/opera_48x48.png) | ![Firefox](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/firefox/firefox_48x48.png) | ![Safari](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/safari/safari_48x48.png) |![IE](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |  ![Edge](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/edge/edge_48x48.png) |
:---: | :---: | :---: | :---: | :---: | :---: |
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | 11+ | Latest ✔

## Development

**1 -** Install [Bower](http://bower.io/) & [Polymer-CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli):

```sh
$ [sudo] npm install -g bower polymer-cli
```

**2 -** Install local dependencies:

```sh
$ bower install
```

**3 -** Start the development server:

```sh
$ polyserve
```

Go to [localhost:8080/components/made-with-heart/](http://localhost:8080/components/made-with-heart/)

## Tests

Linting with polylint:

```sh
$ [sudo] npm install -g polylint

$ polylint
```

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing

Find on our [issues](https://github.com/simoneas02/made-with-heart/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://https://github.com/simoneas02/made-with-heart/issues/blob/master/CONTRIBUTING.md).

## License

[MIT License](https://github.com/simoneas02/made-with-heart/blob/master/license.md) © [Simone Amorim](https://simoneas02.github.io)
