## aframe-gearvr-controls-component

A GearVR Controller Component component for [A-Frame](https://aframe.io).

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
  <script src="https://aframe.io/releases/0.2.0/aframe.min.js"></script>
  <script src="https://rawgit.com/chenzlabs/gearvr-controls/master/dist/aframe-gearvr-controls-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity gearvr-controls="exampleProp: exampleVal"></a-entity>
  </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-gearvr-controls-component
```

Then register and use.

```js
require('aframe');
require('aframe-gearvr-controls-component');
```
