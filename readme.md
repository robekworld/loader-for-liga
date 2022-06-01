This is a simple loader.

Place content in the content div.
loader needs to go below <head>
  
  2 different load images, one is large, one is smaller with more area to drop.
  can adjust speed of opacity in javascript file
  
  else {
        loader.style.opacity = opacity;
        window.setTimeout(function() {
            loadNow(opacity - 0.05);
        }, 50);
