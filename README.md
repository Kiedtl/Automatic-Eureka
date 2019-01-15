# Automatic-Eureka
A piece of JS that automatically adds a balloon onto every &lt;a> element displaying the contents of the href attribute of the &lt;a&gt; tag.
Automatic-Eureka uses `hint.css` for the tooltips. Because of that, users must add a `hint.css` reference to their HTML document.

### Usage
You can call the `automaticEurekaInit` function on documents load like this:
```html
<!-- snip -->
<body onload="automaticEurekaInit();" >
  <!-- blah blah blah -->
</body>
```
See [this page](http://bit.ly/OnKeysAndCrypto) for an example of Automatic Eureka in action.
