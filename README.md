# A-Frame Mouse Cursor Component

This is similar to `cursor` component besides the mouse behaves as cursor.
There is no `mouseenter` or `mouseleave` events but `click` event for mobile.

For detail, please check [cursor page](https://aframe.io/docs/components/cursor.html).

![example](example.gif)

## Properties

There is no property.


## States

The `mouse-cursor` will add states to the cursor entity on certain events.

| State Name | Description |
| -------- | ----------- |
| hovering | Added when the cursor is hovering over another entity. |

The cursor will add states to the target entity on certain events.

| State Name | Description |
| -------- | ----------- |
| hovered | Added when target entity is being hovered by the cursor. |


## Events

| Event Name | Description |
| -------- | ----------- |
| click | Triggered when an entity is clicked. |
| mouseenter | Triggered on mouseenter of the canvas. |
| mouseleave | Triggered on mouseleave of the canvas. |

For events, please check [demo page](https://mayognaise.github.io/aframe-mouse-cursor-component/basic/index.html).


## Usage

**The `mouse-cursor` component is usually used alongside the [camera component][components-camera].**

### Browser Installation

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.2.0/aframe.min.js"></script>
  <script src="https://rawgit.com/mayognaise/aframe-mouse-cursor-component/master/dist/aframe-mouse-cursor-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity camera mouse-cursor>
  </a-scene>
</body>
```

### NPM Installation

Install via NPM:

```bash
npm i -D aframe-mouse-cursor-component
```

Then register and use.

```js
import 'aframe'
import 'aframe-mouse-cursor-component'
```



