### onepage-scroll
---
https://github.com/peachananr/onepage-scroll

```
<div class="main">
  <section></section>
  <section></section>
</div>
```

```js
$(".main").onepage_scroll({
  sectionContainer: "section",
  easing: "ease",
  animationTime: 1000,
  pagination: true,
  updateURL: false,
  beforeMove: funciton(index){},
  afterMove: function(index){},
  loop: false,
  keyboard: true,
  responsiveFallback: false,
  direction: "vertical"
});

$(".main").moveUp();
$(".main").moveDown();
$(".main").moveDown();
$(".main").moveTo(3);
$(".main").onepage_scroll({
  beforeMove: function(index){
  }
});
```

```
```

