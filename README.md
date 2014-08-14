# three-pointerlock

This is an adaptation of three.js' [PointerLockControls](http://threejs.org/examples/#misc_controls_pointerlock) to a common js module, based itself on [three.fly](https://github.com/anvaka/three.fly).

# usage

``` js
// 1. Create pointer lock controls:
var PointerLockControls = require('three-pointerlock');
var controls = new PointerLockControls(camera);

// 2. Inside your update scene loop (e.g. inside requestAnimationFrame()):
controls.update(1); // `1` is time delta.
```

# install

With [npm](https://npmjs.org) do:

```
npm install three-pointerlock
```

# license

MIT
