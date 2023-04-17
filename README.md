# prepenv

Prepares a standard environment from which to peruse Jupyter notebooks, typically for data scientific purposes.

## Install

```sh
pip install git+https://github.com/hamelin/prepenv.git
```

## Usage

Look up `prepenv --help`.

The script puts a default environment file at `$HOME/.config/prepenv/environment.yml`, to which the script's help dump refers as the *fallback environment*.
It can be edited as fashions come and go.
The script will also latch onto the `environment.yml` file in the current directory if it exists.
Specifying an alternative file with the `-e` option can trump this, as would using option `-F` to force usage of the fallback environment.
