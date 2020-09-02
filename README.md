# swig_cpp

## Dependencies to build

Install the following packages

* cmake, swig, python-dev

```console
foo@bar:~$ apt install cmake swig python-dev
foo
```

Tested on:

```console
foo@bar:~$ cat /etc/os-release 
NAME="Linux Mint"
VERSION="18.1 (Serena)"
ID=linuxmint
ID_LIKE=ubuntu
PRETTY_NAME="Linux Mint 18.1"
VERSION_ID="18.1"
HOME_URL="http://www.linuxmint.com/"
SUPPORT_URL="http://forums.linuxmint.com/"
BUG_REPORT_URL="http://bugs.launchpad.net/linuxmint/"
VERSION_CODENAME=serena
UBUNTU_CODENAME=xenial
```

## How to build

Standard cmake build instructions. On the root folder of the project:

```console
foo@bar:~$ mkdir build
foo@bar:~$ cd build
foo@bar:~$ cmake ..
foo@bar:~$ cmake --build .
```

To rebuild, either remove CMakeCache.txt inside the build folder, or remove the entire build folder, and recreate it.
