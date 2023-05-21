# wangEditor server

用于测试wangEditor编辑器的图片上传、视频上传等，也可当作其他项目的文件服务器使用
需要服务端配合的功能。需下载到本地运行。

## 环境要求

本机需要安装

- nodejs （v12 版本及以上）

## 本地运行

运行

- 下载[源码](https://github.com/wangeditor-team/server)到本地
- 打开控制台，进入 server 文件夹
- 运行 `npm install` 安装插件
- 运行 `npm run dev` 启动本地服务

测试

- 上传图片 http://127.0.0.1:3000/html/upload-image.html
- 上传视频 http://127.0.0.1:3000/html/upload-video.html

访问路径
- http://127.0.0.1:3000/upload-files/avatar-f18.png

## 相关文档

- [上传图片配置](https://www.wangeditor.com/v5/menu-config.html#上传图片)
- [上传视频配置](https://www.wangeditor.com/v5/menu-config.html#上传视频)
- [视频教程](https://www.wangeditor.com/v5/video-course.html)

## 提交问题

- [提交 issue](https://github.com/wangeditor-team/wangEditor/issues)
