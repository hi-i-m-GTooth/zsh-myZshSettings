# zsh-myZshSettings
## Installation (Ubuntu 18.04.4 LTS)
  * 1. Update & Upgrade for apt
  ```shell
  $ sudo apt-get update   
  $ sudo apt-get upgade
  ```
  * 2. Install ZShell
  ```shell
  $ sudo apt-get install zsh
  ```
  * 3. Install Oh-My-Zsh
  ```shell
  # via curl
  $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  # via wget
  $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
  ```
  * 4. Set Path
  ```shell
  $ export $ZSH = $HOME/.oh-my-zsh
  ```
  
## My Plugins
  * *(default)* git
  * zsh-autosuggestions
  * zsh-syntax-highlighting
  * autojump   
     
  After adding new plugins, don't forget to run ```$ source /.zshrc```.
## My Theme
  * *(for WSL)* powerline/fonts (install & change default font)
    * https://github.com/powerline/fonts
  * *(edited for speedup)* agnoster   
     
  After changing themes, don't forget to change ```ZSH_THEME``` in ```.zshrc```.
## Reference
  * https://blog.xuite.net/chingwei/blog/28082882-%E3%80%90%E7%B3%BB%E7%B5%B1%E3%80%91Ubuntu+%3A+%E6%9F%A5%E7%9C%8B%E7%B3%BB%E7%B5%B1%E8%B3%87%E8%A8%8A+by+Command
