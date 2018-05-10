# Sublime-Text
To sync Sublime Text 3 Settings and Package


## 同步规则
    不要同步 Packages 和 Installed Packages，不同平台内容不同；
    同步 Packages/User/ 即可，该文件夹里面有 Package Control.sublime-settings 文件，它会帮你做好未装插件的安装工作；


## 同步方式
    将$AppData$/Roaming/Sublime Text/Package/User目录替换为git里的内容