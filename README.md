# IMDT Renesas EVK Board Support Package

To use this manifest, you must first install the `repo` tool:
```sh
$ mkdir ~/bin
$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$ chmod a+x ~/bin/repo
$ PATH=${PATH}:~/bin
```

To create a working environment for development work:
```sh
$ mkdir <working directory>
$ cd <working directory>
$ repo init -u git@github.com:imd-tec/imdt-renesas-manifest-dev.git -b imdt-linux-dunfell -m development.xml
$ repo sync
```
