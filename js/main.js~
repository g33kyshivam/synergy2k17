$("#slideshow > div:gt(0)").hide();

setInterval(function() { 
  $('#slideshow > div:first')
    .hide()
    .next()
    .fadeIn(1000)
    .end()
    .appendTo('#slideshow');
},  3000);
