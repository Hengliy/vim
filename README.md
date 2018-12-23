# vim
the vimrc of hengliy

## 1、安装vim
>     $ sudo apt-get install vim

## 2、配置bundle管理器
>     $ mkdir .vim/bundle
>     $ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

## 2、配置.vimrc
> 复制仓库中的.vimrc文件到~目录
> 打开vim，命令模式下输入 :PluginInstall

## 3、编译配置YouCompleteMe
### 1)安装编译环境
>     $ sudo apt-get install build-essential cmake
>     $ sudo apt-get install python-dev python3-dev

### 2)编译YCM
>     $ cd ~/.vim/bundle/YouCompleteMe/
>     $ python install.py --clang-completer

### 3)配置.ycm_extra_conf.py
> 下载https://github.com/Hengliy/vim 中的.ycm_extra_conf.py(暂只支持C++)放在~/.vim/bundle/目录下

### 4)新建.cpp测试

## 4、安装molokai主题
>     $ git clone https://github.com/tomasr/molokai
将color文件夹放在.vim文件夹内即可

## 5、安装Airline-theme 
> https://github.com/vim-airline/vim-airline-themes 下载并用里面的themes文件夹替换~/.vim/bundle/Airline/autoload/airline/themes文件夹

## 6、安装oh my zsh
> $ sudo apt-get install zsh
> $ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"


