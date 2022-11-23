# 安装编译
nginx中新增lua-nginx-module，同时支持x-waf在idea中编程调试。
安装过程参考：
https://blog.csdn.net/liaomin416100569/article/details/127982273?spm=1001.2014.3001.5501

## 编译luajit
包：package/luajit2-2.1-agentzh.zip

## 编译lua-nginx-module
源代码中包含:
1. ndk源码：ngx_devel_kit-0.3.0
2. lua-nginx-module源码

## 其他编译依赖关联的库
1. package/lua-resty-core-master.rar
2. package/lua-resty-lrucache-master.rar
3. package/lua-resty-core-master.rar

## x-waf
1. x-waf: conf/x-waf目录