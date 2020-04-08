

## cookeis the begingin of Localstorage


- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


### html Local storage
- allows for stuf to be stored localy 
- every broser suports it 
- setItem() it is done by key pairs
-  window object whenever 
- setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, 
- the storage event will not fire, because nothing actually changed in the storage area.
### calls changes

- IndexedDB is the futer 