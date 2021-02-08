# Welcome to the Splitwise API!

This repo powers the official documentation for the Splitwise API. You can view our official API documentation website at [http://dev.splitwise.com](http://dev.splitwise.com).

## Questions? Issues?

If something in the API is confusing you, you can open an [issue](https://github.com/splitwise/api-docs/issues) about it on GitHub. We're a small team, so we may not have an instant fix, but we'll get back to you as soon as we're able.

If you spot an issue in our API documentation itself, feel free to open a [pull request](https://github.com/splitwise/api-docs/pulls) to update this repo! Most of the relevant files live in the [/source/includes](https://github.com/splitwise/api-docs/tree/master/source/includes) directory.

## Powered by OpenAPI + redocly

These API docs follow the [OpenAPI v3](https://swagger.io/specification/) specification. The website is built with [redoc](https://github.com/Redocly/redoc).

### Developing
```
$ npm install -g redoc-cli
$ redoc-cli serve splitwise.yaml --watch
```

### Compiling
This will create a zero-dependency HTML file at docs/index.html.

```
$ redoc-cli bundle splitwise.yaml -o docs/
```
