这是 C++ 之父 Bjarne Stroustrup 的 [HOPL4 论文](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf)的中文版。

[HOPL](https://dl.acm.org/conference/hopl) 是 History of Programming Languages（编程语言历史）的缩写，是 [ACM](https://www.acm.org/)（Association of Computing Machines，国际计算机协会）旗下的一个会议，约每十五年举办一次。Bjarne 的这篇论文是他为 2021 年 [HOPL IV 会议](https://hopl4.sigplan.org/)准备的论文，也是他的第三篇 HOPL 论文。在这三篇前后间隔近三十年的论文里，Bjarne 记录了 C++ 的完整历史，从 1979 年到 2020 年。这篇 HOPL4 论文尤其重要，因为它涵盖了 C++98 之后的所有 C++ 版本，从 C++11 直到 C++20。如果你对更早期的历史也感兴趣的话，则可以参考[他的其他 HOPL 论文](https://www.stroustrup.com/papers.html)，及他在 1994 年出版的《C++ 语言的设计与演化》（*The Design and Evolution of C++*）。

鉴于这篇论文对于 C++ 从业者的重要性，[全球 C++ 及系统软件技术大会](http://cpp-summit.org/)的主办方 [Boolan](http://boolan.com/) 组织了一群译者，把这篇重要论文翻译成了中文，让 C++ 开发人员对 C++ 的设计原则和历史有一个系统的了解。下面是论文的一级目录：

1. [前言](01.md)
2. [背景：C++ 的 1979–2006](02.md)
3. [C++ 标准委员会](03.md)
4. [C++11：感觉像是门新语言](04.md)
5. [C++14：完成 C++11](05.md)
6. [概念](06.md)
7. [错误处理](07.md)
8. [C++17：大海迷航](08.md)
9. [C++20：方向之争](09.md)
10. [2020 年的 C++](10.md)
11. [回顾](11.md)

参加论文翻译工作的译者有（按拼音序）：

- 陈常筠
- 高辉
- 何荣华
- 何一娜
- 侯晨
- 侯金亭
- 彭亚
- 王奎
- 王绍新
- 吴咏炜
- 徐宁
- 杨文波
- 于波
- 余水清
- 翟华明
- 章爱国
- 张云潮

论文翻译的校对和体例统一工作由吴咏炜、杨文波、张云潮完成。最后的发布由吴咏炜完成。

我们翻译的是论文的正文部分，英文原文超过 140 页。最后的参考文献部分，由于翻译的意义不大，没有译出。不过，这也带来了一个小小的负面后果：虽然我们对论文内部的交叉引用可以用脚本生成链接，但对指向参考文献的链接就完全无能为力了。所以，如果想要阅读参考文献的话，只能请你到[英文原文](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf)结尾的 References 部分自行查找了。

翻译过程中我们发现了一些原文中的小问题，并在译文中进行了修正或标注（绝大部分已经经过 Bjarne 老爷子确认）。当然，在翻译过程中引入翻译错误或其他技术问题，恐怕也在所难免——不过，跟 ACM 上发表论文不同，这个网页仍然是可以修正的。所以，如果你，亲爱的读者，发现问题的话，请不吝提交 pull request，我们会尽快检查并进行修正。
