# site_name: Linux基础

## -nav:

### 一：index: index.md

### 二：桌面Linux安装

1. ##### 虚拟机： [创建虚拟机.md]()

2. ##### SSH测试：  [SSH测试.md]()

3. ##### 换源：  [换源.md]()

4. ##### 基础测试（zsh)：[基础测试.md]()

5. ##### 分区创建测试：[分区创建测试.md]()

6. ##### 磁盘挂载测试：[磁盘挂载测试.md]()

7. ##### B系统预装测试：[B系统预装测试.md]()

8. ##### B安装基础测试：[B安装基础测试.md]()

9. ##### B系统必备软件安装测试：[B系统必备软件安装测试.md]()

10. ##### B系统引导设置：[B系统引导设置.md]()

11. ##### **B系统SSH测试：[B系统SSH测试.md]()**

12. ##### **B系统基础测试：[B系统基础测试.md]()**

13. ##### 搜狗输入法测试：[搜狗输入法测试.md]()

14. ##### **samba测试：[samba测试,md]()**

15. ##### **WPS测试：[WPS测试.md]()**

16. ##### xrdp测试:[xrdp测试.md]()

17. **远程桌面操作：[远程桌面操作.md]()**

## -plugins:

### 一：pandoc

combined: true
enabled_if_env: ENABLE_PANDOC_EXPORT
pandoc_args:
   pdf_engine: xelatex
   metadata: mainfont=SimSun
   metadata: sansfont="Microsoft YaHei
   metadata: monofont="WenQuanYi Micro Hei Mono
   to: pdf
