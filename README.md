# Nord Polybar

A [Nord theme](https://www.nordtheme.com/) port for [Polybar](https://github.com/polybar/polybar/).

## Usage

Copy [`nord.ini`](https://raw.githubusercontent.com/mgred/nord-polybar/main/nord.ini) to your Polybar config files.

```ini
include-file = nord.ini

[bar/mybar]
background = ${color.nord0}
foreground = ${color.nord4}
```

**Note**: Including files by relative path is only possible since Polybar version `3.6.0`.
See the [Polybar Wiki](https://github.com/polybar/polybar/wiki/Configuration#file-inclusion) for more information.

## Additional Links

* [Nord](https://github.com/arcticicestudio/nord) on Github

## License

MIT
