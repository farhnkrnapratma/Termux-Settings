# Termux-Settings

This repository contains configuration and personalization files for the Termux application on my device.

Clone this repository with the command below.

```Shell
gh repo clone farhnkrnapratma/Termux-Settings
```
or
```Shell
git clone https://github.com/farhnkrnapratma/Termux-Settings.git
```

## .bashrc

This file contains aliases of several Termux basic commands.

Please copy this file to `/data/data/com.termux/files/home` with this command:

```Shell
cp .bashrc /data/data/com.termux/files/home
```

## bash.bashrc

This file contains the configuration of the main prompt display in the terminal (line 15).

```Shell
15. PS1='\[\e[1;36m\]\w\[\e[0m\] \[\e[1;37m\]\$\[\e[0m\] '
```

Please copy this file to `/data/data/com.termux/files/usr/etc` with this command:

```Shell
cp bash.bashrc /data/data/com.termux/files/usr/etc
```

## termux.properties

This file is used to configure various terminal environment settings and behavior.

Please copy this file to `/data/data/com.termux/files/home/.termux` with this command:

```Shell
cp termux.properties /data/data/com.termux/files/home/.termux/
```

After the file is successfully copied, run the command below to reload the default settings that have been changed.

```Shell
termux-reload-settings
```

And the final step, please end all Termux sessions via the "exit" button in the notification or via the command below.

```Shell
logout
```

---

Updated on: Wednesday, July 03, 2024 at 14:26:50 GMT +7