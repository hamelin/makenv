# `makenv` -- Minimal Conda environments and Jupyter kernels made quickly

Prepares a Conda environment, with a particular facility towards installing it as a Jupyter kernel.

## Install

```sh
pip install git+https://github.com/hamelin/makenv.git
```

## Usage

Look up `makenv --help`.

The script puts a default environment file at `$HOME/.config/prepenv/environment.yml`, to which the script's help dump refers as the *fallback environment*.
It can be edited as fashions come and go.
The script will also latch onto the `environment.yml` file in the current directory if it exists.
Specifying an alternative file with the `-e` option can trump this, as would using option `-F` to force usage of the fallback environment.
