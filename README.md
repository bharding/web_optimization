Index.html
On the index page I put the css in the html file
put the images in a sprite sheet compressed the images
added @media print 
Moved the js files to the bottom to keep from blocking
copy images locally

Pizza.html
put the css code in the html file
copy images locally
moved css and js files to load last to keep from blocking

Main.js
 function changePizzaSizes declared variable before the for loop
 Added the function onScroll()  to determine the scroll position call the updatePosition on the requestAnimationFrame
 On the function updatePositions moved all the variable before the for loop
  call the onscroll function instead fo the updatePositions window.addEventListener('scroll', onScroll)