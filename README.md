# Markdown Editor webcomponent
----

Baasic markdown editor with preview, based on the work by Nicolas Chaulet.

## Instalation

With bower

```shell
bower install baasic-markdowneditor
```

## Usage 

In your head include component and platform.js
```html
<head>
	<script src="bower_components/platform/platform.js"></script>
	<link rel="import" href="bower_components/baasic-markdowneditor/baasic-markdowneditor.html" />
</head>
```

Then use components
```html
<baasic-markdowneditor id="editor">
# Title

`var editorValue = document.getElementById('editor').value;`

</baasic-markdowneditor>
```
