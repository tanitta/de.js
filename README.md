# de.js

[![npm version][npm-badge]][npm-badge-url]
[![License][license-badge]][license-badge-url]

de.js contribute at DataFlow EventDriven Multi Paradime Javascript thinking about Functional Programing.

## de.js is very friendly of OOP

### Sample code

~~~javascript
let MyButton = function () {
    this
    ._({
        Alice: "Who are you ?",
        CheshireCat: "I not interested about you."
    })
    ._(button.$("Push Me"))
    .on("click");
}._({
    click (e) {
        this.each((v, k) => e.$.outer.$(p.$(k + ": " + v)));
    }
});
$.body.$(article.$(new MyButton()));
~~~

You can Connect on webRTC;
~~~javascript
let pvp = new PvP((e) => window.talk = e.$);
~~~
Let's hack it!

# reference

https://github.com/johnny-shaman/de.js/wiki

GNU Public License v3


[npm-badge]: https://badge.fury.io/js/de.js.svg
[npm-badge-url]: https://www.npmjs.com/package/de.js
[license-badge]: https://img.shields.io/badge/License-GPL%20v3-blue.svg
[license-badge-url]: ./LICENSE
