pixel-sprite-generator
======================

JavaScript implementation of a procedural pixel sprite generator similar to the old days of video game sprites. The sprites are algorithmically generated by combinatorial methods. 

##Live Example
[http://plnkr.co/edit/Dji8rljS0yDL16Ao8Iq6?p=preview](http://plnkr.co/edit/Dji8rljS0yDL16Ao8Iq6?p=preview)

<a href="http://plnkr.co/edit/Dji8rljS0yDL16Ao8Iq6?p=preview"><img src="https://github.com/zfedoran/pixel-sprite-generator/raw/master/doc/screenshot.png"></a>

##Algorithm

The sprites are generated by using a two dimensional mask. The values in the mask are then randomized and mirrored. The resulting template is rendered to a canvas element.

<a href="http://web.archive.org/web/20080228054410/http://www.davebollinger.com/works/pixelspaceships/"><img src="https://github.com/zfedoran/pixel-sprite-generator/raw/master/doc/algorithm-1.png"></a>

The algorithm is explained in more detail on [Dave Bollinger's](http://web.archive.org/web/20080228054410/http://www.davebollinger.com/works/pixelspaceships/) website.

<a href="http://web.archive.org/web/20080228054410/http://www.davebollinger.com/works/pixelspaceships/"><img src="https://github.com/zfedoran/pixel-sprite-generator/raw/master/doc/algorithm-0.png"></a>
