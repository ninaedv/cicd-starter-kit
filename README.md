# CI/CD Starter Kit

## Necessary config files

### `public/staticwebapp.config.json`

```js
{
	"navigationFallback": {
		"rewrite": "/index.html",
		"exclude": ["/img/*.{png,jpg,gif,webp}", "/css/*"]
	},
	"mimeTypes": { ".json": "text/json" }
}
```
