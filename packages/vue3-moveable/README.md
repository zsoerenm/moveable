

<p align="middle" ><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/logo.png"/></p>
<h2 align="middle">Vue 3 Moveable</h2>
<p align="middle">
<a href="https://www.npmjs.com/package/vue3-moveable" target="_blank"><img src="https://img.shields.io/npm/v/vue3-moveable.svg?style=flat-square&color=007acc&label=version" alt="npm version" /></a>
<img src="https://img.shields.io/badge/language-typescript-blue.svg?style=flat-square"/>
<a href="https://github.com/daybrush/moveable/blob/master/LICENSE" target="_blank"><img src="https://img.shields.io/github/license/daybrush/moveable.svg?style=flat-square&label=license&color=08CE5D"/></a>
</p>
<p align="middle">A Vue 3 Component that create Moveable, Draggable, Resizable, Scalable, Rotatable, Warpable, Pinchable, Groupable, Snappable.</p>
<p align="middle">
    <a href="https://daybrush.com/moveable" target="_blank"><strong>Demo</strong></a> /
    <a href="https://github.com/daybrush/moveable/tree/master/packages/vue-moveable" target="_blank"><strong>Vue 2</strong></a> /
    <a href="https://daybrush.com/moveable/storybook/" target="_blank"><strong>Storybook</strong></a> /
    <a href="https://daybrush.com/moveable/release/latest/doc/" target="_blank"><strong>API</strong></a> /
    <a href="https://github.com/daybrush/scena" target="_blank"><strong>Main Project</strong></a>
</p>



<table width="100%" align="center">
<tr>
<th colspan="4">Moveable</th>
</tr>
<tr>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-draggable"><strong>Draggable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-resizable"><strong>Resizable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-scalable"><strong>Scalable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-rotatable"><strong>Rotatable</strong></a></td>
</tr>
<tr>
<td align="center">
<img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/draggable.gif">
</td>
<td align="center">
<img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/resizable.gif">
</td>
<td align="center">
<img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/scalable.gif">
</td>
<td align="center">
<img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/rotatable.gif">
</td>
</tr>
<tr>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-warpable"><strong>Warpable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/release/latest/doc/Moveable.Pinchable.html"><strong>Pinchable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/group--group-draggable-resizable-rotatable"><strong>Groupable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/snap-bound--snap-guidelines"><strong>Snappable</strong></a></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/warpable.gif"></td>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/pinchable.gif"></td>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/groupable.gif"></td>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/snappable.gif"></td>
</tr>
<tr>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-clippable"><strong>Clippable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-roundable"><strong>Roundable</strong></a></td>
<td align="center"><a href="https://daybrush.com/moveable/storybook/index.html?path=/story/basic--basic-origin-draggable"><strong>OriginDraggable</strong></a></td>
<td align="center"><a href="https://github.com/daybrush/selecto"><strong>Selecto</strong></a></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/clippable.gif"></td>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/roundable.gif"></td>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/origindraggable.gif"></td>
<td align="center"><img src="https://raw.githubusercontent.com/daybrush/moveable/master/demo/images/selecto.gif"></td>
</tr>
</table>


## 🔥 Features
* **Draggable** refers to the ability to drag and move targets.
* **Resizable** indicates whether the target's width and height can be increased or decreased.
* **Scalable** indicates whether the target's x and y can be scale of transform.
* **Rotatable** indicates whether the target can be rotated.
* **Warpable** indicates whether the target can be warped(distorted, bented).
* **Pinchable** indicates whether the target can be pinched with draggable, resizable, scalable, rotatable.
* **Groupable** indicates Whether the targets can be moved in group with draggable, resizable, scalable, rotatable.
* **Snappable** indicates whether to snap to the guideline.
* **OriginDraggable*** indicates Whether to drag origin.
* **Clippable** indicates Whether to clip the target.
* **Roundable** indicates Whether to show and drag or double click border-radius.
* Support SVG Elements (svg, path, line, ellipse, g, rect, ...etc)
* Support Major Browsers
* Support 3d Transform


## ⚙️ Installation

* Vue 3
```sh
$ npm i vue3-moveable
```

* Vue 2
```sh
$ npm i vue-moveable@beta
```

## 🚀 How to use
If you want to check the methods and events, please refer to the [**API documentation**](https://daybrush.com/moveable/release/latest/doc/).

```vue
<template>
<div class="container">
    <div class="target" ref="target">Vue Moveable</div>
    <Moveable
        className="moveable"
        v-bind:target="['.target']"
        v-bind:draggable="true"
        v-bind:scalable="true"
        v-bind:rotatable="true"
        @drag="onDrag"
        @scale="onScale"
        @rotate="onRotate"
    />
</div>
</template>
<script>
// `VueMoveableInstance` is Vue Moveable's Instance type.
import Moveable, { VueMoveableInstance } from "vue3-moveable";

export default {
  name: "app",
  components: {
    Moveable,
  },
  methods: {
    onDrag({ transform }) {
        this.$refs.target.style.transform = transform;
    },
    onScale({ drag }) {
        this.$refs.target.style.transform = drag.transform;
    },
    onRotate({ drag }) {
        this.$refs.target.style.transform = drag.transform;
    },
  }
}
</script>
```


## ⚙️ Developments
### `npm run serve`

Runs the app in the development mode.<br>
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.



## ⭐️ Show Your Support
Please give a ⭐️ if this project helped you!


## 👏 Contributing

If you have any questions or requests or want to contribute to `moveable` or other packages, please write the [issue](https://github.com/daybrush/moveable/issues) or give me a Pull Request freely.


### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](https://github.com/daybrush/moveable/blob/master/CONTRIBUTING.md)].

<a href="https://github.com/daybrush/moveable/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=daybrush/moveable" />
</a>

## 🐞 Bug Report

If you find a bug, please report to us opening a new [Issue](https://github.com/daybrush/moveable/issues) on GitHub.

## Sponsors
<p align="center">
	<a href="https://daybrush.com/sponsors/sponsors.svg">
		<img src="https://daybrush.com/sponsors/sponsors.svg"/>
	</a>
</p>




## 📝 License

This project is [MIT](https://github.com/daybrush/moveable/blob/master/LICENSE) licensed.

```
MIT License

Copyright (c) 2019 Daybrush

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
