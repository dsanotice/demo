# dsanotice.com demo

This is a demo of how dsanotice.com can be integrated on a photo sharing platform to fight illigal content and make this platform compliant with Digital Services Act


> Live demo may be found at https://dsanotice.com/demo.html


## 1. Client script

Add this script to end of the `body` tag on your platform

```html
    <script src="https://dsanotice.com/client.js"></script>
```


## 2. Add Report buttons

Add any number of report buttons (CSS class `dsanotice`) on your platform pages.


```html
<span class="dsanotice">Report this post</span>
```


## 3. Content data

Provide additional `data-dsacontenturl`, `data-dsacontentimg` and `data-dsacontenttxt` attributes to the buttons


```html
<span class="dsanotice" 
            data-dsacontenturl="https://domain/post/42"
            data-dsacontentimg="https://domain/static/42.jpg"
            data-dsacontenttxt="Post text">
        Report this post
</span>
```
