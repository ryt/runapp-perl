> :atom: Note: An improved python version of this project is available at [ryt/runapp](https://github.com/ryt/runapp) with a better CLI interface.

# runapp-perl

Perl-based command line helper for gunicorn app processes/daemons.

Instructions:

1. Make `runapp.pl` executable & create a symbolic link to it in the app directory:

```
$ chmod +x runapp.pl
$ ln -s ../runapp.pl runapp
```

2. Configure app settings in runapp.conf file.

```
$ vi runapp.conf
$ { appname => hello } etc...
```

3. Create a "pids" directory:

```
$ mkdir pids
```

Usage:

```
./runapp start
./runapp stop
./runapp restart
./runapp reload
./runapp list
./runapp
```
