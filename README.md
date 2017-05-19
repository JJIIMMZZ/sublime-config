# 同步我的Sublime 配置

Package Control.sublime-settings ：已安装的插件包  
Preferences.sublime-settings ：自定义设置
  
官方同步操作说明：
https://packagecontrol.io/docs/syncing#git
  
- **Sublime配置文件夹位置**  
选择菜单 Preference -> Browse Packages 打开，进入User 文件夹。  

- **打开git输入**
```
git clone git://github.com/JJIIMMZZ/sublime-config
mv sublime-config/* .
rm -rf sublime-config
```
注意 mv 最后面有空格和一个点。  
平时慎用 `rm -rf` 命令，容易误删文件。  
  
- **Sublime安装 Package Control**  

安装插件包的时候容易被墙，最好打开VPN。  
到 https://packagecontrol.io/installation 复制至控制台(Ctrl + \` )，这样所有插件包会自动安装。
