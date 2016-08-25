# SystemJS-glsl-loader-plugin
glsl files loader plugin for SystemJS

###Usage
---

SystemJS config:

```js
SystemJS.config({
	map: {
		glsl: 'src/glsl.js'  // path to glsl.js file
	},
	meta: {
		'_KNOX/*.glsl': {   // for all glsl files on your project
			loader: 'glsl'
		}
	},
	packages: {
		"_KNOX": {  // path to your project root
			"defaultJSExtensions": true
		}
	}
});
```

License
---
My codes, open sourced. Have fun and learn. Licensed under [WTFPL](http://www.wtfpl.net/)
