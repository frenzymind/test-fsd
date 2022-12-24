# eslint-plugin-test-fsd

trany

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-test-fsd`:

```sh
npm install eslint-plugin-test-fsd --save-dev
```

## Usage

Add `test-fsd` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "test-fsd"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "test-fsd/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here


