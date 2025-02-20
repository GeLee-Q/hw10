# 高性能并行编程与优化 - 第0x讲的回家作业

通过 pull request 提交作业。会批分数，但是：

没有结业证书，回家作业仅仅作为评估学习效果和巩固知识的手段，不必为分数感到紧张 :)
量力而行，只要能在本课中，学到昨天的自己不懂的知识，就是胜利，没必要和别人攀比。
注意不要偷看别人的作业哦！

- 课件：https://github.com/parallel101/course
- 录播：https://space.bilibili.com/263032155

作业提交时间不限 :) 即使完结了还想交的话我也会看的~ 不过最好在下一讲开播前完成。

- 如何开 pull request：https://zhuanlan.zhihu.com/p/51199833
- 如何设置 https 代理：https://www.jianshu.com/p/b481d2a42274

## 评分规则

- 完成作业基本要求 50 分（详见下方"作业要求"）
- 能够在 ANSWER.md 中用自己的话解释 25 分
- 代码格式规范、能够跨平台 5 分
- 有自己独特的创新点 20 分
- 明显抄袭现象 -100 分

## 作业要求

修改 main.cpp，改良其中的康威生命游戏模拟器（使用稀疏数据结构，高效利用内存），回答注释中的问题，并保证输出的答案正确。

测试的结果和你的优化思路，请填到 ANSWER.md。

温馨提示：如果用了 IDE，记得统一开启 Release 模式来比较性能。

## 关于内卷

如果你自己实现了哈希表而没有用标准库，或是结合第七课知识用了 `_mm_stream_ps`，或是用了莫顿序分块的，用了局部数组实现 loop fusion：
只要是在 **满足作业要求的基础** 上，这是件好事！
老师会酌情加分，视为“独特的创新点”，但最多不超过 20 分。
