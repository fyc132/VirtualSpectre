# VirtualSpectre
a free vt-x&amp;ept debugger

# 虚拟幽灵
一个免费的基于vt-x&ept技术的多功能调试器

![avatar](https://wx4.sinaimg.cn/mw690/e9978128gy1gqecu134gdj21110cbq5m.jpg)

## 环境支持
支持所有的Win10版本x64系统 ,支持intel虚拟化的cpu,需要在主板中打开vt选项


## 功能

### 超级调试引擎
使用重构的调试引擎接管系统，不受各种反调试影响 (BE/XE/XC3/EAC/TP...)

调试EAC示例:
![avatar](https://wx1.sinaimg.cn/mw1024/e9978128gy1gqeiyn721kj21h90u0hdv.jpg)

### 超级断点引擎
一方通行，使用ept技术接管硬件断点 R/W/E。不受占坑影响，且无法被检测到drx

### 超级句柄引擎
使用自定义句柄引擎接管，独立于系统句柄之上,无法被检测句柄

### 反ASLR
基址固定，可以指定程序或其加载的DLL时的基址，方便调试

![avatar](https://wx4.sinaimg.cn/mw690/e9978128gy1gqecu142kcj211d0bdq82.jpg)

![avatar](https://wx4.sinaimg.cn/mw690/e9978128gy1gqecu15resj20wj09l46m.jpg)

### 内存监视器
监视指定进程中的内存的读写访问记录，支持指定长度，同时支持内核地址，类似于CE的查找访问读写地址

### 调试器保护
保护调试器本身内存跟句柄不被读取，检测

### 异常忽略器
自动跳过频繁的异常，不发送给调试器

## 用法

coming soon
