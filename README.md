# Stremio 
is a modern media center.

Movies, TV shows, live TV or web channels - find all this on Stremio.

Slackbuild script build stremio in /opt directory,
and install a stremio.desktop entry.
You can run stremio from menu or from terminal
```
/opt/stremio-shell/build/stremio &
```
or create an alias in your ~/.bashrc
```
alias stremio='/opt/stremio-shell/build/stremio &'
```
or create a bash file named stremio in /usr/local/bin/
```
#!/bin/bash
/opt/stremio-shell/build/stremio &
```
and dont forget to make it executable
```
chmod +x /opt/stremio-shell/build/stremio
```

### Install
Download zip file and extract
Make executable stremio.Slackbuild
and as root command
```
./stremio.SlackBuild
```
### Deps
Deps are in the info file...
