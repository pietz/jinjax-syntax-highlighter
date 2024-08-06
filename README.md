# jinjax-syntax

Syntax Highlighting for JinjaX in VS Code

## Features

[JinjaX](https://jinjax.scaletti.dev/) is an extension to the Jinja templating engine in Python. It adds the use of componenets instead of dealing with the `extends`, `block` and `call` directives.

This is a simple syntax highlighter for VS Code. I've never written one of these before, so I'd assume there are likely some rough edges and things to improve.

Before:
![before](https://raw.githubusercontent.com/pietz/jinjax-syntax/main/before.png)

After:
![after](https://raw.githubusercontent.com/pietz/jinjax-syntax/main/after.png)

Happy to accept PRs!

## Release Notes

Users appreciate release notes as you update your extension.

### 0.0.1

- Initial release
- Support for component tags with PascalCase e.g. `<Headline />`
- Support for component definition header e.g. `{#def name, age=34 #}`
- Support for Python expressions inside double curly braces e.g. `{{ person.name }}`
- Probably still buggy - Happy to accept PRs.