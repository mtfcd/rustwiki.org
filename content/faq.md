+++
title = "FAQ"
description = "关于 Rust Wiki、Rust 语言、Rust 中文社区和 Rust 教程，以及 Rust 学习和 Rust 文档翻译的相关常见问题。"

[extra]
lead = "关于 Rust Wiki、Rust 语言、Rust 中文社区和 Rust 教程的相关常见问题"
id = "kube-faq"
+++

## Rust Wiki 是什么网站？

Rust Wiki 是非营利性的关于 Rust 教程的中文资源网，由 [Rust 中文翻译项目组][rust-lang-cn]创建。我们深受 Rust 开发团队的影响，Rust 开发团队以前所未有的开放形式开发出 Rust 语言，并给出了全面且规范的开源组织范例。Rust 官方的网站还提供了一系列全面的文档，不过目前为止只有英文版。

正因于此，我们创立了 Rust Wiki 网，也将各类纷繁复杂的资源收拢在一起，从而更好地将中文资源呈现给大家。就像 Rust 官方一样，在 Rust 的官网上就能找到重要的英文的 Rust 资源，Rust Wiki 也努力做到本站涵盖 Rust 中文的相关重要资源。我们的所有资源都以开源的形式提供，在 [GitHub][rust-lang-cn] 上均可以找到相关资源，包括[本网站的所有源码、文档和文章][rustwiki]，如无特别声明，本网站的源码和文章均遵循 [MIT 协议][mit]。

本网站主要采用的是 Rust 相关的工具链完成:

- 网站使用 [Zola][zola] 技术制作，Zola 是一个使用 Rust 语言编写的具有极速生成速度的静态网站生成器;
- 网站的 Logo 来自 [Rust 官方的多媒体资源][rust-logo];
- 网站的主题包含两部分：
  1. 第一部分是主站，采用的是 [kube 主题][kube] 来构建页面；
  2. 第二部分是 Wiki 站，采用的是 [EasyDocs 主题][zola-easydocs-theme] 来构建。

[rust-lang-cn]: https://github.com/rust-lang-cn
[rustwiki]: https://github.com/rust-lang-cn/rustwiki.org
[zola]: https://www.getzola.org
[rust-logo]: https://github.com/rust-lang/rust-artwork
[kube]: https://kube.elemnts.net/
[zola-easydocs-theme]: https://www.getzola.org/themes/zola-easydocs-theme/
[mit]: https://mit-license.org/

## Rust Wiki 的中文资源来源于哪里？

Rust Wiki 的中文教程等相关资源主要来源于两方面：

1. Rust Wiki 自身的组织，即 Rust 中文翻译项目组完成的翻译作品，比如[《通过例子学 Rust》][rbe]和[《Rust 版本指南》][edition-guide]；
2. 源自组织外的 Rust 翻译作品，如[《Rust 程序设计语言》][book]。

我们遵循 “DRY”（Don't Repeat Yourself）原则，以减少不必要的重复劳动。一般来说，组织都会计划翻译 Rust 官方的作品，若是发现已经有别处给出了译作，我们将采用可取的作品，比如第二版的《Rust 程序设计语言》本组织也翻译了前几个章节，后面发现有更完整的翻译成品，所以本组织整合已有的资源而不再重新翻译，我们欢迎所有的 Rust 中文翻译作者加入翻译项目组。

Rust 中文翻译项目组会不断收集和更新网上已有的开源的翻译文档，并将相关资源聚集到 [*rust-lang-cn*][rust-lang-cn] 的 GitHub 仓库上，且遵循原作者和译者的相关协议。我们的目标是将所有的公开的开源作品都无限制（比如 CC0 协议）或少数限制（比如 MIT、GPL 等协议）分享给全世界所有人。所有人都可以在遵循开源协议的条件下，获得所有这些开源资源，包括本网站的一切资源内容，甚至我们不反对将这些开源的资源全部复刻到自己的网站上，因为我们本来的目的就是让 Rust 的中文资源能更广泛地传播。

当然，为了让相关的资源良性发展和不断改进，我们鼓励大家将改进的内容反馈到原作者，当然也欢迎反馈到 [*rust-lang-cn*][rust-lang-cn] 的有关资源内容，[*rust-lang-cn*][rust-lang-cn] 组织也对所有人开放。

⚡️ 注意：Rust 中文翻译项目组的作品一般采用 MIT 或 Apache 2.0 协议，除非特定教程使用了其他不兼容的许可协议（如 GPL 和 CC BY-SA-4.0 等协议）。另外对于以指定禁止转载或闭源形式公开的作品，我们项目组不会采用。

[rbe]: https://rustwiki.org/zh-CN/rust-by-example
[edition-guide]: https://rustwiki.org/zh-CN/edition-guide
[book]: https://rustwiki.org/zh-CN/book
[rust-lang-cn]: https://github.com/rust-lang-cn

## Rust 中文项目组有什么目标和计划？

我们的总体目标是构建一个完整且完善的 Rust 中文知识库，为此我们会翻译所有必要的 Rust 官方资源以及部分非官方的 Rust 资源，这也是我们的总的计划，但并未给出时间表。为了达成这个目标，我们会一步步翻译相关的作品，目前我们已经翻译了部分重要的作品，未来还需要进一步翻译。

对于具体的翻译作品而言，我们会给出特定的计划和说明，在相关的作品说明页会有说明。

## 如何加入 Rust 中文项目组？

Rust 中文项目组是一个开放的组织，我们欢迎每一个热爱 Rust 的人加入，并一起朝着组织的目标一步步完善 Rust 的中文知识库。加入组织前，请确保已经注册了 [GitHub][github] 账号并熟悉 Git 工具，因为我们的资料内容均采用 Git 工具和 GitHub 托管平台来进行编写。

[github]: https://github.com

## 我想为 Rust Wiki 提交博客文章或技术分享文章，如何投稿？

Rust Wiki 网站会不定期发表博客文章，我们欢迎所有人为 Rust Wiki 网站投稿。注意我们网站的博客只发表关于 Rust 编程相关的内容，比如 Rust 的技术分享的文章、翻译 Rust 英文技术文章，或是 Rust 的新闻资讯相关的文章等等。若是有这类文章，请随时在在本站仓库中[创建一个新的 PR][pr]，只要文章内容合适、格式符合规范，我们都会快速合并到主分支并更新网站。

[pr]: https://github.com/rust-lang-cn/rustwiki.org/pulls

## 我该如何学习 Rust？

这个问题没有统一的答案，因为每个人的知识结构（数学、英语等）以及编程能力各不相同，不同人的学习方式也不尽相同。总的来说，学习 Rust 分两类：

- 有其他编程语言的基础，比如已经熟悉 C、C++、Python 等，那么最好的学习方式是通过项目驱动型来学习，比如通过《Rust 程序设计语言》中的[“猜数字游戏”][guessing-game]这个章节了解 Rust 的大概全貌，在此基础上不断拓展了解 Rust 的各个知识点。
- 没有编程基础。这种情况下学习 Rust 可能会稍感觉有点难，也有一些人提到 Rust 不太适合作为第一门编程语言来学习，这是因为 Rust 的概念相对比较多，要快速掌握并写出一些有成绩的代码并不太容易，但是确实想将 Rust 作为第一门语言来学习不是不可以。这种情况下就需要按照官方的《Rust 程序设计语言》和《通过例子学 Rust》一步步熟悉各个编程的概念，多看多思考多写代码，不断总结和深入。

以上只是给出一些通用建议，但学习是一种很主观的行为，个人应该选择或尝试出最适合自己的学习方式。

在有一定的基础后，我们还可以通过去一些编程平台（如 LeetCode）使用 Rust 语言来编写相关算法，找一些合适的 Rust 项目（比如一些 crate 项目）的源码来阅读学习。

相关资料：

- [《Rust 程序设计语言》][book]
- [《通过例子学 Rust》][rbe]
- [Rust 小练习][rustlings]
- [crates.io][crates]
- [LeetCode][leetcode]

[guessing-game]: https://rustwiki.org/zh-CN/book/ch02-00-guessing-game-tutorial.html
[rustlings]: https://github.com/rust-lang-cn/rustlings-cn
[crates]: https://crates.io/
[leetcode]: https://leetcode-cn.com/

## 我要学习或入门 Rust，看中文教程还是英文教程？

最重要是看自己的英文水平。若是英语水平足够好，建议直接看英文的文档。若是直接看英文吃力，可以选择看中文的文档，这种在学习 Rust 的过程中逐渐看一些英文文档，慢慢加强自己的英文水平。

但是对于大多数国人来说，看英文的能力都会差于看中文的能力，特别是快速浏览了解内容的能力，这些能力是需要慢慢锻炼提高的。我们创建 Rust Wiki 网并翻译 Rust 资源，也有一部分这样的原因。我们提供越来越完善的中文资料，丰富中文知识的同时，也为我们更多英语不好的人能够通过中文的译文来快速了解 Rust 的概要。

另外，为了方便大家学习，**本站特别开发了官方文档中英双语切换的功能**，可以看中文的时候随时切换到相同的英文页面，也能够阅读英文页面的时候随时切换到中文，对于想直接看英文文档又需要对照中文的朋友来说特别方便。其中英文文档每天都会自动同步一次官方的最新版本，确保英文资料的准确性和时效性。

我们也希望更多热爱 Rust 的人加入 Rust 中文翻译项目组，共同打造出更丰富的 Rust 中文知识库。

## 为什么语言切换跳转回来找不到页面？

在阅读文档的时候，有时发现从英文文档切换回中文文档时，发现提示页面找不到的情况。出现这种情况一般来说是因为英文的翻译添加了新的章节文件内容，而中文还未翻译出对应的章节文件，所以出现中文文档找不到对应的页面。

还有一种可能是官方的文档删除了章节，导致中文文档切换过去找不到页面。这会在一些官方不是特别重要的文档中可能出现这样的会这样，因为官方对这些文档未进行旧页面的重定向处理。而对于官方几个重要的文档，比如《Rust程序设计语言》一书，已经做了移除文档的重定向的跳转。

出现这些跳转异常的情况，可以发送邮件 <aaranxu@outlook.com> 第一时间报告给我们。

## 我想认领 Rust 相关文档的翻译，如何进行？

我们非常欢迎您提出认领文档翻译，官方的文档很多，而目前我们由于人力和精力有限，只能维护较少的文档，主要是《Rust 程序设计语言》和《通过例子学 Rust》两书，而其他文档基本没太多时间去更新和维护，您的加入将给我们 Rust 中文翻译工程带来巨大的帮助，可以随时到 [Rust 中文翻译项目组的 GitHub 组织](https://github.com/rust-lang-cn) 找到对应的仓库提出 Issue，或是直接在未翻译完的文档页面点击仓库进入提出 Issue。

你也可以随时拉取组织上的相应仓库进行翻译，并向我们发起 PR 请求，我们更热切欢迎您加入到 *rust-lang-cn* 组织中来，也可以对单独某个或某几个仓库加入管理和更新的权限。

我们 Rust 中文翻译项目组始终以敞开的姿态欢迎来自全国各地以及世界各地的朋友，我们的愿景就是丰富 Rust 的中文开放的资源知识库，让 Rust 的中文知识也能向英文那样，不断丰富拓展，自由传播，不让 Rust 的编程知识受限。

## 我想翻译 Rust 的文章，有什么好的指导建议吗？

请参阅 [Rust 文档翻译指引][translation-guide]，我们将不断完善整个社区翻译的指南，让更多人更好地翻译出 Rust 的相关的作品。

[translation-guide]: https://rustwiki.org/wiki/translate/rust-translation-guide/

## 发现网站文章或文档有错误，如何报告？

如果发现本站的文章有错误的话，可以随时到本站的源码仓库报告 Issue 或是直接修改 PR，我们会特别重视您的纠正，将会第一时间更新本站的网站。

如果发现文档上的错误，可以直接点击文档右上角处进入到文档对应的源文件，可以[直接进行修改和 PR][report]。另外在文档中英文切换过程中，出现 404 页面，说明中文版暂未翻译对应的英文文档页面，也可以直接在中文项目文档的对应仓库上提出 Issue。

Rust 中文翻译和开源发展，离不开大家的支持和鼓励，我们希望更多人踊跃参与到 Rust 中文的开源行动中来，帮助 Rust 创建出完善的中文知识库，让每个国人都能通过中文学习到较为全面和深入的 Rust 知识体系。

[report]: https://github.com/rust-lang-cn/rustwiki.org
