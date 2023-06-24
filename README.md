# Test Build Sophgo Vendor Kernel For Archlinux

**注意** 

**This Kernel for test on Sophgo Milk-V RISCV Archlinux**

````
[houge_personal]
SigLevel = Optional TrustAll
Server = http://hougearch.litterhougelangley.club/riscv/
````
下一步争取将 rc 内核进行打包并提供给想参与测试的朋友使用，到时候我会再开一个源地址，谢谢大家的助力～

**P.S**

1. 内核如果是大版本更新，请将这个目录下 `/usr/share/dtbs/sophgo/` 的4个dtb文件替换第1分区 riscv64 文件夹下的内容（对应名称替换）；
2. 任何问题都可以提交 issue 。