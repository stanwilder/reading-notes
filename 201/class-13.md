# Local Storage

## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

- Cookies can be used to store small amounts of data. There are three downsides to them.
  
  - Cookies are included with every HTTP request, slowing down your web app.
  
  - It sends data unencrtypted over the internet.

  - Limited to about 4 KB of data. Thats enough to slow down your computer but not enough to be useful.

- HTML5 Storage: it’s a way for web pages to store named key/value pairs locally, within the browser. Unlike cookies, its not transmitted to a remote server. 

- Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.
<!-- diveinto.html5doctor.com -->

- 5 megabytes is how much storage space each origin gets by default. 

- Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it.
<!-- diveinto.html5doctor.com -->

- 