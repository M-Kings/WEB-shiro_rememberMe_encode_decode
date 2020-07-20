# WEB-shiro_rememberMe_encode_decode 在线加解密工具

## 工具简述

本项目为 shiro rememberMe 在线加解密工具（WEB）

在线体验地址：https://simolin.cn/tools/shiro

可以使用本工具：


功能|加密|解密
---|---|---
AES key 特性|支持 shiro 常见 100 key|支持 shiro 常见 100 key 遍历识别解密
ysoserial 特性|支持 ysoserial CommonsBeanutils1、CommonsCollections 1-10|支持 ysoserial CommonsBeanutils1、CommonsCollections 1-10 遍历识别
其他|/|支持执行命令内容识别


## 使用方法

打开页面即可使用，所见即所得，应该不用多解释


功能|加密|解密
---|---|---
输入（必填）|选择加密使用的 AES_key|要解密的内容
/|选择加密使用的 ysoserial_option|/
/|要加密的命令内容 command|/
输出|加密结果|自动识别使用的 AES_key
/|/|自动识别使用的 ysoserial_option
/|/|自动识别执行的命令内容 command
/|/|解密结果


![shiro rememberMe 在线加解密工具](https://github.com/M-Kings/WEB-shiro_rememberMe_encode_decode/blob/master/webapp-shiro.png)

## 部署方法（前端页面）

项目地址：https://github.com/M-Kings/WEB-shiro_rememberMe_encode_decode

项目前端基于 Vue + ElementUI 实现

### 本地打开

可本地打开直接使用

- 下载全部文件
- 使用浏览器打开index.html页面即可使用

### 部署到Web服务器

可以部署到任何WEB服务器（前端页面纯静态，也可以放到github博客上）

- 下载全部文件
- 放入WEB目录
- 使用浏览器直接访问index.html即可

> 为方便使用及保证源码安全，本项目前后端分离，只需要部署前端静态页面即可使用

> 后端已部署到VPS服务器上可通过前端直接调用API，目前暂不公开后端源码

## 附录A shiro 常见100key

> 有一些key可能有点问题不能使用，忽视即可

```
kPH+bIxk5D2deZiIxcaaaA==(shiro默认key，最常见)
wGiHplamyXlVB11UXWol8g==
2AvVhdsgUs0FSA3SDFAdag==
4AvVhmFLUs0KTA3Kprsdag==
3AvVhmFLUs0KTA3Kprsdag==
Z3VucwAAAAAAAAAAAAAAAA==
U3ByaW5nQmxhZGUAAAAAAA==
6ZmI6I2j5Y+R5aSn5ZOlAA==
fCq+/xW488hMTCD+cmJ3aQ==
1QWLxg+NYmxraMoxAXu/Iw==
ZUdsaGJuSmxibVI2ZHc9PQ==
L7RioUULEFhRyxM7a2R/Yg==
r0e3c16IdVkouZgk1TKVMg==
5aaC5qKm5oqA5pyvAAAAAA==
bWluZS1hc3NldC1rZXk6QQ==
a2VlcE9uR29pbmdBbmRGaQ==
WcfHGU25gNnTxTlmJMeSpw==
bWljcm9zAAAAAAAAAAAAAA==
MTIzNDU2Nzg5MGFiY2RlZg==
5AvVhmFLUs0KTA3Kprsdag==
0AvVhmFLUs0KTA3Kprsdag==
1AvVhdsgUs0FSA3SDFAdag==
25BsmdYwjnfcWmnhAciDDg==
3JvYhmBLUs0ETA5Kprsdag==
6AvVhmFLUs0KTA3Kprsdag==
6NfXkC7YVCV5DASIrEm1Rg==
cmVtZW1iZXJNZQAAAAAAAA==
7AvVhmFLUs0KTA3Kprsdag==
8AvVhmFLUs0KTA3Kprsdag==
8BvVhmFLUs0KTA3Kprsdag==
9AvVhmFLUs0KTA3Kprsdag==
OUHYQzxQ/W9e/UjiAGu6rg==
a3dvbmcAAAAAAAAAAAAAAA==
aU1pcmFjbGVpTWlyYWNsZQ==
bXRvbnMAAAAAAAAAAAAAAA==
OY//C4rhfwNxCQAQCrQQ1Q==
5J7bIJIV0LQSN3c9LPitBQ==
f/SY5TIve5WWzT4aQlABJA==
bya2HkYo57u6fWh5theAWw==
WuB+y2gcHRnY2Lg9+Aqmqg==
kPv59vyqzj00x11LXJZTjJ2UHW48jzHN
3qDVdLawoIr1xFd6ietnwg==
ZWvohmPdUsAWT3=KpPqda
YI1+nBV//m7ELrIyDHm6DQ==
6Zm+6I2j5Y+R5aS+5ZOlAA==
2A2V+RFLUs+eTA3Kpr+dag==
6ZmI6I2j3Y+R1aSn5BOlAA==
SkZpbmFsQmxhZGUAAAAAAA==
2cVtiE83c4lIrELJwKGJUw==
fsHspZw/92PrS3XrPW+vxw==
XTx6CKLo/SdSgub+OPHSrw==
sHdIjUN6tzhl8xZMG3ULCQ==
O4pdf+7e+mZe8NyxMTPJmQ==
HWrBltGvEZc14h9VpMvZWw==
rPNqM6uKFCyaL10AK51UkQ==
Y1JxNSPXVwMkyvES/kJGeQ==
lT2UvDUmQwewm6mMoiw4Ig==
MPdCMZ9urzEA50JDlDYYDg==
xVmmoltfpb8tTceuT5R7Bw==
c+3hFGPjbgzGdrC+MHgoRQ==
ClLk69oNcA3m+s0jIMIkpg==
Bf7MfkNR0axGGptozrebag==
1tC/xrDYs8ey+sa3emtiYw==
ZmFsYWRvLnh5ei5zaGlybw==
cGhyYWNrY3RmREUhfiMkZA==
IduElDUpDDXE677ZkhhKnQ==
yeAAo1E8BOeAYfBlm4NG9Q==
cGljYXMAAAAAAAAAAAAAAA==
2itfW92XazYRi5ltW0M2yA==
XgGkgqGqYrix9lI6vxcrRw==
ertVhmFLUs0KTA3Kprsdag==
5AvVhmFLUS0ATA4Kprsdag==
s0KTA3mFLUprK4AvVhsdag==
hBlzKg78ajaZuTE0VLzDDg==
9FvVhtFLUs0KnA3Kprsdyg==
d2ViUmVtZW1iZXJNZUtleQ==
yNeUgSzL/CfiWw1GALg6Ag==
NGk/3cQ6F5/UNPRh8LpMIg==
4BvVhmFLUs0KTA3Kprsdag==
MzVeSkYyWTI2OFVLZjRzZg==
CrownKey==a12d/dakdad
empodDEyMwAAAAAAAAAAAA==
A7UzJgh1+EWj5oBFi+mSgw==
YTM0NZomIzI2OTsmIzM0NTueYQ==
c2hpcm9fYmF0aXMzMgAAAA==
i45FVt72K2kLgvFrJtoZRw==
U3BAbW5nQmxhZGUAAAAAAA==
ZnJlc2h6Y24xMjM0NTY3OA==
Jt3C93kMR9D5e8QzwfsiMw==
MTIzNDU2NzgxMjM0NTY3OA==
vXP33AonIp9bFwGl7aT7rA==
V2hhdCBUaGUgSGVsbAAAAA==
Z3h6eWd4enklMjElMjElMjE=
Q01TX0JGTFlLRVlfMjAxOQ==
ZAvph3dsQs0FSL3SDFAdag==
Is9zJ3pzNh2cgTHB4ua3+Q==
NsZXjXVklWPZwOfkvk6kUA==
GAevYnznvgNCURavBhCr1w==
66v1O8keKNV3TTcGPK1wzg==
SDKOLKn2J1j/2BHjeZwAoQ==
```