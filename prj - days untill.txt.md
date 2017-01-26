##Days until

* Day counter
* cube to other formats
* pager to other/next dates

https://developer.apple.com/safaridemos/photo-transitions.php

```
<html>
<head></head>
<style type="text/css">
/* CUBE */
#transitions #cube {
    -webkit-transform-style: preserve-3d;
    width: 250px;
    height: 100px;
    position: absolute;

}
#transitions #cube.active {
    -webkit-animation-duration: 1s;
    -webkit-animation-iteration-count: 1;
    -webkit-animation-name: cubedemo;
    -webkit-transform: rotateX(-90deg);
}
#transitions #cube .face {
    position: absolute;
    width: 250px;
    height: 100px;
    display: block;
    overflow: hidden;
}
#transitions #cube .front {
    -webkit-transform: scale3d(.835,.835,.835) translateZ(200px);
}
#transitions #cube .back {
    -webkit-transform: scale3d(.835,.835,.835) rotateY(180deg) translateZ(200px);
}
#transitions #cube .top {
    -webkit-transform: scale3d(.835,.835,.835) rotateX(90deg) translateZ(200px);
}
@-webkit-keyframes cubedemo {
    0% { -webkit-transform: rotateX(0); -webkit-animation-timing-function: linear; }
    50% { -webkit-transform: rotateX(-92deg); -webkit-animation-timing-function: ease-in; }
    70% { -webkit-transform: rotateX(-84deg); -webkit-animation-timing-function: ease-in; }
    80% { -webkit-transform: rotateX(-90deg); -webkit-animation-timing-function: ease-in; }
    95% { -webkit-transform: rotateX(-88deg); -webkit-animation-timing-function: ease-in; }
    100% { -webkit-transform: rotateX(-90deg); }
}​
</style>
<body>
<div id="cube" class="demo">
                                <div class="front face outgoing"><img src="https://devimages.apple.com.edgekey.net/safaridemos/showcase/transitions/images/showcase_transitions_001.jpg" width="250" height="100"></div>
                                <div class="top face incoming"><img src="https://devimages.apple.com.edgekey.net/safaridemos/showcase/transitions/images/showcase_transitions_002.jpg" width="250" height="100"></div>
                            </div>
</body>
</html>
```

---
2012-06-26