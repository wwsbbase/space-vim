# space-vim

         ___ _ __   __ _  ___ ___     __   _(_)_ __ ___
         / __| -_ \ / _- |/ __/ _ \____\ \ / / | -_ - _ \ 
         \__ \ |_) | (_| | (_|  __/_____\ V /| | | | | | |
         |___/ .__/ \__._|\___\___|      \_/ |_|_| |_| |_|
             |_|


[space-vim](https://github.com/liuchengxu/space-vim) is a vim distribution inspired by [spacemacs](https://github.com/syl20bnr/spacemacs), especially in key bindings.

I use both spacemacs and vim everyday and hope they maintain consistency in operation as far as possible.
Hence it is fruitful to those who use spacemacs and vim at the same time as well as vim beginer.

The distribution is customisable using a `~/.vimrc.local` and `~/.vimrc.plug.local` Vim RC files.

It has also learned a great deal from other first-class vim configurations, such as [spf13-vim](https://github.com/spf13/spf13-vim).
Thanks for their outstanding works.

Screenshots:

- ubuntu

![ubuntu](doc/img/ubuntu.png)

- macOS

![screenshot](doc/img/screenshot.png)


## [中文指南](doc/tutorial_cn.md)

## Installation

You need to statisfy some prerequisites to make all the plugins work, especially vim complied with certain features, such as python, and some other tools used by related plugins. [Here is a recommended list](doc/tutorial_cn.md#prerequisites).

For linux and macOS, it is easy to install space-vim with curl or wget.

- curl

  ```
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/liuchengxu/space-vim/master/install.sh)"
  ```

- wget

  ```
  sh -c "$(wget -qO- https://raw.githubusercontent.com/liuchengxu/space-vim/master/install.sh)"
  ```

## How to use

If you are just starting to use vim, refer to [中文指南](doc/tutorial_cn.md) for some tips.

If you have been a vimer for a while, refer to the `vimrc` related files directly.

## Updating to the latest version

You can manually perform the following steps, or completely reinstall space-vim, which is more easier and safer.

```
cd ~/.space-vim
git pull
vim +PluginInstall! +PluginClean +q
```

## TODO

[space-vim](https://github.com/liuchengxu/space-vim) is a work in progress, so any ideas and patches are appreciated.

- Windows compatibility.