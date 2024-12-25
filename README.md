# srv00-vless

在 Serv00 免费托管网站上部署 vless 节点

## 部署教程
用编辑器打开 index.js 文件，修改第 7 行和第 8 行画红圈的位置。第 7 行修改为自己的 UUID，第 8 行修改为放行分配的端口号

待更新打开 start.sh 文件，然后在第 2 行和第 3 行修改哪吒面板的登陆地址、端口号和通信密钥

将 index.js、start.sh 和 package.json 上传至 domains/你的域名 文件夹中

打开 SSH 终端，输入以下命令运行代码程序，如出现节点信息即可代表运行成功

cd domains/你的域名 && npm install ws && screen node index.js

## 免责声明

* 本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责.

## 赞助

爱发电：https://afdian.net/a/Misaka-blog

![afdian-MisakaNo の 小破站](https://user-images.githubusercontent.com/122191366/211533469-351009fb-9ae8-4601-992a-abbf54665b68.jpg)
