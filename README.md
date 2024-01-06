# Revealjs themes based on xaringanthemer

This Quarto extension provides users with themes for revealjs presentations based on [xarignanthemer](https://pkg.garrickadenbuie.com/xaringanthemer/index.html).

## Installing

```bash
quarto add stefanocoretta/xthemer
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

As of now, there are only two themes available: the mono-light and mono-dark themes.

```yaml
---
format: mono-light-revealjs
# format: mono-dark-revealjs
---
```

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

