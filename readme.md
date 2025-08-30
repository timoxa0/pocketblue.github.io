### pocketblue flatpak repo

```shell
sudo flatpak remote-add pocketblue https://pocketblue.github.io/pocketblue.flatpakrepo
```

### list available apps

```shell
flatpak remote-ls pocketblue
```

this command will list apps:

```shell
io.github.pocketblue.handyfox
org.mozilla.firefox.systemconfig
```

### install app

```shell
flatpak install pocketblue io.github.pocketblue.handyfox
flatpak install pocketblue org.mozilla.firefox.systemconfig
```

### manifests

- https://github.com/pocketblue/handyfox
- https://github.com/pocketblue/firefox-systemconfig

