## 简介
  使用该工具在Macos中对wx小程序进行反编译
  适用于微信版本>3.8.0

## 使用
1.装依赖
```
npm install
```
2.解包主包
```
./bingo.sh <主包文件路径>
```
例:
```
./bingo.sh /Users/whoami/Desktop/WxAPP/30/__APP__.wxapkg
```
3.解子包
```
./bingo.sh <子包路径> -s=<主包解包后生成的文件夹>
```
例:
```
./bingo.sh /Users/whoami/Desktop/WxAPP/30/_pages_guide_.wxapkg -s=/Users/whoami/Desktop/WxAPP/30/__APP__
```
