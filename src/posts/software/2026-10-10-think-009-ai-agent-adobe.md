---

title: AI 把 Adobe 的饭碗给砸了？
date: 2026-10-10
categories: [software]
tags: [think, software, sh]
published: true
---

## AI 把 Adobe 的饭碗给砸了？

大家好，我是老马。

这两天在 GitHub 看到了开源版本的 Adobe 全家桶，第一反应是：AI 这是把 Adobe 的饭碗给砸了？

另一个叫 REA 的项目，正在尝试让 AI Agent 分析现有软件，从程序结构、运行行为一路研究到原生二进制。

一个帮 AI 研究别人怎么做软件，一个用 AI 尝试重做成熟软件。

接下来，和大家一起看下一个软件到底能不能被复制？真正难的又是什么？

## 软件生态

先摆几组数据。

| 软件 / 公司 | 近期公开数据 | 核心生态 |
|---|---|---|
| Adobe | 2025 财年收入 **237.69 亿美元**；2026 财年第三季度收入 67.6 亿美元，同比增长 13% | 创作工具、专业文件、插件、素材与团队工作流 |
| JetBrains | 2026 年度资料披露，公司收入同比增长 **25.69%**，经常性活跃用户超过 1250 万 | IntelliJ IDEA、代码分析、调试、重构与开发工具链 |
| Autodesk | 2026 财年收入 **72.06 亿美元**；AutoCAD 产品家族收入约 17.87 亿美元 | CAD、建筑工程、机械设计、制造与协作 |
| MathWorks | 官方资料披露年收入约 **15 亿美元**，MATLAB 用户超过 500 万 | 数值计算、Simulink、专业工具箱与工程验证 |
| 微信 / Weixin | 2026 年第二季度合并月活用户达到 **14.39 亿** | 社交关系、支付、内容、小程序与商家网络 |

这些数字的统计期间与业务口径不同，不适合直接比较公司实力，但足以帮助我们理解这些产品背后的商业规模。

这里有个有意思的问题：

**如果 AI 让开发软件越来越便宜，这些公司的收入会不会被一点点蚕食？**

## vscode vs IDEA

vscode（微软大战代码，人称宇宙第一编辑器） 很轻量，插件生态丰富，早就让很多开发者不再需要安装一个庞大的专业 IDE。

后来，GitHub Copilot、Cursor 等 AI 编程工具出现，VS Code 所代表的开发环境又多了一层优势：它不只是写代码的地方，还逐渐成为 AI 编程工作流的入口。

年初很多 ai 编辑器都是基于 vscode 改造的，现在也渐渐从 IDE->ADE 发展，乃至代码阅读开始都变得不重要。

看看开发者调查数据：在 2026 年 Stack Overflow 开发者调查中，70.9% 的受访者表示过去一年经常使用 VS Code，IntelliJ IDEA 为 24.3%，Cursor 为 14.9%。

**AI 不一定直接消灭老软件，但会改变用户为什么选择老软件。**

老马以前作为一个老 javaer，以前特别喜欢 IDEA。现在渐渐地，也变成 vscode 使用的更多了。

## 过去为什么难以替代？

以前知乎上有一个问题，说为什么我们国家没有一流的软件？

比如为什么实现不了 matlab、cad 等工业级软件。

如今看来，也许事情有了微妙的转机。

以前常说“没人能实现”，真正的问题往往不是实现不了，而是把全部专业能力、兼容性和生态一起做到可用，成本太高。

AI 正在改变这个成本结构。以前要花大钱才能启动的项目，现在可能值得重新算账。

但专业软件最难的部分，并不会因为代码生成更快，就自动消失。

## 微信的护城河

因为微信的价值，根本不只在软件里。

你可以让 AI 很快做出一个聊天应用，包含好友、群聊、消息和图片。

但你怎么把十几亿用户请过来？

怎么让商家入驻、开发者制作小程序、用户使用支付，再让日常交流和服务都围绕它运转？

怎么能让公众号、视频号的作者全部迁移过去？

今年上半年我也自己写了一个简易版本的微信，当然只是自娱自乐。没人用，商业价值很低。

## 版权呢？

技术上做得到，不代表法律上就可以随便做。

这里需要区分软件功能与受保护的程序表达。

版权法通常不保护思想、方法和系统本身；欧盟法院在 SAS Institute v World Programming 一案中，也区分了软件功能与受版权保护的表达。

但这绝不意味着可以直接复制源代码、搬运图标、复制文档，或者无视软件许可和其他知识产权。

即使 AI 帮你分析了一个程序，也不意味着分析结果就可以随意复制。

## 写在最后

AI 正在降低软件的实现成本，但没有让所有商业价值都变得廉价。

这对程序员是机会：过去做不起的产品，可以重新算账。

对创业者也是机会：不必一上来就做一个庞大的平台，可以先解决某个细分场景，把一个功能真正做到可靠。

以前，我们问一个软件能不能被做出来；

以后，更值得问的是：**即使别人也做得出来，用户为什么还要选择你？**

---

# 参考资料

以下统一列出文中财务数据、开发者调查和法律论述的原始来源，方便读者查证。

**一、公司财报与产品生态**

1. Adobe，FY2025 财报及 FY2026 第三季度业绩公告  
   - [Adobe FY2025 财报](https://www.sec.gov/Archives/edgar/data/796343/000079634326000003/adbe-20251128.htm)  
   - [Adobe FY2026 Q3 业绩公告，2026 年 9 月 10 日](https://news.adobe.com/news/2026/09/adobe-q3fy26-financial-results)

2. JetBrains，Annual Highlights 2026  
   - [公司收入增长、活跃用户、AI 产品与 IDE 统一发行版](https://www.jetbrains.com/lp/annualreport-2026/)

3. Autodesk，Fiscal 2026 Fourth Quarter Results  
   - [2026 财年收入与产品家族收入](https://investors.autodesk.com/news-releases/news-release-details/autodesk-inc-announces-fiscal-2026-fourth-quarter-results)

4. MathWorks，Company Fact Sheet 2025  
   - [官方公司资料 PDF](https://jp.mathworks.com/content/dam/mathworks/fact-sheet/2025-company-factsheet-8-5x11-8282v25.pdf)

5. 腾讯，2026 年第二季度财报  
   - [Tencent Announces 2026 Second Quarter Results](https://www.tencent.com/wp-content/uploads/2026/08/Tencent-Announces-2026-Second-Quarter-Results.pdf)  
   - 文中的微信及 Weixin 合并月活数据，见财报第 3 页的 Operating Metrics。

**二、开发者调查**

6. Stack Overflow，2026 Developer Survey  
   - [开发环境使用情况统计](https://survey.stackoverflow.co/2026/technology/data/dev-ide)

**三、版权与法律依据**

7. 美国版权局：Computer Programs  
   - [计算机程序版权保护说明](https://www.copyright.gov/register/tx-programs.html)

8. 欧盟法院：SAS Institute Inc. v World Programming Ltd.  
   - [案件判决全文](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A62010CJ0406)

**四、本文讨论的开源项目**

9. [REA：Reverse Engineer Anything](https://github.com/morluto/rea)

10. [ArtCraft：Crafting Apps](https://github.com/storytold)

