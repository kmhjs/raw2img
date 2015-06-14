# raw2img

Raw image format to typical image format command wrapper

## Requirements

This script requires following tools.

* Netpbm [http://netpbm.sourceforge.net/](http://netpbm.sourceforge.net/)
    * Internally, this script calls `pnmto<format>` command
* DCRaw [http://www.cybercom.net/~dcoffin/](http://www.cybercom.net/~dcoffin/)

## Usage

This script requires to be used as zsh-plugin.
Write folloing 2 lines in your `.zshrc` (or your preferred configuration file), and replace `<SOMEWHERE>` to your installation path.

```
FPATH=<SOMEWHERE>/raw2img/src:$FPATH
autoload -Uz raw2img
```

## Important

As part of MIT License, `You use AT YOUR OWN RISK`.

## License

MIT License. See `LICENSE`.
