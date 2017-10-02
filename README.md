# eslint-config-bbt-react
ESLint Config for JavaScript used by BlackBird Team


Current React version supported: 15.6.1
## Install
```cmd
npm i -D esling-config-bbt-react
```

## Usage
```eslint
{
	...
	"extends": [ "bbt-react" ]
	...
}
```

## Includes

[eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)

### Settings

```eslint
...
"settings": {
  "react": {
    "pragma": "React",
      "version": "15.6.1"
    }
  }
...
```

## Custom Rules

...