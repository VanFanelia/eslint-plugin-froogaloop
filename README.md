# eslint-plugin-froogaloop

eslint plugin for froogaloop video player

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-froogaloop`:

```
$ npm install eslint-plugin-froogaloop --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-froogaloop` globally.

## Usage

Add `froogaloop` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "froogaloop"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "froogaloop/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





