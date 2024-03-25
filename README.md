# WEB-shiro_rememberMe_encode_decode 在线加解密工具

## 工具简述

本项目为 shiro rememberMe 在线加解密工具

在线体验地址：https://simolin.cn/tools/shiro (已弃用，直接看关键代码吧)

![shiro rememberMe 在线加解密工具](https://github.com/M-Kings/WEB-shiro_rememberMe_encode_decode/blob/master/webapp-shiro.png)

可以使用本工具：

| 功能           | 加密                                                      | 解密                                                               |
| -------------- | --------------------------------------------------------- | ------------------------------------------------------------------ |
| AES key 特性   | 支持 shiro 常见 key                                       | 支持 shiro 常见 100 key 遍历识别解密                               |
| ysoserial 特性 | 支持 ysoserial CommonsBeanutils1、CommonsCollections 1-10 | 支持 ysoserial CommonsBeanutils1、CommonsCollections 1-10 遍历识别 |
| 其他           | /                                                         | 支持执行命令内容识别                                               |

## 使用方法

非常抱歉原本只给了前端源码(屁用没有)

现在把关键的加解密代码更新上来(其实也没啥用，就一个加解密和正则提取，随便看看吧)

## 附录 A shiro 常见 key

> 有一些 key 可能有点问题不能使用，忽视即可

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
3qDVdLawoIr1xFd6ietnwg==
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
empodDEyMwAAAAAAAAAAAA==
A7UzJgh1+EWj5oBFi+mSgw==
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
