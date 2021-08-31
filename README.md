[![Discord](https://img.shields.io/discord/881535801807224862.svg?color=768AD4&label=discord&logo=https%3A%2F%2Fdiscordapp.com%2Fassets%2F8c9701b98ad4372b58f13fd9f65f966e.svg)](https://discord.gg/kW2crCYuDF)
# IC

Ic is a repl for C and tries to make something like Ipython, but Ic is not a copy of Ipython but something like that, and [probably] its graphical environment is used in Ic.

Contents
--------

* [How the compile Ic](#How-the-compile-Ic)
    - [Install Prerequarments](#Install-Prerequarments)
    - [Configuration](#Configuration)
    - [Make](#Make)

How the compile Ic
--------

Install Prerequarments
--------

* Install "python" (version >= 3.8) and "pip"
* Install "C compiler" (gcc, clang, etc.)
* Install "make", "autoconf" and "automake"(You can install this on your operating system with the following commands.)

**Arch**

```sh
sudo pacman -S base-devel
```

**Debian/Ubuntu and bases(Kali, Mint, etc.)**

```sh
sudo apt install build-essential
```

**Fedora**

```sh
sudo dnf install build-essential
```

Install Requirements
--------

* python Requirements

> __**note:**__ Better for install python packages is You Are Use Virtual Environments  (virtualenv, etc.)

```sh
pip install -r requirements.txt
```

Configuration
--------

```sh
autoconf
```

```sh
./configuration
```

Make
--------

```sh
make
```

> Of course, to speed up compilation, you can use the following command to compile 4 cores (or more by changing the number)

```sh
make -j4
```
