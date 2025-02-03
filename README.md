# IBNIZ
### (Attempted Chinesize)

IBNIZ是一种专为极其紧凑的低级音视频程序设计的虚拟机。其主要设计目标是作为展示场景（demoscene）作品、故障艺术（glitch art）及类似项目的平台。主流软件工程方面的内容被认为完全无关紧要。

IBNIZ的全称是Ideally Bare Numeric Impression giZmo。这个名字也与戈特弗里德·莱布尼茨（Gottfried Leibniz）有关，他是17世纪的博学多才者，他发明了二进制算术，制造了第一台四则运算计算器，并且相信世界是基于“最小规则集产生最大多样性”的原则设计的。

<a href="http://www.youtube.com/watch?feature=player_embedded&v=aKMrBaXJvMs
" target="_blank"><img src="http://img.youtube.com/vi/aKMrBaXJvMs/0.jpg" 
alt="示例" width="240" height="180" border="10" /></a>

* [示例视频](https://www.youtube.com/watch?v=aKMrBaXJvMs)
* [文档](src/ibniz.txt)
* [官方网站](http://viznut.fi/ibniz/)
* 社区: `#countercomplex` @ IRCnet
* [JavaScript实现](http://ibniz.breizh-entropy.org/) ([git](https://github.com/asiekierka/ibnjs))
* [另一种JavaScript实现](https://flupe.github.io/jibniz/) ([git](https://github.com/flupe/jibniz))

## 构建

### Linux

前置:
* [SDL](https://www.libsdl.org) v1.2.x

运行以下命令：
```
cd src
make
```

### MacOS

前置:
* Apple开发者工具（通过Xcode安装）
* [SDL](https://www.libsdl.org) v1.2.x (通过[Homebrew](https://brew.sh)获取SDL的简单方法是运行 `brew install sdl`)

运行以下命令：
```
cd src
make -f Makefile.osx
```

### Windows

前置:
* [MinGW](http://www.mingw.org)
* [SDL](https://www.libsdl.org) v1.2.x

运行以下命令：
```
cd src
make -f Makefile.win
```
