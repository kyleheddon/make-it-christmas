make-it-christmas
=================

Javascript bookmarklet that makes isitchrismas.com tell you it is Christmas 

## To make it Christmas

Add a bookmark to your web browser, with this as the url:
  
javascript:window.e=document.getElementById('answer');function r(){e.style.color='red'}function g(){e.style.color='green'}function a(){if(e.style.color!='green') g(); else r()}e.innerHTML='YES';g();window.i=setInterval(a, 500)
