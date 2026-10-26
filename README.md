if you want to use the new url:
```js
javascript:(function () { var script = document.createElement('script'); script.src="https://cdn.jsdelivr.net/gh/feeshmaster/Eruda-cdn@main/eruda.js"; document.body.append(script); script.onload = function () { eruda.init(); } })();
```
or
```js
javascript:(function () { var script = document.createElement('script'); script.src="https://cdn.statically.io/gh/feeshmaster/Eruda-cdn@main/eruda.js"; document.body.append(script); script.onload = function () { eruda.init(); } })();
```
if jsdelivr is blocked.
as it is for me.
