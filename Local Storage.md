## what is HTML5 Storage?:
it’s a way for web pages to store named key/value pairs locally, within the client web browser. 
Like cookies, this data persists even after you navigate away from the web site, close your browser tab, 
exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server 
(unless you go out of your way to send it manually).

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. 
The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};

## Tracking Changes to the HTML5 Storage Area:
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. 
The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. 
For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, 
because nothing actually changed in the storage area. 

## Beyond Named Key-Value Pairs: Competing Visions:
While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. 
A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, 
that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” 
and the future of persistent local storage is… how shall I put it… well, there are competing visions. 
