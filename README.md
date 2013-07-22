cw.single
=========

A single use worker which is created with it's data and imediatly closes itself, not as useful in practice as you'd think.

For use with [communist](http://communistjs.com).

```javascript
cw.single(function,data).then(onSuccess,onErr);
```
