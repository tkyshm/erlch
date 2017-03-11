# erlenv

## Install

erlenv install to /usr/local/bin:
```
$ git clone https://github.com/tkyshm/erlenv.git
$ install -m 0755 bin/erlenv /usr/local/bin
```

setting .bashrc or .zshrc:
```
export ERLENV_BIN=$HOME/.erlenv/bin
export PATH=$PATH:$ERLENV_BIN
```

If you use zsh shell, you can use completion (need to install `_erlenv` into your zsh competions dir).


## Usage
Please check `erlenv help` command.

## License
MIT License.
