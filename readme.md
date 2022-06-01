This is a simple loader.

Place content in the content div.
loader needs to go below <head>
  
  2 different load images, one is large, one is smaller with more area to drop.
  can adjust speed of opacity in javascript file by adjusting the numbers below.
  the loadNow(opacity is the speed opacity decreases compared to the "50" which is the amount of time in millisecond cycle
  
 ``` else {
        loader.style.opacity = opacity;
        window.setTimeout(function() {
            loadNow(opacity - 0.05);
        }, 50);
```
