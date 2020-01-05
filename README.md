# [fish-history-merge][]

[fish-history-merge]:        https://github.com/2m/fish-history-merge

This is a [fish](https://fishshell.com) plugin that modifies built-in `up-or-search` command to merge the command history.
The effect is that shell command history becomes shared across all open shells.
Original implementations by @farcaller from https://github.com/fish-shell/fish-shell/issues/825#issuecomment-440286038

## Instalation

If using [fundle](https://github.com/danhper/fundle) add the following to `~/.config/fish/config.fish` before `fundle init`:

```fish
fundle plugin '2m/fish-history-merge'
```

then reload fish shell and then run `fundle install`.

If using [fisher](https://github.com/jorgebucaran/fisher) run `fisher add 2m/fish-history-merge`.
