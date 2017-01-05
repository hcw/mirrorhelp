==============================
Homebrew Bottles 源使用帮助
==============================

地址
====

https://mirrors.ustc.edu.cn/homebrew-bottles/

说明
====

Homebrew 预编译二进制软件包


收录仓库
========
* homebrew/homebrew-core
* homebrew/homebrew-dupes
* homebrew/homebrew-games
* homebrew/homebrew-gui
* homebrew/homebrew-python
* homebrew/homebrew-php
* homebrew/homebrew-science
* homebrew/homebrew-versions
* homebrew/homebrew-x11


使用说明
========

请在运行brew前设置环境变量``HOMEBREW_BOTTLE_DOMAIN``，值为 ``https://mirrors.ustc.edu.cn/homebrew-bottles``.

对于bash用户：

::

    echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.ustc.edu.cn/homebrew-bottles' >> ~/.bash_profile
    source ~/.bash_profile

对于zsh用户

::

    echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.ustc.edu.cn/homebrew-bottles' >> ~/.zshrc
    source ~/.zshrc