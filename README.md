# Grav Markdown Typography Plugin

The **Markdown Typography plugin** for [Grav](http://github.com/getgrav/grav) enables substitution of typographic characters during Markdown processing.

## Installation

### GPM (preferred method)

You can install the plugin by running `bin/gpm install markdown-typography` or searching for `markdown-typography` in the Admin Panel.

### Manual installation

Alternatively, you can download the zip version of this repository, unzip to `/your/site/grav/user/plugins` and rename the directory to `markdown-typography`.

## Configuration

The `markdown-typography.yaml` file contains several configuration options which allow each typographic substitution to be disabled.

```yaml
enabled: true
smart_quotes: true
line_breaks: true
dashes: true
ellipsis: true
interrobang: true
arrows: true
plus_minus: true
```

## License

MIT license. See [LICENSE](LICENSE)
