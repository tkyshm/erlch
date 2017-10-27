# erlch

## Install

erlch install to /usr/local/bin:
```
$ git clone https://github.com/tkyshm/erlch.git
$ install -m 0755 bin/erlch /usr/local/bin
```

setting .bashrc or .zshrc:
```
export ERLCH_BIN=$HOME/.erlch/bin
export PATH=$PATH:$ERLCH_BIN
```

If you use zsh shell, you can use completion (need to install `_erlch` into your zsh competions dir).


## Usage
Please check `erlch help` command.

## Example `configure_opts`

- `$HOME/.erlch/configure_opts`
```
--enable-dynamic-ssl-lib
--enable-hipe
--enable-kernel-poll
--enable-shared-zlib
--enable-smp-support
--enable-threads
--enable-vm-probes
--disable-sctp
--with-dynamic-trace=dtrace
--with-wx
--without-javac
--without-odbc
```

## License
MIT License.
