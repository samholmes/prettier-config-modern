# prettier-config-modern

A Prettier [shareable config](https://prettier.io/docs/en/configuration.html#sharing-configurations)
for projects wanting to conform to a modern format.

## Installation

```
npm install --save-dev prettier-config-modern
```

_This is only a shareable configuration. It does not install Prettier._

## Usage

Reference it in `package.json` using the `prettier` property:

```json
{
	"name": "my-projects-name",
	"prettier": "prettier-config-modern",
	"devDependencies": {
		"prettier-config-modern": "^1.0.0"
	}
}
```

If you don't want to use `package.json`, you can use any of the supported
extensions to export a string:

```jsonc
// `.prettierrc.json`
"prettier-config-modern"
```

```javascript
// `prettier.config.js` or `.prettierrc.js`
module.exports = 'prettier-config-modern'
```
