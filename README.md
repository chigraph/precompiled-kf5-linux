# precompiled-kf5-linux
Precompiled KDE frameworks 5 for linux

A bunch of scripts for generating precompiled KF5 tarballs/directories

# build_frameworks.sh
Generates a tar.XX file and/or a directory with KF5 installed in it. Example:

```bash
./build_frameworks.sh -i ~/my-kf5-install -g Ninja -t Debug -o ~/my-kf5-tarball.tar.xz
```
