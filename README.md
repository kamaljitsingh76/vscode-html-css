# Visual Studio Code CSS Support for HTML Documents

Missing CSS support for HTML documents.

## Features

- Html class attribute completion.
- Supports `<link rel="stylesheet">` and `<style></style>` tags.
- Supports other remote style sheets, see below.
- Local workspace parsing for css files is deprecated.

## Remote Style Sheets

If it is not possible to specify remote styles with `<link rel="stylesheet">` tag, they can be specified in VS Code settings:

```json
"css.remoteStyleSheets": [
  "https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css"
]
```

## Supported Languages

Supported languages can be configured with the `css.enabledLanguages` configuration setting. By
default "html" is enabled:

```json
"css.enabledLanguages": [
  "html"
]
```

Some languages are listed below:

`django-html` `laravel-blade` `razor` `vue` `blade` `pug` `jade` `handlebars` `php` `twig` 
`md` `nunjucks` `javascriptreact` `erb` `typescriptreact` `HTML (Eex)` `html-eex` `haml` `svelte`

## Installation

[Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)

## Usage

You can view a list of class attributes via `ctrl + space`.
