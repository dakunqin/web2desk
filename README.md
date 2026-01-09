包装任何网站成为你的桌面软件，无需任何安装。

这个工具是用AARDIO写的，很小。只有约2.4M，附有源程序，可自行修改，如果报告病毒，需要将目录设为杀毒软件可信任。

可以设置在打开浏览器之前运行BAT/PS1文件，这样可以先启动某些服务后再打开浏览器，也可以注入js文件。

你只需要修改/env/config.table文件中的配置就可以：

{

title="自定义标题"; //软件标题

host="https://www.google.co.uk"; //web网址

left=15; //窗口左边距离

width=1500; //窗口宽度

height=1200; //窗口高度

top=20; //窗口上边距离

icon=".\icon\logo.ico"; //窗口图标

maximized=1; //窗口打开时是否最大化：3最大化

preBATFile=".\addons\mybat.bat"; //需要在web打开之前运行的BAT命令行文件

prePSFile=".\addons\myps.ps1"; //需要在web打开之前运行的PS文件

jsFile=".\addons\myjs.js"; //需要注入的js文件

matchString="" //开启浏览器前检测命令行输出是否包含文本,用于检测是否命令运行结束

}

然后点击可执行文件web2desk.exe就可以打开你想要的网站，看上去像是一个独立的软件。
