# goda-cmp-ui-pum.vim

The UI `pum` of [goda-cmp.vim](https://github.com/Shougo/goda-cmp.vim):
the popup of [pum.vim](https://github.com/Shougo/pum.vim), in insert mode, on the command line and in a terminal (ddc-ui-pum).

## Requirements

- [goda-cmp.vim](https://github.com/Shougo/goda-cmp.vim)
- [pum.vim](https://github.com/Shougo/pum.vim)

## Usage

Add it in the configuration of goda-cmp.vim:

```go
import "github.com/Shougo/goda-cmp-ui-pum.vim/ext/ui/pum"

b.AddUI(pum.New())
b.PatchGlobal(cmp.Config{UI: "pum"})
```

See `:help goda-cmp-ui-pum`.
