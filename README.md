# BMapLib.TextIconOverlay

## Installation

### NPM

```bash
$ npm i --save bmaplib.texticonoverlay
```

### CDN

```html
<script src="//unpkg.com/bmaplib.texticonoverlay"></script>
```

## Usage

### ES Next

```js
import TextIconOverlay from 'bmaplib.texticonoverlay'

// You should use this lib after BaiduMap loaded. For Example:

loadBaiduMap.then(() => {
  new TextIconOverlay()
})
```

### CDN

```html
<script src="//api.map.baidu.com/api?v=2.0"></script>
<script src="//unpkg.com/bmaplib.texticonoverlay"></script>
<script>
  new BMapLib.TextIconOverlay()
</script>
```
