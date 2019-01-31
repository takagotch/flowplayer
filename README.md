### flowplayer
---
https://github.com/flowplayer/flowplayer

```
export mxmlc=<PATH_TO>/flex_sdk_4.5.1.212328_mpl/bin/mxmlc
cd ./flowplayer
make flash
```

```js
flowplayer(1).bind("load", function(e, api, video){
}).bind("pause", function(e, api){
});
$(".flowplayer").bind("unload", function(e, api){
});
```

```
<!DOCTYPE html>
<head>
  <script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery.min.js"></script>
  <script type="text/javascript" src="flowplayer.min.js"></script>
  <link rel="stylesheet" type="text/css" href="flowplayer/minimalist.css">
</head>
<body>
  <div class="flowplayer">
  </div>
  <div class="flowplayer">
    <video>
      <source type="video/webm" src="my-video2.webm">
      <source type="video/mp4" src="my-video2.mpr">
    </video>
  </div>
</body>
```

