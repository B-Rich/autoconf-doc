# Readme for autoconf

## acconfig.h

```
 configure.ac --.   .------> autoconf* -----> configure
                +---+
 [aclocal.m4] --+   `---.
 [acsite.m4] ---'       |
                        +--> [autoheader*] -> [config.h.in]
 [acconfig.h] ----.     |
                  +-----'
 [config.h.top] --+
 [config.h.bot] --'
```

