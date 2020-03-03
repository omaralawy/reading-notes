# ersistent
ersistent local storage is one of the areas where native client applications have held an advantage over web applications. 
There three potentially dealbreaking downsides:
Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
## Html5 Storage 
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string.
The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string
