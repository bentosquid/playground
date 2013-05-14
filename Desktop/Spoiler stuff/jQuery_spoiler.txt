$(document).ready(function(){
    $("button").toggle(
      function(){
          $(".spoilerParts").css({opacity : 1});},
      function(){
          $(".spoilerParts").css({opacity : .03});
  });
});