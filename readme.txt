一 vim配置脚本
包管理器VundleVim下载地址 https://github.com/VundleVim/Vundle.vim
1. git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
2. 在vim输入PluginInstall


二 代码格式化工具下载地址
https://sourceforge.net/projects/astyle/
脚本文件astyle.bat，首次使用需要修改软件路径，记事本打开修改即可
                        其他软件配置参数
MDK        //单个文件         
command     D:\Program Files\AStyle\bin\AStyle.exe
arguments   --style=allman -k3 -W1 -xG -S -s4 -xb -U -p -xf -xh -xC120 -xL -H -Y -xW -w -n !E  

source insight    
run         "D:\Program Files (x86)\Source Insight 4.0\AStyle\bin\AStyle.exe" --style=allman -k3 -W1 -xG -S -s4 -xb -U -p -xf -xh -xC120 -xL -H -Y -xW -w -n %f
