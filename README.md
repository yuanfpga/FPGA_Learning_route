<h1 align="center">FPGA学习路线整理</h1>

收集整理FPGA资料帮助大家进行FPGA的入门，分享FPGA路线、相关的书籍、学习网站等。

# 学习路线

找到的比较优质的学习路线，值得在学习到不同阶段反复观看，每次看都有不一样的体会！

1. [如何学习FPGA(by队长-Leader)](https://blog.csdn.net/k331922164/article/details/44626989?spm=1001.2014.3001.5506)

2. [FPGA学习路线视频入门篇(by老石)](https://www.bilibili.com/video/BV1aK4y1E7nc/?spm_id_from=333.337.search-card.all.click&vd_source=b9f12a3e5aa727d9bbd667d8ff4b9193)
3. [FPGA学习路线视频进阶篇(by老石)](https://www.bilibili.com/video/BV11y4y1i7Lv/?spm_id_from=333.337.search-card.all.click&vd_source=b9f12a3e5aa727d9bbd667d8ff4b9193)

![在这里插入图片描述](https://img-blog.csdnimg.cn/36efed42417645fe89e6bddecfac3b5f.png)

![在这里插入图片描述](https://img-blog.csdnimg.cn/38828545c50946d0b91387c46adc6e1c.png)

# 书籍推荐

(1) 数字电路工具书：对数字电路的某些专业术语、符号表示、语言描述不太明了时，就可以翻阅数字电路基础的相关工具书进行查阅式学习。

1. 《零起步轻松学数字电路》，人民邮电出版社，蔡杏山、蔡玉山主编。这本书讲解 的内容非常基础，从最简单的门电路到 AD/DA 的应用介绍都做了很详细的描 述，非常适合没有数字电路基础的初学者入门学习。 
2. **《数字电子技术基础》**，高等教育出版社，阎石主编。作为高校数字电路教学的指定教材，对于很多同学来说是相当熟悉而富有亲切感。该书讲解的内容较为全面且详细，十分注重理论部分的讲解，其内容几乎涵盖了所有数字电路的基础部分，从 MOS 管到 FPGA 基础都有涉及，可谓是经典中的经典。

(2) 详解 Verilog 语法和 FPGA 知识点的工具书：推荐这类书的主要目的是希望学习者能够在初学时进一步了解 FPGA 是什么，怎么个工作原理，并在学习 Verilog 语法的时候有一本可以参考的工具书以供随时翻阅，毕竟初学的时候不一定能够一下子把所有的关键词和语法都记住，写的代码多了、翻书翻的多了自然就够熟能生巧。 这类书就像是 FPGA 的百科全书一样，在学习FPGA 的时候随手一本能够及时的答疑解惑。

1. **《Verilog 数字系统设计教程》**，北京航空航天大学出版社，夏宇闻主编。这本书 由业内元老北航夏宇闻教授所撰写，被十一五规划列为高校指定教材。因为书出 的比较早，而且当时国内关于 FPGA 的资料较少，所以这本书也是很多业内技术 大牛的 FPGA 启蒙书。该书从 FPGA 是什么、硬件结构、设计验证方法、Verilog 语法、建模方式、各种类型的应用案例等都做了详细的讲解。因为这本书讲的太 全面，内容过多，很容易把初学者搞晕，本来内容丰富的教材是好的，但是尺度 把握不好也会适得其反，要把最重要最基础先讲给初学者，再去提高才会更容易 让初学者接受。 
2. 《设计与验证：Verilog HDL》：这本书相对于夏教授的书来说内容上做了精简， 全书 200 页左右，其主要内容更易于初学者接受，可作为初学者的参考工具书。 书中对一些重要的知识点，比如开发流程、验证方法、可综合语法和不可综合语 法、发展趋势等都有比较详细的介绍和说明，是一本不错的启蒙工具书。详解 FPGA 开发流程的工具书：这类书的重点就不再是语法了，而是开发流程，着 重讲解了 FPGA 开发过程中的一些常见问题，有助于更加深入全面的提高初学者 对 FPGA 的认识，进一步拓宽初学者的视野，为 FPGA 学习者进阶之路做铺垫。

(3) 详解 FPGA 开发流程的工具书：这类书的重点就不再是语法了，而是开发流程，着重讲解了 FPGA 开发过程中的一些常见问题，有助于更加深入全面的提高初学者对 FPGA 的认识，进一步拓宽初学者的视野，为 FPGA 学习者进阶之路做铺垫。 

1. **《FPGA 设计指南：器件、工具和流程》**，人民邮电出版社，杜生海、刑闻译。这本书是国外工具书的翻译版，其中对 FPGA 的前世今生和内部结构都做了很详细 的讲解，还包括全套的设计流程、开发工具的使用、器件的选型、常用术语的介 绍和一些高级应用，可以说是一本除了语法之外的 FPGA 百科全书，该书的讲解 角度也有别于其他工具书，很有特色。

 (4) 详解 Xilinx IP 核的工具书：为了缩短开发周期，工程师往往会选择使用一些好用 又省事的 IP 核。网上关于 IP 核的资料都是一些工程笔记，资料比较分散、内容不够全面，虽然直接阅读英文的官方手册是最好的方法，但对于经验不足的初学 者来说较难抓到虽然手册重点，从而增加学习的难度，所以在此学习者推荐一本详解 IP 核的工具书。

1. **《Xilinx 系列 FPGA 芯片 IP 核详解》**，电子工业出版社，刘东华主编。该书几乎覆 盖了 ISE 中所有常用的免费 IP 核，是市面上关于 IP 核总结较为全面的一本工具书，该书对 IP 核的设置、使用方法都进行了详细的讲解，这能使学习者节省大量 的开发时间。
1. **《Altera系列FPGA芯片IP核详解》**

(5) 详解 Modelsim 仿真的书：关于仿真其实大家只需要会一些基本的操作和应用就可以了，但是如果需要使用 Modelsim 更强大的功能还需要找一本 Modelsim 相关的工具书作为参考，当你能够熟练使用 Modelsim 的时候一定会大大提高开发效率。

1. **《Modelsim 电子系统分析及仿真》**，电子工业出版社，于斌、米秀杰主编。该书 主要是介绍 Modelsim 的使用和操作，从能够满足最基本仿真需求的操作到更高级的应用操作都有很详细的介绍，看完本书后你会感慨 Modelsim 的强大，才真正体会到为什么 Modelsim 作为一个第三方仿真工具却是无数 FPGA 工程师的选择。

(6)Verilog硬件描述语言IEEE官方手册

# 学习网站

## 刷题

[HDLBits](https://hdlbits.01xz.net/wiki/Problem_sets)

[HDLBits 中文导学](https://zhuanlan.zhihu.com/c_1131528588117385216)

[HDLBits答案参考](https://github.com/Shengrong-LSR/HDLBits-Solutions-Verilog) (对比与其他答案，都比较频繁地存在表达式没有化到最简（从卡诺图的几道题可以看出）、思路繁冗（几道偏复杂的题中可以看出）等问题。可以多参考不同人的答案，综合一下。

[HDLBits答案参考](https://blog.csdn.net/m0_61298445/article/details/126853052?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522168837832716800180678899%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=168837832716800180678899&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_click~default-2-126853052-null-null.142^v88^control,239^v2^insert_chatgpt&utm_term=HDLBits&spm=1018.2226.3001.4187)



[牛客网Verilog题库](https://www.nowcoder.com/exam/oj?page=1&tab=Verilog%E7%AF%87&topicId=353)

## 常用

[菜鸟Verilog教程](https://www.runoob.com/w3cnote/verilog-tutorial.html)：语法速查。

[Fpga4fun](https://www.fpga4fun.com/):基础项目和进阶项目网站。

## FPGA资源整理项目

包括FPGA网站，工具安装包，教学视频，开源项目的整理等。

[FPGA资源整理](https://github.com/LeiWang1999/FPGA)

## 学习网站汇总

[学习网站汇总](https://www.zhihu.com/question/348990787/answer/2921448755)

# 学习点

FPGA芯片结构

FPGA片上资源

状态机FSM(组合+时序)

IP核的配置和使用：PLL、FIFO、存储器、软核NIOS、以太网控制器MAC/PHY、PCIe、DDR

接口应用    如：UART、SPI、I2C、USB、JTAG、SD card、SDRAM、PCIE、DDR、HDMI、CAN、Rapid l0、TCP/IP、SPI4.2(10G以太网接口)、SATA、光纤、DisplayPort。

高速接口：PCle、以太网

总线：DDR、AXI

跨时钟域处理

**掌握设计方法和设计原则**：学会同步设计原则、优化电路，是速度优先还是面积优先，时钟树应该怎样设计，怎样同步两个异频时钟等等。学会加快编译速度（增量式编译、LogicLock），静态[时序分析](http://blog.csdn.net/k331922164/article/details/48687161)（[timequest](http://wenku.baidu.com/link?url=f55u1aL6d5XKysDuD4keltciKNk46aUXn39IF0hINNjaTqHxOeh34PfZDkudvU3JuI1RuwT9DPsow_kRFe9qhWYZbG7uWVo-AoAAylvlLP3)），嵌入式逻辑分析仪（[signaltap](http://blog.csdn.net/k331922164/article/details/47623501)）

使用MATLAB仿真

信号处理 

验证

RISC-V

# 竞赛

FPGA创新赛：8月左右

全国大学生集成电路创新竞赛：3月左右

研电赛：6月左右