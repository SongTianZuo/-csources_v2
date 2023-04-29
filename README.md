# csources_v2
Nim csources_v2, Support for Loongarch64，增加loongarch64的支持

龙芯环境下，对nim源码编译loongarch64的支持

原先在直接在3A5000 linux编译不了。然后在windows 下 clone了 nim 的源代码，先运行 build_all.bat， 再修改 nim 源码中 compiler 目录下的 installer.ini, 增加 linux 的 loongarch64 支持：

linux: i386;hppa;ia64;alpha;amd64;powerpc64;arm;sparc;sparc64;m68k;mips;mipsel;mips64;mips64el;powerpc;powerpc64el;arm64;riscv32;riscv64;**loongarch64**

再运行 koch csource, 以上。

