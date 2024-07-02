# Termux-Settings

This repository contains configuration and personalization files for the Termux application on my device.

## .bashrc

This file contains aliases of several Termux basic commands.

Please move this file into `/data/data/com.termux/files/home` directory with this command:

```Shell
~ $ mv .bashrc /data/data/com.termux/files/home
```

## bash.bashrc

This file contains the configuration of the main prompt display in the terminal (line 15).

```Shell
15. PS1='\[\e[1;36m\]\w\[\e[0m\] \[\e[1;37m\]\$\[\e[0m\] '
```

Please move this file into `/data/data/com.termux/files/usr/etc` directory with this command:

```Shell
~ $ mv bash.bashrc /data/data/com.termux/files/usr/etc
```

## termux.properties

This file is used to configure various terminal environment settings and behavior.

Please move this file into `/data/data/com.termux/files/home/.termux` directory with this command:

```Shell
~ $ mv termux.properties /data/data/com.termux/files/home/.termux/
```

---

Updated on: Tuesday, July 02, 2024 at 19:24:25 GMT +7