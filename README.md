# Sass Project
- Example of using sass to compile scss style into css file.
- Minify css to reduce file size.
- Example of watch for file change.
- Example of build production files.
```
"scripts": {
		"compile": "sass scss/style.scss public_html/css/style.css && echo Compile terminated",
		"xcss": "uglifycss public_html/css/style.css > public_html/css/style.min.css && echo Minify CSS terminated",
		"watch": "sass --watch scss/style.scss public_html/css/style.css",
		"dev": "npm run compile && npm run xcss"
	},
```
