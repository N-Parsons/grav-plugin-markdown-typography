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

## Features and Usage

### Smart-quotes

Replaces straight quotes ('/") with the appropriate curved quote marks (‘’/“”). You don't need to do anything special to use them!

### Line breaks

While line breaks should be avoided most of the time, there are some times when they are useful, so all you need to do is end your line with `\`.

```markdown
First line\
Second line
```

### Dashes

This provides access to en dash (–) and em dash (—) via `--` and `---`, respectively.

You should use an en dash in number and time ranges, such as `1--2pm`.

Clauses can use either a spaced en dash `--` (eg. "something – clause") or an em dash without spaces `---` (eg. "something—clause"). There's also a shortcut for en dashed clauses, so `--` can be written as `-` instead.

### Ellipsis

Ellipsis is the set of three dots at the end of a sentence that trails off…
So `...` will be converted to "…".

### Interrobang

An interrobang consists of an exclamation point combined with a question mark. This is accessed simply by typing `!?`, which gets converted to "‽".

### Arrows

#### Thin arrows:

- `->`: →
- `-<`: ←
- `-->`: ⟶
- `--<`: ⟵

#### Thick arrows:

- `=>`: ⇨
- `=<`: ⇦
- `==>`: ⇨
- `==<`: ⇦

Note: there's currently only one type of thick arrow.

### Plus-minus

There are two ways to access the plus-minus symbol.

- `+-`: ±
- `+/-`: ±

## License

MIT license. See [LICENSE](LICENSE)
