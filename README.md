# tmux-snazzy

> A [tmux](https://github.com/tmux/tmux/wiki) theme with bright colors. Based on [hyper-snazzy](https://github.com/sindresorhus/hyper-snazzy/) by [Sindre Sorhus](https://sindresorhus.com).

TODO: screen

## Install

Download this file and place it alongside your kitty config file.

```
$ curl -o ~/tmux-snazzy.theme.conf https://raw.githubusercontent.com/jaketrent/tmux-snazzy/master/tmux-snazzy.theme.conf
```

Place this line at the bottom of your `.tmux.conf` file:

```
source-file ~/tmux-snazzy.theme.conf
```

## Related

- [iterm2-snazzy](https://github.com/sindresorhus/iterm2-snazzy) - iTerm2 version
- [terminal-snazzy](https://github.com/sindresorhus/terminal-snazzy) - Terminal version
- [konsole-snazzy](https://github.com/miedzinski/konsole-snazzy) - Konsole version
- [vscode-snazzy](https://github.com/Tyriar/vscode-snazzy) - VS Code version
- [emacs-snazzy](https://github.com/weijiangan/emacs-snazzy) - Emacs version
- [termite-snazzy](https://github.com/kbobrowski/termite-snazzy) - Termite version
- [deepin-snazzy](https://github.com/xxczaki/deepin-snazzy) - Linux Deepin terminal version
- [vim-snazzy](https://github.com/connorholyday/vim-snazzy) - Vim version
- [base16-snazzy](https://github.com/h404bi/base16-snazzy-scheme) - Base16 version
- [kitty-snazzy](https://github.com/connorholyday/kitty-snazzy) - Kitty version


## License

MIT © [Jake Trent](https://jaketrent.com)


## Colors Used

Using colortrans.py for 256 colors from https://gist.githubusercontent.com/MicahElliott/719710/raw/73d047f0a3ffc35f0655488547e7f24fa3f04ea6/colortrans.py
myBg
python colortrans.py 24252F
RGB 282a36 -> xterm color approx colour16 (000000)

foregroundColor
python colortrans.py eff0eb
RGB eff0eb -> xterm color approx colour231 (ffffff)

backgroundColor
python colortrans.py 282a36
RGB 282a36 -> xterm color approx colour17 (00005f)

red
python colortrans.py ff5c57
RGB ff5c57 -> xterm color approx colour203 (ff5f5f)

green
python colortrans.py 5af78e
RGB 5af78e -> xterm color approx colour84 (5fff87)

yellow
python colortrans.py f3f99d
RGB f3f99d -> xterm color approx colour229 (ffffaf)

blue
python colortrans.py 57c7ff
RGB 57c7ff -> xterm color approx colour81 (5fd7ff)

magenta
python colortrans.py ff6ac1
RGB ff6ac1 -> xterm color approx colour205 (ff5faf)

cyan
python colortrans.py 9aedfe
RGB 9aedfe -> xterm color approx colour123 (87ffff)
