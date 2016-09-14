# eslint-config-ivantage

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) for the iVantage.


## Install

```
$ npm install --save-dev eslint eslint-config-ivantage
```


## Usage

Tell ESLint you want to extend the iVantage rules in your ESLint config or
package.json:

```json
{
	"scripts": {
		"lint": "eslint ."
	},
	"devDependencies": {
		"eslint": "^3.5.0",
		"eslint-config-ivantage": "^0.1.0"
	},
	"eslintConfig": {
		"extends": "ivantage"
	}
}
```

Then lint with `$ npm run lint`.


## License

MIT
