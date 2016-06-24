# Moneyplex Debian Packaging


## BUILDING


* Run `make deb` to build the Debian package in `out/`

## TODO


* Set proper deb dependencies, find required packages with `dpkg -S $(ldd moneyplex/moneyplex  | sed -n -e 's/.* \(\/.*so..\).*/\1/p')`

## LICENSE

The ccript code is licensed under the Apache Public License, see `LICENSE.txt` for full license text.

The icon is provided by [Matrica](http://matrica.de/) and may be used only in context of packaging Moneyplex.
