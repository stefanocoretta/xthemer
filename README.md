# Revealjs themes based on xaringanthemer

This Quarto extension provides users with themes for revealjs presentations based on [xarignanthemer](https://pkg.garrickadenbuie.com/xaringanthemer/index.html).

## Installing

```bash
quarto add stefanocoretta/xthemer
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

As of now, only the mono themese are available.

```yaml
---
format: mono-light-revealjs
# format: mono-dark-revealjs
# format: mono-accent-revealjs
# format: mono-accent-inverse-revealjs
---
```

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

