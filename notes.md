The following converts to 'a\nb' in source view which becomes 'a b' in html view.

```javascript
wysi.setValue('<p>a</p><br><p>b</p>');
```

Default markup in wysihtml5 for the above is:

```javascript
<span>a<br>
b</span>
```

---

wysihtml5-0.3.0.js modification.

```javascript
fromComposerToTextarea: function(shouldParseHtml) {
  // use html exactly as is.
  this.textarea.setValue(this.composer.getValue().trim(), false);
},
```
