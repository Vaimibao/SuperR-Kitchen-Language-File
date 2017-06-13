# SuperR-Kitchen-Language-File
# 所有汉化均由曦颜XY独立完成

# 原作者：SuperR

# 修订版本：Beta1.1.0_17.4.16
汉化SuperR厨房的语言文件：替换位置/tools/language/

如有汉化建议请联系本人微博：曦顏XY
所有版权归SuperR拥有/Copyright is owned by SuperR

厨房XDA链接：https://forum.xda-developers.com/apps/superr-kitchen/kitchen-superr-s-kitchen-v1-1-50-v2-1-6-t3597434

# 同步安装SuperR Kitchen

Open your terminal to the location where you want the kitchen to reside. Enter the following commands one by one pressing ENTER after each line.（先创建一个你想放厨房的空文件夹，然后根据Linux不同输不同命令）

First：

You must have git-lfs installed. Follow the appropriate instructions below.（必须安装git-lfs，看下面）

1. Ubuntu and Debian based systems:

   Code:

       $  curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash

       $  sudo apt-get install git-lfs

       $  git lfs install

       $  git config --global credential.helper cache

2. Other Linux: 
   Download and install from https://github.com/git-lfs/git-lfs/releases

       Code:

       $  git lfs install

NEXT：

   Clone and run(下载代码并运行):

       Code:

       $  mkdir ~/SuperR-Kitchen

       $  cd ~/SuperR-Kitchen

       $  git clone https://bitbucket.org/superr/superrs-kitchen.git

       然后替换语言文件

       $  cd superrs-kitchen

       $  ./superr

当然如果你想简单粗暴下载厨房，请转下载厨房打包好的zip，替换中文文件：
Link/链接：http://srk.ddayweb.com/

# 注意Deepin Linux用的有问题

解决办法：

      1. 编辑/tools/dependencies 删除getcap 

      2. 同时superr文件里搜索getcap替换为cp

# 捐赠版本详情见XDA原帖
