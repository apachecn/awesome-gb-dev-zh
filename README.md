# GB 开发资源列表

## 介绍

### [GameBoy，硬件尸检](https://www.youtube.com/playlist?list=PLu3xpmdUP-GRDp8tknpXC_Y4RUQtMMqEu)

[https://www.youtube.com/embed/videoseries?list=PLu3xpmdUP-GRDp8tknpXC_Y4RUQtMMqEu](https://www.youtube.com/embed/videoseries?list=PLu3xpmdUP-GRDp8tknpXC_Y4RUQtMMqEu)

### [终极GameBoy谈](https://media.ccc.de/v/33c3-8029-the_ultimate_game_boy_talk)

[https://www.youtube.com/embed/HyzD8pNlpwI](https://www.youtube.com/embed/HyzD8pNlpwI)

> ### 解疑
> 
> #### GameBoy前进
> 
> Game Boy 高级开发被另一个项目覆盖， [awesome-GBAdev 列表。然而，GBA 可以运行 GB/GBC 游戏。与本机硬件相比，它的实现方式略有不同。这包括在这个列表的模拟器开发部分。](https://github.com/gbdev/awesome-gbadev)
> 
> #### GameBoy颜色和超级GameBoy
> 
> 这份名单集中在最初的(1989 年)GameBoy(DMG)，GameBoy颜色(T0)和超级GameBoy(T3)是非常相似的系统，有一些重要的区别，例如:
> 
> *   不同的硬件规格
> *   特定的硬件和软件功能
> *   特定寄存器
> *   特定的错误、怪癖和可利用的行为
> 
> 如果你的目标是为 SGB 或 GBC 开发你的软件，或者你想知道它如何在其他系统上运行，你可能想要利用并适应这些差异，检查 [Game Boy Color](#game-boy-color) 类别并寻找 GBC/CGB 和 SGB 的具体参考。

## 证明文件

*   [**【Pan Docs】**](https://gbdev.github.io/pandocs/)——向公众提供 Game Boy 最全面的单一技术参考。由社区更正、更新和维护。
*   周期精确的 Game Boy Docs 打开——AntonioND 制作周期精确的 Game Boy 模拟器的精确文档。
*   [完成技术参考](https://gekkio.fi/files/gb-docs/gbctr.pdf) ——由 Gekkio 完成。
*   [Game Boy 项目报告](http://www.cs.columbia.edu/~sedwards/classes/2019/4840-spring/reports/GameBoy.pdf) -硬件报告[仿真器](https://github.com/kitsuneh/SVGameBoy) (在 Terasic DE1-SoC 板上)作为哥伦比亚大学 CSEE4840 嵌入式系统设计课程的最终项目开发。

#### 操作码

*   [GB-操作码](https://gbdev.github.io/gb-opcodes/optables/) -操作码表
*   [RGBDS 操作码引用](https://rgbds.gbdev.io/docs/gbz80.7) ——所有指令的引用，包括简短描述、周期和字节计数，以及对标志修改的解释。

### GameBoy颜色

*   [自举 ROM](https://tcrf.net/Game_Boy_Color_Bootstrap_ROM)
*   [未使用的调色板](https://tcrf.net/Notes:Game_Boy_Color_Bootstrap_ROM)
*   [BIOS 中的调色板](https://forums.nesdev.com/viewtopic.php?p=114388&sid=c3d4ce08cfd9d9c834958d4f148750c3#p114388)
*   [ROM 拆卸](https://gist.github.com/drhelius/6063265)

### 五金器具

*   [DMG 原理图](http://gbdev.gg8.se/wiki/articles/DMG_Schematics) -硬件原理图。
*   [Game Boy 项目](http://marc.rawer.de/Gameboy/Docs/GBProject.pdf) ——为三个 8 位双向并行端口的实现提供硬件研究和详细的结构信息。
*   [相关自定义硬件](https://github.com/Gekkio/gb-hardware) ——由 Gekkio 打开。
*   [ESP8266 GB 开发板](https://github.com/applefreak/esp8266-gameboy-dev-board) -用于 Game Boy 配件开发的开发板，由 ESP8266 驱动。
*   [ESP8266 GB 打印机](https://github.com/applefreak/esp8266-gameboy-printer) -一种模拟 GB 打印机的设备，让您使用 WiFi 检索图像。
*   [fruttenboel](http://verhoeven272.nl/fruttenboel/Gameboy/index.html) ——页面上有大量关于硬件、定制板的信息，以便与控制台和其他相关项目进行交互。
*   [Game Boy 硬件数据库](https://gbhwdb.gekkio.fi/)——各种类型 Game Boy 游戏机的数据和照片。
*   [DMG-CPU-Inside](https://github.com/furrtek/DMG-CPU-Inside) -DMG-CPU-B 芯片的原理图和注释叠加图，从芯片照片中提取。

### 外围设备

*   [丹文档](https://shonumi.github.io/dandocs.html) ——晦涩的 Game Boy 硬件文档。
*   [边缘仿真](https://shonumi.github.io/articles.html) ，一系列关于仿真和调查 Game Boy 配件的文章。也可作为在 GBE- emulator 文档的新窗口 的[技术文档 。](https://github.com/shonumi/gbe-plus/tree/master/src/docs/technical)
    *   [移动适配器 GB](https://shonumi.github.io/articles/art14.html) -网络连接和游戏上的 DLC 男孩色。
    *   [游戏机打印机](https://shonumi.github.io/articles/art2.html)
    *   [袖珍声纳](https://shonumi.github.io/articles/art13.html) ——一辆内置声纳硬件的蓝色推车。
    *   [Zok Zok Heroes](https://shonumi.github.io/articles/art8.html)——Zok Zok Heroes 的全换器，一个动作激活的配件。
    *   [红外疯狂](https://shonumi.github.io/articles/art11.html) ——游戏上的红外通讯男孩色。
    *   [Game Boy 4 人适配器](https://shonumi.github.io/articles/art9.html) - DMG-07。
    *   [条码男孩](https://shonumi.github.io/articles/art7.html)——第一个GameBoy的卡片扫描仪。
    *   [条形码泰森 Bardigun](https://shonumi.github.io/articles/art6.html) ——一款 90 年代末的 DMG-GBC 条形码阅读器。
*   [DMG-07 技术文档](https://raw.githubusercontent.com/shonumi/gbe-plus/master/src/docs/technical/DMG_07.txt)
*   [Game Boy Camera RE](https://github.com/AntonioND/gbcam-rev-engineer) ——关于 GB Camera 的文档以及使用 Arduino 对其进行逆向工程的工具。
*   [使用神经网络和 Gameboy 相机创建照片级逼真图像](http://www.pinchofintelligence.com/photorealistic-neural-network-gameboy/)
*   [Game Boy 打印机](https://shonumi.github.io/articles/art2.html) ——一份关于打印机硬件、通信协议和游戏用于实现打印功能的常用例程的深入技术文档。
*   [Ben Heck 逆向工程师 Game Boy 打印机](https://www.youtube.com/watch?v=43FfJvd-YP4) (勘误:使用过的热敏纸过期，实际可打印 4 色)。
*   [Arduino Game Boy 打印机模拟器](https://github.com/mofosyne/arduino-gameboy-printer-emulator) -通过 Game Boy Link 线缆用 Arduino 模拟 Game Boy 打印机。
*   [手机GameBoy适配器](https://bulbapedia.bulbagarden.net/wiki/Mobile_Game_Boy_Adapter)
*   [GB KISS LINK MODEM](http://nectaris.tg-16.com/GB-KISS-LINK-FAQ-hudson-gameboy-nectaris.html)

### 子弹

*   [AntonioND 的文档](https://github.com/AntonioND/giibiiadvance/tree/master/docs) -更正了墨盒标题数据上的原理图和信息。
*   [Gekkio 的 Game Boy 弹夹类型](http://gekkio.fi/blog/2015-02-14-mooneye-gb-gameboy-cartridge-types.html) -现有弹夹类型概述。
*   盖柯的弹壳分析:
    *   [DMG-比恩-02T3】](http://gekkio.fi/blog/2015-05-18-mooneye-gb-cartridge-analysis-dmg-bean-02.html)；
    *   [MBC1](http://gekkio.fi/blog/2015-05-17-mooneye-gb-cartridge-analysis-fortress-of-fear.html)；
    *   [没有 MBCT3】](http://gekkio.fi/blog/2015-02-28-mooneye-gb-cartridge-analysis-tetris.html) 。
*   Tauwasser 的 wiki 上某些墨盒类型的引脚排列、寄存器描述和 VHDL 代码:
    *   [MBC1](https://wiki.tauwasser.eu/view/MBC1)
    *   [MBC2](https://wiki.tauwasser.eu/view/MBC2)
    *   [MMM01](https://wiki.tauwasser.eu/view/MMM01)
*   [Game Boy 墨盒原理图](http://www.devrs.com/gb/files/gb.html) -MB C2 和 MBC3 类型的原理图。
*   [墨盒 PCB 照片](https://imgur.com/a/D5bpC)
*   [MB C1+RAM+电池盒原理图](http://www.devrs.com/gb/files/mbc1.gif) ——Jeff Frohwein 的第一张原理图。
*   [MBC1 和 MBC2 盒式电路](http://fms.komkon.org/GameBoy/Tech/Carts.html) ——并解释这些 MBC 银行如何开关和控制 RAM。
*   GB Rom 列表 -每款游戏的导航表，详细介绍了游戏的卡带。
*   [Game Boy 墨盒 PCB 照片](http://gekkio.fi/blog/2016-03-19-game-boy-cartridge-pcb-photos.html)

#### 定制墨盒

*   [仿真 GameBoy 卡盒](https://dhole.github.io/post/gameboy_cartridge_emu_1/) -使用开发板 STM32F4 仿真 Game Boy 卡盒的功能。
*   [狼](http://www.happydaze.se/wolf/)——Game Boy 卡带协处理器。
*   [家酿-Gameboy-Cartridge](https://github.com/dwaq/Homebrew-Gameboy-Cartridge) - Eagle 库，原理图，以及使用 Atmel AT49F040 作为 ROM 的 cartridge PCB 的板文件。
*   [家酿 Gameboy 彩色墨盒](https://github.com/Xyl2k/Gameboy-Color-Cartridge) -EEPROM 供电墨盒的电路板布局。
*   [Nekocart](https://github.com/zephray/NekoCart-GB) ——使用 Xilinx CPLD 作为 MBC5 的开源 flash cart([Post](https://hackaday.io/project/41160-nekocart-cpld-gameboy-cartridge) )。
*   [Reiner Ziegler 的 Game Boy 页面](http://reinerziegler.de.mirrors.gg8.se/) -商业和自制可编程盒式磁带和编程系统。提供教程、布线和原理图。
*   [game boy-MB C5-MB C1-Hybrid](https://github.com/insidegadgets/Gameboy-MBC5-MBC1-Hybrid) -一个 MBC5/MBC1 混合弹药筒的 CPLD 实现。

#### 混杂的

*   [Game Boy 黑客入门](http://pepijndevos.nl/sha2017/workshop.pdf)——工作坊介绍基本组装、调试和逆向工程。
*   [GBSOUND.txt](https://github.com/bwhitman/pushpin/blob/master/src/gbsound.txt) ——一个详细介绍 Game Boy 声音引擎的文档。
*   [gbdev FAQ](http://www.devrs.com/gb/files/faqs.html)——杰夫·弗罗温必读。
*   [Game Boy Bootrom](http://www.neviksti.com/DMG/DMG_ROM.asm)——评论转储 DMG bootrom。
*   [Z80 和 gameboy 的处理器的区别](http://www.z80.info/z80gboy.txt) 打开
*   [Gameboy 2BPP 图形格式](http://www.huderlem.com/demos/gameboy2bpp.html) ——关于 Gameboy 如何将 VRAM 图块数据解释为彩色像素的信息。

## 仿真器开发

*   [逆向工程 Game Boy 硬件的精细细节](https://www.youtube.com/watch?v=GBYwjch6oEE) - 43 分钟 Gekkio 在违抗 2018 时给出的对话([勘误表](https://gekkio.fi/blog/2018-02-05-errata-for-reverse-engineering-fine-details-of-game-boy-hardware.html) )。
*   [任天堂游戏机 的仿真](https://github.com/Baekalfen/PyBoy/blob/master/PyBoy.pdf)——从构建仿真器的角度概述游戏机硬件。
*   [DMG-01](https://rylev.github.io/DMG-01/public/book/) -Rust 中的一款教育性 Gameboy 模拟器以及解释其开发的配套书籍。* [哎呀小子！在 Rust 中创建 Game Boy 模拟器](https://media.ccc.de/v/rustfest-rome-3-gameboy-emulator) ——这是 Rust Fest 18 上的一个演讲。
*   [用 JavaScript 构建 Game Boy 模拟器](http://imrannazar.com/gameboy-Emulation-in-JavaScript)——循序渐进教程。
*   [编写一个 Game Boy 模拟器，Cinoop](https://cturt.github.io/cinoop.html)
*   [0dmg](https://jeremybanks.github.io/0dmg/2018/05/23/getting-started.html)——通过构建一个偏 Game Boy 模拟器学习 Rust。
*   [RealBoy 模拟器](https://realboyemulator.wordpress.com/posts/)——关于 RealBoy 模拟器的设计与实现的一系列帖子。
*   [Codeslinger](http://www.codeslinger.co.uk/pages/projects/gameboy.html) ——另一系列记录模拟器构建的帖子。
*   [为什么我要花 1.5 个月的时间来创建一个 Gameboy 模拟器？](http://blog.rekawek.eu/2017/02/09/coffee-gb/) -博文。
*   [binjgb 倒带](https://binji.github.io/2017/12/31/binjgb-rewind.html) -实现*倒带功能。
*   [web 上的 binjgb](https://binji.github.io/2017/02/26/binjgb-on-the-web-part-1.html) -将 binjgb 仿真器移植到 Web 程序集。 [(Part 2)](https://binji.github.io/2017/02/27/binjgb-on-the-web-part-2.html)
*   [binjgb 调试挂起](https://binji.github.io/2017/05/03/debugging-hangs.html) ——对仿真怪癖进行调查。
*   [解码 Gameboy Z80 操作码](https://gb-archive.github.io/salvage/decoding_gbz80_opcodes/Decoding%20Gamboy%20Z80%20Opcodes.html) ——如何从算法上解码 Gameboy 指令(相对于编写一个巨大的 switch-case 语句)。
*   [将 GO Game Boy 模拟器移植到 WebAssembly](https://djhworld.github.io/post/2018/09/21/i-ported-my-gameboy-color-emulator-to-webassembly/)
*   [关于 swotGB](https://mitxela.com/projects/swotgb/about)——关于用 JavaScript 开发一个 Game Boy 模拟器的注意事项。
*   [开源仿真器列表](/EMULATORS.html)

### 测试

*   [Blargg 的测试 rom](http://gbdev.gg8.se/files/roms/blargg-gb-tests/) 打开
*   [Gekkio 的测试 rom](https://gekkio.fi/files/mooneye-gb/latest/) 打开
*   [SameSuite](https://github.com/LIJI32/SameSuite)
*   [粉蚧茶室测试](https://github.com/mattcurrie/mealybug-tearoom-tests) 打开
*   [GB 准确度测试](http://tasvideos.org/EmulatorResources/GBAccuracyTests.html)
*   [144p 测试套件](https://github.com/pinobatch/240p-test-mini/tree/master/gameboy)——阿尔特米奥乌尔维纳港的 240p 测试套件给 Game Boy。
*   [MBC3 RTC 测试 ROM](https://github.com/aaaaaa123456789/rtc3test)
*   [dmg-acid2](https://github.com/mattcurrie/dmg-acid2) 和 [cgb-acid2](https://github.com/mattcurrie/cgb-acid2) -基本 PPU 渲染测试。

## 软件开发

的[为 Game Boy 开发选择工具 文章概述了 Game Boy 可用的开发工具。](https://gbdev.io/guides/tools.html)

### 装配工

*   [RGBDS](https://github.com/gbdev/rgbds) ——汇编器和链接器包。[文档](https://rgbds.gbdev.io/docs/) 。
*   [ASMotor](https://github.com/csoren/asmotor) ——汇编引擎和开发系统针对 Game Boy 等 CPU。由 RGBDS 原作者撰写。[文档](https://github.com/asmotor/asmotor/tree/develop#further-reading) 。
*   [wla-dx](https://github.com/vhelin/wla-dx) -又一个 GB-Z80/Z80/...多平台交叉汇编程序包。[文档](http://www.villehelin.com/wla.txt) 。

### 编译程序

*   [GBDK](https://github.com/gbdk-2020/gbdk-2020/) ——维护和现代化 GBDK (Game Boy 开发套件)，由 SDCC 工具链的更新版本提供支持。提供了一个 C 编译器，汇编器，链接器和一组库。
    *   [API 文档:入门](https://gbdk-2020.github.io/gbdk-2020/docs/api/docs_getting_started.html)
    *   [示例](https://github.com/mrombout/gbdk_playground)
    *   [文档、链接和工具](https://gbdk-2020.github.io/gbdk-2020/docs/api/docs_links_and_tools.html)
*   [Turbo Rascal 语法错误](https://lemonspawn.com/turbo-rascal-syntax-error-expected-but-begin/) -完整套件(IDE、编译器、编程语言、资源编辑器)，用于开发 8 / 16 位系列计算机的游戏/演示，包括 Game Boy 和 Game Boy Color。

#### 实验/概念验证

*   [RGBDS-Live](https://daid.github.io/rgbds-live/) -在浏览器编码环境中试用 RGBDS。
*   [Wiz](https://github.com/wiz-lang/wiz) ——一种用于在复古主机平台(Game Boy、NES、雅达利 2600 等)上编写自制程序的高级汇编语言。
*   [gbforth](https://github.com/ams-hackers/gbforth)——一个基于 forth 的 Game Boy 开发套件。
*   [gbasm-rs](https://gitlab.com/BonsaiDen/gbasm-rs) ——一个自以为是的基于 Rust 的编译器，用于 Game Boy z80 汇编代码。
*   [gbasm](https://github.com/BonsaiDen/gbasm) ——一个基于 JavaScript 的编译器，用于 Game Boy z80 汇编代码。
*   [tniASM](http://www.tni.nl/products/tniasm.html) -宏汇编器。
*   [汇编程序](https://github.com/ulrikdamm/Assembler) ——用 Swift 编写的汇编程序。
*   [llvm-gbz80](https://github.com/Bevinsky/llvm-gbz80)/[Clang-gbz 80](https://github.com/Bevinsky/clang-gbz80) - Clang/LLVM 端口到 GBZ80 CPU(类似于已弃用的[euclio/LLVM-gbz 80](https://github.com/euclio/llvm-gbz80)
*   [gbdk-go](https://github.com/pokemium/gbdk-go) ——一个编译器将 go 程序翻译成 C 代码。输出的 C 代码由 GBDK 内置到 GB ROM 中。

### 模拟器

*   [](https://bgb.bircd.org/)——功能强大的仿真器和调试器。提供精确的硬件仿真。
*   [SameBoy](https://github.com/LIJI32/SameBoy) -精确的仿真器，具有多种强大的调试功能。
*   [Mooneye GB](https://github.com/Gekkio/mooneye-gb) ——研究项目和仿真器在生锈。
*   [mGBA](https://github.com/mgba-emu/mgba) -现代跨平台 GBA 模拟器，也运行 GB/GBC 游戏。
*   [Binjgb](https://github.com/binji/binjgb) - 5Kloc 仿真器，通过大部分测试。*倒带功能。使用 WebAssembly 在浏览器中运行。
*   [Gambatte](https://github.com/sinamas/gambatte) ——跨平台和精确的仿真器。
*   [MetroBoy](https://github.com/aappleby/MetroBoy) ——一个可玩的，电路级模拟整个游戏的男孩。
*   [gbe-plus ...)](https://github.com/shonumi/gbe-plus)
*   [竞争](https://emulicious.net/) ——提供精确的仿真，包括强大的工具，例如通过 [VS 代码调试适配器](https://marketplace.visualstudio.com/items?itemName=emulicious.emulicious-debugger) 对 ASM 和 C 进行剖析和源代码级调试。

[开源仿真器的完整列表](/EMULATORS.html)

### 工具

#### 发动机

*   [](https://github.com/Zal0/ZGB)——一个为原来的 Game Boy 创作游戏的小引擎(扩展 gbdk，更多信息[此处](https://zalods.blogspot.com/2017/01/zgb-little-engine-for-game-boy.html) )。
*   [Retr0 GB](https://bitbucket.org/HellSuffering/retr0-gb/)——一个创作游戏的引擎(扩展 GBDK)。

#### 开发工具

*   [GBExtended](http://www.tensi.eu/thomas/programming/gameboy/gbextended.html) - C 库扩展 gbdk。
*   [gbdk-lib-extension](https://github.com/ProGM/gbdk-lib-extension) -由 Michael Hope 开发的 Game Boy 开发工具包的一个小的源码和工具集。
*   [点阵游戏编辑器](http://www.dotmatrixgame.com/) ——一个用于 Game Boy 编程的 IDE，使用类似 C 语言，名为 GBL，具有许多其他功能，如平铺和地图提取、WLA-DX 组装等等。
*   [mgbdis](https://github.com/mattcurrie/mgbdis) - Game Boy ROM 反汇编器与 RGBDS 兼容输出。
*   [ROM 标题实用程序](http://catskull.net/GB-Logo-Generator/) -一个在线工具，用于检查和修改 ROM 的标题数据，包括徽标。
*   [romusage](https://github.com/bbbbbr/romusage) -命令行工具，用于从地图中估算 Game Boy ROMs 的使用量(空闲空间)。noi 或 ihx 文件。与 GBDK-2020 和 RGBDS 合作。
*   [清醒](https://github.com/devdri/awake)——Game Boy 反编译程序。
*   [Game Boy 文本工具](https://github.com/raphaklaus/gameboy-text-tools) -一套用于文本操作和翻译 Node.js 中编写的 Game Boy ROMs 的工具
*   evscript ——GameBoy的脚本语言，对敌方 AI、对话、动画和协程有用。
*   [evunit](https://github.com/eievui5/evunit) -一个针对汇编代码的单元测试程序。

#### 图形实用程序

*   [Game Boy 图块数据生成器](https://github.com/chrisantonellis/gbtdg) - HTML5 / JS web 应用程序，将位图图像转换为适合在基于图块的图形应用程序中使用的十六进制数据，特别是 GB。
*   [哈利莫特的 GB 开发](http://www.devrs.com/gb/hmgd/intro.html) ——Game Boy Tile Designer(GBTD)和 Game Boy Map Builder (GBMB)工具的一些来源和主页。
*   [GBTiles](https://github.com/bashaus/gbtiles) ——转换。GBR 文件创建与哈利莫特的瓷砖设计师(GBTD)和。用哈利·莫特的地图构建器(GBMB)创建的 GBM 文件被转换成不同的格式用于GameBoy和 GBDK。
*   [bmp2cgb](https://github.com/gitendo/bmp2cgb) -为 Game Boy 色彩开发提供实时调色板调整的图形转换器。
*   [png2gb](https://github.com/LuckyLights/png2gb) - CLI 工具将图像文件转换为 game boy。c 数组。
*   [GB-转换](https://github.com/exezin/gb-convert) - Game Boy 磁贴转换和地图编辑工具(转换为汇编)。
*   [brewtool](http://make.vg/brewtool/) -一组原始编辑器/转换器工具，用于制作家酿 ROM 开发中使用的资源。
*   [vtGBte](https://github.com/paul-arutyunov/vtGBte) -一个极简的 ncurses 磁贴编辑器。
*   [tpp1](https://github.com/TwitchPlaysPokemon/tpp1) -自定义 GB/GBC 内存/硬件映射器的定义和规范，作为 MBC 的功能超集。
*   [libstdgb](https://github.com/delwink/libstdgb) -一个 C 库的有用的 Game Boy 操作(SDCC)。
*   [Tilemap GB](https://github.com/bbbbbr/gimp-tilemap-gb) - GIMP 图像编辑器插件用于导入&导出 GBMB 和 GBTD 的 Tilemap 和 tilesets(作为位图图像或。GBM/。GBR 文件)。
*   [Tilemap Helper](https://github.com/bbbbbr/gimp-tilemap-helper) - GIMP 图像编辑器插件，用于优化平铺地图和平铺集。
*   -一个用于 Game Boy、Color、Advance 和 SNES 项目的 Tilemap 编辑器。用 FLTK 用 C++写的。
*   [Superfamiconv](https://github.com/Optiroc/SuperFamiconv) -灵活且可组合的磁贴图形转换器，支持超级任天堂、Game Boy、Game Boy Color、Game Boy Advance、Mega Drive 和 PC 引擎格式。

#### 硬件和 ROM 实用程序

*   [cart-dumper](https://github.com/Palmr/cart-dumper) - Game Boy 弹夹 Dumper ROM。
*   [gbcamextract](https://github.com/jkbenaim/gbcamextract) ——从 Game Boy 相机中提取照片保存。
*   [Game Boy LCD 嗅探](https://github.com/svendahlstrand/game-boy-lcd-sniffing) ——使用逻辑分析仪嗅探您 Game Boy 的 LCD。
*   [swapdump](https://github.com/sanqui/swapdump) ——Game Boy flash carts 的诊断实用程序。
*   [Gameboy-LinkUp](https://github.com/JustinLloyd/Gameboy-LinkUp) - Game Boy LinkUp 串口有线联网项目。

#### 音乐驱动器和跟踪器

*   [DevSound](https://github.com/DevEd2/DevSound) -可嵌入自制软件的声音驱动程序，支持脉冲宽度操作、琶音和多种波形。
*   [钟琴播放器](http://gbdev.gg8.se/files/musictools/Aleksi%20Eeben/Carillon%20Editor.zip) -音乐引擎。
*   [GBT 播放器](https://github.com/AntonioND/gbt-player) -一个音乐播放器库和转换器套件。
*   [mmlgb](https://github.com/SimonLarsen/mmlgb) ——一个用于任天堂 Game Boy 的 MML 解析器和 GBDK 声音驱动程序。
*   -一个基于 MML 的音乐编译器，支持 Game Boy & Game Boy Color。
*   [SoundSystem](https://github.com/gb-archive/GBSoundSystem) -game boy Tracker(又名 Paragon 5 音乐播放器)的现代化音频驱动程序。
*   [hUGETracker](https://github.com/SuperDisk/hUGETracker) ——一个基于 OpenMPT 的音乐追踪器，专注于易用性、紧凑的输出，以及在自制游戏中的可嵌入性。
*   [CBT-FX](https://github.com/datguywitha3ds/CBT-FX) -一个兼容 FX-Hammer 音效的 GBDK-2020 音效驱动。

## 编程；编排

使用[软件开发](#software-development)章节中描述的开发工具链为 Game Boy 开发软件的指南、教程和工具。

### 空对地导弹

*   **[gb asm 教程](https://eldred.fr/gb-asm-tutorial)** ——循序渐进教程，构建几个 rom 来伴随其讲解。
*   [ASMSchool](http://gameboy.mongenel.com/asmschool.html)——Duo 关于 GB/GBC 汇编中编码与反汇编的一套教程。
*   [hardware.inc](https://github.com/tobiasvl/hardware.inc) -标准包含文件，包含用于 RGBDS 项目的 Game Boy 硬件定义。
*   [大卫·佩洛 的组装教程](https://gb-archive.github.io/salvage/tutorial_de_ensamblador/tutorial_de_ensamblador_la_decadence.html) -学习为 gb 生成工作 asm 代码的好文档。许多重要主题的简要说明。许多带有注释源代码的例子。
*   [assemblydigest](https://github.com/assemblydigest/gameboy) -探索 Game Boy 编程技巧:
    *   [制作一个空GameBoy ROM(在 Wiz)](http://assemblydigest.tumblr.com/post/77203696711/tutorial-making-an-empty-game-boy-rom-in-wiz)
    *   [为GameBoy制作美术](http://assemblydigest.tumblr.com/post/77404621743/tutorial-making-art-for-the-game-boy)
*   [逆向工程入门指南 GB](https://web.archive.org/web/20150511145100/http://www.bennvenn.com/Beginners_Guide_To_Reverse_Engineering.htm)——反汇编和逆向工程的一些入门技巧。
*   [FlappyBoy:制作简单的GameBoy游戏](http://voidptr.io/blog/2017/01/21/GameBoy.html)
*   [超级游戏王开发](https://imanoleasgames.blogspot.no/2016/12/games-aside-1-super-game-boy.html)——一步一步教程实现超级游戏王功能(框架和调色板)。
*   [GameBoy 编程教程:Hello World！](https://peterwynroberts.wordpress.com/2014/05/11/gameboy-programming-tutorial-hello-world/) ——循序渐进教程。
*   [DMGreport](https://github.com/lancekindle/DMGreport)——游戏编程教程在汇编。
*   [OAM DMA 教程](https://gbdev.gg8.se/wiki/articles/OAM_DMA_tutorial) ——如何在汇编中使用 OAM DMA 的例子。
*   [Game Boy 汇编编程面向现代游戏开发者](https://github.com/ahrnbom/gbapfomgd)——一本关于汇编制作 Game Boy 游戏的电子书。

#### 来源

代码片段、效果、概念证明和一般不完整的游戏。

*   [dev RS ASM 部分](http://www.devrs.com/gb/asmcode.php) ——大量工作演示和源代码。
*   [EmmaEwert 的实验](https://github.com/EmmaEwert/gameboy)——一堆原型程序，大多只是随便玩玩。其中包括日光效果、透明度和天气效果。
*   -一个关于如何使屏幕抖动的详细教程，以及其他“光栅效果”

#### 计时

*   [细节GameBoy循环计时](http://blog.kevtris.org/blogfiles/Nitty%20Gritty%20Gameboy%20VRAM%20Timing.txt)
*   [Mode3 雪碧定时](https://www.reddit.com/r/EmuDev/comments/59pawp/gb_mode3_sprite_timing/)
*   [GameBoy Color DMA-Transfers v 0 . 0 . 1](http://gameboy.mongenel.com/dmg/gbc_dma_transfers.txt)
*   [STAT 中断计时](http://gameboy.mongenel.com/dmg/istat98.txt)
*   [视频定时](https://github.com/jdeblese/gbcpu/wiki/Video-Timing)

#### 样板文件和库

*   [rgbds-模板](https://github.com/nezticle/rgbds-template) -GameBoy使用 RGBDS 的基本 hello-world 示例。
*   [Game Boy 汇编语言入门](http://www.devrs.com/gb/files/galp.zip) ——简单的模板代码，带有内存定义，复制例程和 IBM 字体 tilemap。
*   [bootstrap.gb](https://github.com/yenatch/bootstrap.gb) ——一个 Game Boy 项目的例子。
*   [Gameboy 样板文件](https://github.com/junebug12851/GameboyBoilerplateProj) ——样板文件项目可以更快地移入游戏的实际汇编代码。
*   [姜饼](https://github.com/ahrnbom/gingerbread) ——一个制作自己的 Game Boy 游戏的软件库。它是为 的现代游戏开发者 的书 [Game Boy Assembly Programming 一起使用的，该书也兼作文档。](https://github.com/ahrnbom/gbapfomgd)
*   [gb-vwf](https://github.com/ISSOtm/gb-vwf) -库打印可变宽度文本，附带演示。
*   [GB-样板文件](https://github.com/ISSOtm/gb-boilerplate) -启动 Game Boy 项目的模板，为基础设施提供 Makefile。
*   [gb-starter-kit](https://github.com/ISSOtm/gb-starter-kit) -对上述内容的扩展，包括基础库代码，以便更快上手。
*   [gb-template](https://github.com/gb-archive/gb-template) -具有基本功能的模板，如游戏手柄输入、DMA 传输和地图/图块数据加载。

#### 语法突出显示包

*   [RGBASM的 Atom 语言包](https://atom.io/packages/language-rgbasm)-RGBDS 汇编的 Atom 语法高亮显示。
*   [gbz 80-高亮显示](https://github.com/ISSOtm/gbz80-highlight) -记事本+-和 gedit 语法高亮显示 RGBDS 汇编文件。
*   [Game Boy 汇编程序的 Vim 语法文件 RGBASM](https://www.vim.org/scripts/script.php?script_id=819) -RGBDS 汇编程序的 Vim 语法高亮显示。
*   [RGBDS的 Vim 语法文件](https://github.com/Leandros/dotfiles/blob/master/.vim/syntax/rgbds.vim) -RGBDS 装配的另一个 Vim 语法高亮文件。
*   [sublime-rgbds](https://packagecontrol.io/packages/RGBDS) -Sublime Text 3 包用于 rgbds，包括语法突出显示和一些完成片段。
*   [Z80 汇编支持 Visual Studio 代码](https://github.com/Imanolea/z80asm-vscode)
*   [rgbds-vscode](https://github.com/DonaldHays/rgbds-vscode) -Visual Studio Code 语言扩展为 RGBDS GBZ80 汇编。
*   [rgbds-模式](https://github.com/japanoise/rgbds-mode) -用于 RGBDS 装配的 Emacs 主要模式。

### C

*   8 位仙境  ——关于 Game Boy 如何工作以及如何开始为其开发工作代码的精心编写的介绍性文档。
*   [Grooves Game Boy 编程](https://github.com/gbdk-salvage/grooves-game-boy-programming) ——一整套关于在 Game Boy 游戏中实现各种游戏机制的课程。
*   [如何编写一个简单的侧滚游戏](https://pastebin.com/F3tHLj68)——老(但仍然相关)教程。
*   [只是另一个简单的教程](https://pastebin.com/gzT47MPJ)
*   [GBDK 教程](https://refreshgames.co.uk/2016/04/18/gameboy-tutorial-rom/)——相当简单的 GBDK 入门游戏演示。
*   [GBDK 精灵](http://gbdev.gg8.se/wiki/articles/GBDK_Sprite_Tutorial) ——展示了一个让多个精灵显示和动画的工作流程。
*   [GBDK 颜色](http://gbdev.gg8.se/wiki/articles/GBDK_Color_Tutorial) -通过给精灵、背景和窗口层添加颜色，扩展您对GameBoy基本精灵的了解。
*   [GBDK 游戏手柄](http://gbdev.gg8.se/wiki/articles/GBDK_Joypad_Tutorial) -详细介绍 GBDK 游戏手柄的使用。
*   [Game Boy 首页的味道](https://web.archive.org/web/20210427064949/www.personal.triticom.com/~erm/GameBoy/)——一些完整的游戏和源码。
*   [GBDK 配置和编程教程](https://videlais.com/2016/07/03/programming-game-boy-games-using-gbdk-part-1-configuring-programming-and-compiling/)——配置 GBDK、使用磁贴、碰撞精灵、GBTD、GBMB、内存管理和 ROM 银行。
*   [简体 GBDK 示例](https://github.com/mrombout/gbdk_playground)
*   [GBDK 编程视频教程](https://www.youtube.com/playlist?list=PLeEj4c2zF7PaFv5MPYhNAkBGrkx4iPGJo) ——一系列视频教程，向初学者介绍用 GBDK 编程。

## 自制啤酒

完整的开源游戏。

*   [家酿中心](https://hh.gbdev.io) ——所有为 Game Boy online(mobile/touch too)制作的非官方家酿:社区领导的收集、存档和保存社区通过多年热情工作制作的所有非官方游戏、家酿、演示、补丁、Game Boy (Color)的黑客程序的尝试。

### 空对地导弹

*   [凝灰岩](https://github.com/BonsaiDen/Tuff.gb)
*   [2048-gb](https://github.com/Sanqui/2048-gb)
*   [蛇](https://bitbucket.org/Sanqui/snake/src/?at=master)
*   [lazer pang](https://github.com/huderlem/lazerpong)
*   [几何矩阵](https://github.com/AntonioND/geometrix)
*   [城市](https://github.com/AntonioND/ucity)
*   [Carazu](https://github.com/mholtkamp/carazu)
*   [Snake-gb](https://github.com/DonaldHays/snake-gb)
*   [GB303](https://github.com/furrtek/GB303) -基于 GB303 波表的 TB-303 风格的任天堂游戏机合成器。
*   [寿司](https://github.com/JustSid/Sushi)
*   [Flappy-boy-ASMT3】](https://github.com/bitnenfer/flappy-boy-asm)
*   [库普曼](https://github.com/dubvulture/gbdev) 等一些项目。
*   [Adjustris](https://github.com/tbsp/Adjustris)
*   [exeman](https://github.com/exezin/exeman/)
*   [](https://github.com/ISSOtm/Aevilia-GB)
*   -一个简单的GameBoy幻灯片浏览器。
*   [Pokered-gbc](https://github.com/dannye/pokered-gbc) -神奇宝贝红色翻拍，完全支持 gbc。
*   [ToyToy](https://github.com/tslanina/Retro-GameBoyColor-ToyToy)
*   [斯蒂芬](https://github.com/tslanina/Retro-GameBoyColor-StefaN) ——四路突围克隆。
*   [](https://github.com/tslanina/Retro-GameBoyColor-Galaxia)
*   [desgb](https://github.com/sanqui/desgb) - DES 加密。
*   [superhappyfunbubbletime](https://github.com/l0k1/superhappyfunbubbletime)
*   [扫雷 pGB](https://github.com/lancekindle/minesweepGB)
*   [Libbet 和魔楼](https://github.com/pinobatch/libbet) 打开
*   [波形-gb](https://github.com/dannye/waveform-gb) -程序可视化波形通道使用的波形。波形可以自由编辑，波形回放可以立即更新。
*   [vectroid.gb](https://gitlab.com/BonsaiDen/vectroid.gb)——用 gbasm 开发。
*   [PlantBoy](https://github.com/gb-archive/plantboy)
*   [死亡星球](https://makrill.itch.io/death-planet)
*   [四方](https://makrill.itch.io/quartet) -益智游戏为 Game Boy(彩色)和 Super Game Boy。
*   [担杆](https://snorpung.itch.io/dangan-gb)

### C

*   [FlappyBoy](https://github.com/bitnenfer/FlappyBoy)
*   [flappybird-game boy](https://github.com/pashutk/flappybird-gameboy)
*   [fbgb](https://github.com/gb-archive/fbgb)
*   [Novascape](https://web.archive.org/web/20171002042716/http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=6823)
*   [粘糊糊的乌龟](https://github.com/cppchriscpp/SquishyTheTurtle)
*   [](https://github.com/avivace/quadratino)
*   [医生如何](https://github.com/elfgames/doctorhow)
*   [超级公主' 2092 出埃及记](https://github.com/Zal0/gbjam2016) - ( [ZGB 引擎](https://github.com/Zal0/ZGB/) )。
*   [GBsnake](https://github.com/brovador/GBsnake)
*   [](https://github.com/andreasjhkarlsson/gb-mines)
*   [橙子](http://www.atari2600land.com/gameboy/oranges.html)
*   [赤热公主大屠杀](https://github.com/Imanolea/bitbitjam3_red_hot_princess_carnage)
*   [loder runner](http://www.tensi.eu/thomas/programming/gameboy/loderunner.html)
*   [蜂巢](https://refreshgames.co.uk/2017/04/24/ludum-dare-38-entry-hives/)
*   [泡工厂](https://github.com/DonaldHays/bubblefactory)-*香草- SDCC(无 gbdk)。
*   [GBC 雅达利拳击](https://github.com/rubfi/gbc-atari-boxing) -雅达利 2600 拳击克隆体(颜色为 Game Boy)。
*   [GB raycaster，Vision-8](https://github.com/haroldo-ok/really-old-stuff/tree/master/gameboy) ——以及其他一些项目。
*   [Tobu Tobu Girl 豪华版](https://github.com/SimonLarsen/tobutobugirl-dx)——一个街机平台的GameBoy(彩色)。
*   [魁梧大熊 vs 卑鄙狐狸](http://sebastianmihai.com/gameboy-burly-bear.html)([GBC](http://sebastianmihai.com/gameboy-color-burly-bear.html) 端口)
*   [PostBot](https://github.com/MasterIV/PostBot)
*   [枪械&骑手T3】](https://github.com/kanfor/gunsridersgameboy)
*   [迪诺的离线冒险](https://github.com/gingemonster/DinosOfflineAdventure)——谷歌 Chrome 离线游戏的克隆版。
*   [dino-gb](https://github.com/rnegron/dino-gb)——Chrome 游戏的另一个克隆版本。
*   [Evoland.gb](https://github.com/flozz/evoland.gb) ——Evoland 的第一级端口。
*   [Petris](https://github.com/bbbbbr/Petris)——一款以身材匀称的宠物为GameBoy色的益智游戏( [itch.io](https://bbbbbr.itch.io/petris) )。
*   [Infinity](https://github.com/gb-archive/infinity-gbc) - RPG 主要由 Affinix 软件在 1999 年至 2001 年间开发。游戏一直没有找到发行商，最终被取消。最近发布了完整的源代码、开发工具和工作流程。
*   [黑城堡](https://gbdev.gg8.se/forums/viewtopic.php?id=743)——GameBoy的侧滚平台( [itch.io](https://user0x7f.itch.io/black-castle) )。
*   [创世纪](https://gbdev.gg8.se/forums/viewtopic.php?id=674)-Shmup for the Game Boy([itch . io](https://user0x7f.itch.io/genesis) )。
*   [无损坦克！](https://antonylavelle.itch.io/indestructotank-gb)
*   [Super JetPak DX](https://pocketpixel.design/super-jetpak-dx-game-boy-rom.html)
*   [Powa！](https://aiguanachein.itch.io/powa) -GameBoy的侧滚平台(彩色)( [ZGB 引擎](https://github.com/Zal0/ZGB/) )。
*   [洞窟](https://thegreatgallus.itch.io/cavern-mvm-9) - ( [ZGB 引擎](https://github.com/Zal0/ZGB/) )。
*   [蒙娜与女巫的帽子豪华](https://ctneptune.itch.io/mona-and-the-witchs-hat-dx) - ( [ZGB 引擎](https://github.com/Zal0/ZGB/) )。
*   [弹跳球](https://gamejolt.com/games/the-bouncing-ball-gb/86699)
*   [DMG 造成伤害 开启新窗口](https://drludos.itch.io/dmg-deals-damage)

### GB Studio

*   [灵魂虚空](https://kadabura.itch.io/soul-void) -互动恐怖小说。
*   [Deadeus](https://izma.itch.io/deadeus)
*   [超级冒名顶替者](https://lumpytouch.itch.io/super-impostor-bros)

### 民众

*   [回色](https://github.com/AntonioND/back-to-color)
*   [beach-gbc](https://github.com/vegard/beach-gbc)
*   [可爱演示](https://github.com/mills32/CUTE_DEMO)
*   [`10 PRINT`GameBoy](https://github.com/svendahlstrand/10-print-game-boy)
*   [Roboto 演示](https://github.com/naavis/roboto-demo)
*   [matrix-rain-gb](https://github.com/wtjones/matrix-rain-gb) -汇编程序中的一个矩阵数字 rain 效果。
*   [GBVideoPlayer](https://github.com/LIJI32/GBVideoPlayer) ——这是一个技术演示，演示了如何入侵 Game Boy LCD 控制器，使 Game Boy Color 播放彩色的全运动视频，并伴有音乐。
*   [GBVideoPlayer2](https://github.com/LIJI32/GBVideoPlayer2)——上面演示的第二次迭代，增加了分辨率，增加了*立体声- PCM 音频，引入了视频压缩*。

## 逆向工程

*   [逆向工程柯比的幻境 2](https://ecc-comp.blogspot.it/2016/03/reverse-engineering-kirbys-dreamland-2.html)
*   [pokemontools](https://github.com/pret/pokemon-reverse-engineering-tools)——一个 python 模块，为各种 Pokémon 游戏提供各种逆向工程组件。
*   [用 radar 2逆向工程一个 Gameboy ROM](https://www.megabeets.net/reverse-engineering-a-gameboy-rom-with-radare2)——一个用 radar 2 逆向工程一个 Game Boy ROM 挑战的演练。
*   [拆链接的觉醒](http://kemenaran.winosx.com/posts/category-disassembling-links-awakening/)——一系列关于拆链接的觉醒的博文 DX。
*   [逆向工程 GameBoy 俄罗斯方块](https://github.com/h3nnn4n/Reverse-Engineering-the-GameBoy-Tetris)
*   [DMA 劫持](https://gbdev.io/articles/dma_hijacking) ——一种简单的技术，允许你在大多数 GB/SGB/CGB 游戏中运行自定义代码，前提是你有 ACE 漏洞。

### 游戏拆卸

*   [神奇宝贝红/蓝](https://github.com/pret/pokered)
*   [神奇宝贝水晶](https://github.com/pret/pokecrystal)
*   [神奇宝贝黄色](https://github.com/pret/pokeyellow)
*   [神奇宝贝金银T3】](https://github.com/pret/pokegold)
*   [神奇宝贝弹球](https://github.com/pret/pokepinball)
*   [神奇宝贝 TCG](https://github.com/pret/poketcg)
*   [pokegold-Space World](https://github.com/pret/pokegold-spaceworld) - Pokémon 金银 1997 Space World demo。
*   [链接的觉醒 DX](https://github.com/mojobojo/LADX-Disassembly)
*   [甲骨文](https://github.com/drenn1/ages-disasm)
*   [俄罗斯方块](https://github.com/vinheim3/tetris-gb-disasm)——完成俄罗斯方块的拆解。
*   [FX 锤](https://github.com/DevEd2/FXHammer-Disasm)
*   [秋月 3](https://github.com/sanqui/hm3)

## 游戏机相机

### 检索图像

Game Boy 打印机模拟(例如从相机中检索图像):

*   [Arduino Gameboy 打印机模拟器](https://github.com/mofosyne/arduino-gameboy-printer-emulator) -通过 Gameboy 连接线模拟 gameboy 打印机。
*   [ESP8266 Game Boy 打印机](https://github.com/applefreak/esp8266-gameboy-printer) -一款模仿 Game Boy 打印机的设备，让你使用 ESP8266 供电的 WiFi 检索图像。
*   [WiFi GBP 模拟器](https://github.com/HerrZatacke/wifi-gbp-emulator) -一个 GameBoy 打印机模拟器，它通过 WiFi 连接提供接收到的数据。
*   [Game Boy WiFi 打印机- D1 Mini Shield](https://github.com/cristofercruz/gbp-esp-shield-pcb) - Game Boy 打印机接口 Shield 为 D1 mini/mini Pro ESP8266 板卡。
*   [游戏机打印机嗅探器](https://github.com/mofosyne/GameboyPrinterSniffer) ——嗅探游戏机和打印机之间的数据包通信。

### 改变摄像机的行为

改善和/或操作摄像机质量和性能的方法:

*   [Game Boy 相机佳能 EF 镜头挂载](http://ekeler.com/game-boy-camera-canon-ef-mount)
*   [将 Game Boy 相机装上 佳能镜头](https://www.thingiverse.com/thing:4337362)——基于以上。
*   [game-boy-camera-frame-replacer](https://github.com/cristofercruz/game-boy-camera-frame-replacer)——操纵相机的 ROM 以包含自定义帧

### 后加工

*   [Game Boy Printer Paper Simulation](https://github.com/mofosyne/GameboyPrinterPaperSimulation) -生成数码打印图像的仿印图像。
*   [Game Boy Printer Web](https://github.com/HerrZatacke/gb-printer-web)-Gallery app for to the Game Boy camera:从导出或墨盒转储中导入图片并选择调色板。

## 相关项目

*   [GB Studio](https://www.gbstudio.dev/) ——简单的拖放游戏创建者，无需任何知识，可视化脚本。
    *   [资源入门](https://gbstudiocentral.com/resources/)
    *   [敬业不和](https://discord.gg/knRryZWGcm)
*   [ArduinoBoy](https://github.com/trash80/Arduinoboy) -从 Arduino 到 Game Boy 的串行通信(MIDI)，用于 LittleSoundDJ、Nanoloop 和 mGB 等音乐应用。
*   [papiGB](https://github.com/diegovalverde/papiGB) ——Game Boy 经典全功能 FPGA 从头实现。
*   [fpgaboy](https://github.com/trun/fpgaboy) ——在 FPGA 上实现任天堂的游戏机。
*   小猪  ——一个 LUA 驱动的人工智能，使用实验玩经典GameBoy颜色游戏。正在开发中。
*   [鸵鸟](https://github.com/PumpMagic/ostrich) ——一个用 Swift 编写的GameBoy音响系统播放器。
*   [mGB](https://github.com/trash80/mGB) -一个 Game Boy 卡带程序，使 Game Boy 能够充当完整的 MIDI 支持的声音模块。
*   [GBVisualizer](https://github.com/LIJI32/GBVisualizer) ——演示两个未记录的 Game Boy 颜色寄存器的使用，昵称为 PCM12 (FF76)和 PCM34 (FF77)，可用于读取 4 个 APU 通道的当前 PCM 幅度。
*   [ArduinoGameBoy](https://github.com/drhelius/arduinogameboy) ——基于 Arduino 的 GameBoy 卡带读写器。
*   [gameboy-brain fuck](https://github.com/bitnenfer/gameboy-brainfuck) - Brainf*ck 解释器。
*   [gbfk](https://github.com/elseyf/gbfk) - Brainf*ck 解释器，带输入。
*   [GB-保存状态](https://github.com/mattcurrie/gb-save-states) -补丁增加 Game Boy 游戏在原硬件上玩时的保存状态支持。
*   [gbcpu](https://github.com/jdeblese/gbcpu) -实现 Game Boy 指令集和功能的 cpu 和外设。
*   [数字化语音在 Game Boy 游戏中](https://youtube.com/watch?v=1lzHfLYzyRM)
*   [用 STM32F4 嗅探 Game Boy 串行流量](https://dhole.github.io/post/gameboy_serial_1/) 打开
*   [用 STM32F4 虚拟游戏机打印机](https://dhole.github.io/post/gameboy_serial_2/) 打开
*   [使用 STM32F4 在 Game Boy 打印机上打印](https://dhole.github.io/post/gameboy_serial_3/)
*   [用 STM32F4 编程 Game Boy 中文墨盒](https://dhole.github.io/post/gameboy_cartridge_rw_1/) 打开
*   [口袋妖怪口袋电脑:](https://tilde.town/~minerobber/techwriteups/pokemonpc.html)——它是什么，如何用它制作作弊码。
*   [用自定义 logo 引导 Game Boy](https://dhole.github.io/post/gameboy_custom_logo/) ——绕过任天堂 logo 检查。
*   2017 年制作 Game Boy 游戏:一个“羊起来！”剖验([部分 1](https://www.gamasutra.com/blogs/DoctorLudos/20171207/311143/) ，[部分 2](https://www.gamasutra.com/blogs/DoctorLudos/20180213/314554/) )
*   任天堂的假标识  ——每个墨盒都必须显示真实标识才能被认为有效并被运行，但显然一些公司成功利用了检查系统。
*   [liblsdj](https://github.com/stijnfrishert/liblsdj) -与 lsdj 保存格式交互的实用程序库(。sav)、歌曲文件(。lsdsng)等。
*   [lsdpatch](https://github.com/jkotlinski/lsdpatch) -用于修改 LSDj ROM 图像上的样本、字体和调色板的工具。
*   [Game Boy 视频特效](https://github.com/ChaosCabbage/crazy-gameboy-video-experiments)——一些使用 STAT 中断做搞笑视频操作的小实验。
*   [gbos](https://github.com/ekimekim/gbos) ——Game Boy 的基本操作系统。
*   [工作主操作系统](https://translate.google.com/translate?hl=&sl=ru&tl=en&u=https%3A%2F%2Fweb.archive.org%2Fweb%2F20081226145726%2Fhttp%3A%2F%2Fworkmaster.ru%2Findex.php%3Fp%3D8&sandbox=1) -俄语多任务操作系统。
*   [Game Boy Link 线缆转接板](https://github.com/Palmr/gb-link-cable)
*   [gbcartflaster 固件](https://github.com/Tauwasser/GBCartFlasher)
*   [VerilogBoy](https://github.com/zephray/VerilogBoy/)——Game Boy 兼容控制台 Verilog RTL 实现。
*   [GBCamcorder](https://github.com/furrtek/GBCamcorder) -使用 GameBoy 摄像盒的 Lo-Fi 便携式录像机。
*   [GBCartRead](https://github.com/insidegadgets/GBCartRead) -从/向 GameBoy 卡盒读取 ROM、读取 RAM 或写入 RAM。
*   [GBxCart-RW](https://github.com/insidegadgets/GBxCart-RW) -通过 USB 从您的 PC 读取游戏 rom、保存游戏和恢复 GB、GBC 和 GBA 购物车的保存的设备。
*   [倾倒超级游戏王开机 ROM](https://www.its.caltech.edu/~costis/sgb_hack/)

### 目录

*   [归档相关文件](http://gbdev.gg8.se/files/)
*   [Game Boy 档案](https://github.com/gb-archive) ——一个关于 Game Boy 相关软件、硬件和文献的图书馆。旨在反映和保存过去三十年来旧的和零散的贡献。
*   [Game Boy Archive-Salvage](https://github.com/gb-archive/salvage) -软件、旧文章、常见问题及各种文档的历史档案。

### 网站

*   [devrs](http://devrs.com/gb)——旧居的场景:例子、来源、完整的文档、指南、教程和各种工具。
*   [pdroms.de](http://pdroms.de/news/gameboy/) ——Game Boy 发布。
*   [手持地下](http://hhug.me)——未授权游戏，关于 Game Boy 的博文，hhugboy 模拟器之家。
