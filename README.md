# AboutBlankSpoofer
Spoof webpage as about:blank for bypassing filters
# Bookmarklet
```javascript
javascript:(function()%7Blet%20url%20%3D%20prompt(%22about%3Ablank%20spoofer%20%7C%20what%20website%20do%20you%20want%20to%20spoof%22)%3B%0A%0Awin%20%3D%20window.open()%3B%0Awin.document.body.style.margin%20%3D%20'0'%3B%0Awin.document.body.style.height%20%3D%20'100vh'%3B%0Avar%20iframe%20%3D%20win.document.createElement('iframe')%3B%0Aiframe.style.border%20%3D%20'none'%3B%0Aiframe.style.width%20%3D%20'100%25'%3B%0Aiframe.style.height%20%3D%20'100%25'%3B%0Aiframe.style.margin%20%3D%20'0'%3B%0Aiframe.src%20%3D%20url%3B%0Awin.document.body.appendChild(iframe)%3B%7D)()%3B
```
