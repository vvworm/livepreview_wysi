The following converts to 'a\nb' in source view which becomes 'a b' in html view.

```javascript
wysi.setValue('<p>a</p><br><p>b</p>');
```

Default markup in wysihtml5 for the above is:

```javascript
<span>a<br>
b</span>
```
