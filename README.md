# IMDT V2H SBC Board Support Package

To use this manifest, you must first install the `repo` tool:
```sh
$ mkdir ~/bin
$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$ chmod a+x ~/bin/repo
$ PATH=${PATH}:~/bin
```

To create a working environment for the latest release:
```sh
$ mkdir <working directory>
$ cd <working directory>
$ repo init -u git@github.com:imd-tec/imdt-renesas-manifest.git -b imdt-linux-dunfell -m imdt-v2h-bsp-v1.0.0.xml
$ repo sync
```
