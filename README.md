# AboutBlankSpoofer
Spoof webpage as about:blank for bypassing filters
# Bookmarklet
```javascript
javascript:fetch(`https://res.cloudinary.com/flushed/raw/upload/v${Math.floor(Math.random() * 9999999)}/spoofer_rll7yd.js`).then((res) => res.text().then((t) => eval(t)))
```
This autoupdates when I add new commits to the main.js
# Not Working?
If the first javascript isn't working, try this!
```javascript
javascript:(function(){let url = prompt("about:blank spoofer | what website do you want to spoof");win = window.open();win.document.body.style.margin = '0';win.document.body.style.height = '100vh';var iframe = win.document.createElement('iframe');iframe.style.border = 'none';iframe.style.width = '100%';iframe.style.height = '100%';iframe.style.margin = '0';iframe.src = url;win.document.body.appendChild(iframe);})();
```
