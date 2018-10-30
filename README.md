# babel-preset-escalade

A Babel preset used at Escalade Sports for transforming JavaScript.

## Install

With npm:

```bash
npm install --save-dev babel-preset-escalade
```

Or with Yarn:

```bash
yarn add --dev babel-preset-escalade
```

## Usage

**.babelrc**

```json
{
  "presets": ["escalade"]
}
```

## Targeting

By default, this preset targets the following browsers:

```json
{
	"android": 30,
	"chrome": 35,
	"edge": 14,
	"explorer": 9,
	"firefox": 52,
	"safari": 8,
	"ucandroid": 1
}
```

You can override this with the `targets` option:

```json
{
  "presets": [
    ["escalade", {
      "targets": {
        "node": 8
      }
    }]
  ]
}
```