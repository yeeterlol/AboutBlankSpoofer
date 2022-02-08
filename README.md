# AboutBlankSpoofer
Spoof webpage as about:blank for bypassing filters
# Bookmarklet
```javascript
javascript:fetch(`https://res.cloudinary.com/flushed/raw/upload/v${Math.floor(Math.random() * 9999999)}/spoofer_rll7yd.js`).then((res) => res.text().then((t) => eval(t)))
```
