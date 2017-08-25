---
layout: post
title:  "Remove a class of a element"
date:   2017-08-25
categories: DOM manipulation
---
Remove a class of a element.

```javascript
function removeClass (el, c) {
  if (el.classList) {
    el.classList.remove(c);
  } else {
    el.className = el.className.replace(c,'').replace(/^\s+|\s+$/g,'');
  }
}
```

File all bugs/feature requests at [GitHub repo][nativejsissexy-gh].

[nativejsissexy-gh]:   https://github.com/dabeng/native-js-is-sexy
