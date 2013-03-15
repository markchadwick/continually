# NAME
**continually** - command...

# DESCRIPTION
Contually run a single command every time any file in the current directory
changes. At present, no arguments are obeyed. All files types are watched in the
current directory, and all arguments given to `continually` are run as a
stand-alone command.  [clear(1)](http://linux.die.net/man/1/clear) is called
before every invocation.

# DEPENDENCIES
[inotify-tools](https://github.com/rvoicilas/inotify-tools/wiki) must be
installed, namely `inotify-wait`.
