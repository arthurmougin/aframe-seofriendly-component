## aframe-seofriendly-component

[![Version](http://img.shields.io/npm/v/aframe-seofriendly-component.svg?style=flat-square)](https://npmjs.org/package/aframe-seofriendly-component)
[![License](http://img.shields.io/npm/l/aframe-seofriendly-component.svg?style=flat-square)](https://npmjs.org/package/aframe-seofriendly-component)

wrap text component to allow the use of SEO friendly tags as p,hn and more.

For [A-Frame](https://aframe.io).

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|          |             |               |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.8.2/aframe.min.js"></script>
  <script src="https://unpkg.com/aframe-seofriendly-component/dist/aframe-seofriendly-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity seofriendly="foo: bar"></a-entity>
  </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-seofriendly-component
```

Then require and use.

```js
require('aframe');
require('aframe-seofriendly-component');
```
