# made-with-love

> <:purple_heart: /> A Polymer element for show your love!.

[![Travis CI Status](https://travis-ci.org/simoneas02/made-with-love.svg?branch=master)](https://travis-ci.org/simoneas02/made-with-love)
![bower](https://img.shields.io/bower/v/made-with-love.svg)

## How to install and use:

**0 -** install the basic dependencies

- [NodeJS](https://nodejs.org/en/)
- [Bower](https://www.npmjs.com/package/bower)

**1 -** Install the element using [Bower](http://bower.io/):

```sh
$ bower install made-with-love --save
```

**2 -** Import the element:

```html
<link rel="import" href="bower_components/made-with-love/made-with-love.html">
```

**3 -** Start using it!

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="made-with-love.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<made-with-love href="https://simoneas02.github.io/">Simone Amorim</made-with-love>
```

## Properties

Property  | Type        | Default   | Description
---       | ---         | :---:       | ---
`href`    | *String*    | `#`       | Hiper link reference

## Styling

The following custom properties and mixins are available for styling:

Custom property               | Default  | Description
---                           | :---:    | ---
--made-with-love-color        | #000     | Text color
--made-with-love-text         | {}       | Text style
--made-with-love-heart-color  | #6309a0  | Heart color
--made-with-love-heart-size   | 10px     | Heart size

## Browser Support

Using the [webcomponents.js](https://github.com/WebComponents/webcomponentsjs):

![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png) | ![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png)
--- | --- | --- | --- | --- |
11+ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔

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

Go to [localhost:8080/components/made-with-love/](http://localhost:8080/components/made-with-love/)

## Tests

Linting with polylint:

```sh
$ [sudo] npm install -g polylint

$ polylint
```

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing

Find on our [issues](https://github.com/simoneas02/made-with-love/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://https://github.com/simoneas02/made-with-love/issues/blob/master/CONTRIBUTING.md).

## License

[MIT License](https://github.com/simoneas02/made-with-love/blob/master/license.md) © [Simone Amorim](https://simoneas02.github.io)
