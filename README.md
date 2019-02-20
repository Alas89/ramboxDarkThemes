# Selection Of Dark Theme For Rambox

## Javascript Injection Of A CSS For Rambox

```js
function applycss(css){
    var head = document.getElementsByTagName('head')[0];
    var s = document.createElement('style');
    s.setAttribute('type', 'text/css');
    s.appendChild(document.createTextNode(css));
    head.appendChild(s);
 }
applycss(`
// css from userstyles.org without the @-moz-document wrapper
`);
```

[Original post](https://github.com/ramboxapp/community-edition/issues/107#issuecomment-266862491)

## Threema

## Other Themes

* [Extensions for Rambox services](https://github.com/streetturtle/rambox-extensions/)

## Credit Where Credit Is Due

Last but not least thanks to all the people to the Rambox and theme creation community.

* **javascript:** The javascript code to inject the css is form [skmexyz](https://github.com/skmexyz) on github ([original post](https://github.com/ramboxapp/community-edition/issues/44#issuecomment-250974800)) and clarified by [streetturtle](https://github.com/streetturtle) in this [post](https://github.com/ramboxapp/community-edition/issues/107#issuecomment-266862491).
* **Threema:** The Threema theme is based on [Threema web dark](https://userstyles.org/styles/167878/threema-web-dark) by [Oliver Grosskloss](https://userstyles.org/users/363846).
* **Telegram:** The Telegram theme is based on [Web Telegram Dark](https://userstyles.org/styles/132781/web-telegram-dark) by [Haron Prime](https://userstyles.org/users/325431).
* **Whatsapp:** The Whatsapp theme is based on [Dark Web Whatsapp Theme](https://userstyles.org/styles/152412/dark-web-whatsapp-theme) by [Robin D.](https://userstyles.org/users/562379).