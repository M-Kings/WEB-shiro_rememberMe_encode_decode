# WEB-shiro_rememberMe_encode_decode 在线加解密工具

# 工具简述

本项目为 shiro rememberMe 在线加解密工具（WEB）

在线体验地址：https://simolin.cn/tools/shiro

可以使用本工具：

- shiro rememberMe encode 加密
  - 支持 shiro 常见 100 key
  - 支持 ysoserial CommonsBeanutils1、CommonsCollections 1-10

- shiro rememberMe decode 解密
  - 支持 shiro 常见 100 key 遍历识别解密
  - 支持 ysoserial CommonsBeanutils1、CommonsCollections 1-10 遍历识别
  - 支持执行命令内容识别


# 部署方法

① 可本地打开直接使用

下载全部文件，打开index.html页面即可使用

② 可以部署到任何WEB服务器（前端页面纯静态，也可以放到github博客上）

下载全部文件，放入WEB目录，使用浏览器直接访问index.html即可

> 为方便使用及保证源码安全，本项目前后端分离，只需要部署前端静态页面即可使用

> 后端已部署到VPS服务器上可通过前端直接调用API，目前暂不公开后端源码


# 使用方法

打开页面即可使用，所见即所得，应该不用多解释

- shiro rememberMe encode 加密
  - 【输入/必填】
    - 选择加密使用的 AES_key
    - 选择加密使用的 ysoserial_option
    - 输入要加密的命令内容 command
  - 【输出】
    - 加密结果

- shiro rememberMe decode 加密
  - 【输入/必填】
    - 输入要解密的内容
  - 【输出】
    - 自动识别使用的 AES_key
    - 自动识别使用的 ysoserial_option
    - 自动识别执行的命令内容 command
    - 解密结果

![shiro rememberMe 在线加解密工具-1](/webapp-shiro-1.png)

![shiro rememberMe 在线加解密工具-2](/webapp-shiro-2.png)