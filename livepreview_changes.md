## Differences from production Live Preview

The live preview gh-pages repo is just static files so the template.css directory must be changed.

`<link rel="stylesheet" type="text/css" href="css/gollum/template.css" />` instead of
`<link rel="stylesheet" type="text/css" href="../css/template.css" />`

css/gollum/template.css has been modified to use a local png.

```
.markdown-body hr {
  background: transparent url('../../extra/dirty-shade.png') repeat-x 0 0;
```
