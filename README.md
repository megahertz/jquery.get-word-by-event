GetWordByEvent jQuery plugin
========================

This plugin allow to get the word under cursor

Require: jQuery 1.7+

install
-------
Include jQuery and plugin JavaScript files:
```html
<script type="text/javascript" src="http://code.jquery.com/jquery-1.10.1.min.js"></script>
<script type="text/javascript" src="jquery.get-word-by-event.js"></script>
```

example
-------

```js
$('p').getWordByEvent('click', function(e, word) {
    alert('You have clicked "' + word + '" word')
});
```
