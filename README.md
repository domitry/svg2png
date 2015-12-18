# svg2png
Encode svg to uri-encoded png.
Most lines are from [d3-downloadable](https://github.com/likr/d3-downloadable).

## HOW TO USE
```javascript
require(['svg2png'], function(util){
  var svg = d3.select("svg");
  util.svg2uri(svg).then(function(uri){
    d3.select("div")
      .append("img")
      .attr("str", uri);
  });
})
```

## LICENCE
[MIT License](https://github.com/domitry/svg2png/blob/master/LICENSE)
