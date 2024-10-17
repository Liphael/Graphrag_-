# 参与GraphRAG开发

首先由衷感谢你对**GraphRAG**作出的贡献！我们对帮助改进项目的社区贡献表示欢迎。

## 开发行为准则

本项目欢迎贡献和建议。绝大多数贡献都要求您签署同意**贡献者许可协议**（以下简称CLA），以声明您有权利并实际授予我们使用您的贡献的权利。有关详细信息，请访问：https://cla.microsoft.com.

当您提交拉取请求时，CLA机器人将自动确定您是否需要提供CLA并适当地修改**PR**（例如：标签、评论）。您只需按照机器人提供的说明进行操作即可，在所有存储库中，只需使用CLA执行此操作一次。

本项目基于[Microsoft开源项目开发行为准则](https://opensource.microsoft.com/codeofconduct/)。<br>
更多详细信息，请参阅：[Microsoft开源项目开发行为准则 FAQ](https://opensource.microsoft.com/codeofconduct/faq/)，或者联系[opencode@microsoft.com](mailto:opencode@microsoft.com)以提出其他问题、意见等。

## 开发参与指南

1. 创建库分支，并将其复制到本地主机。
2. 为您的贡献内容创建一个新分支： `git checkout -b my-contribution`.
3. 尝试您的修改，并**确保代码全部过测**。
4. 提交更改：`git commit -m "Add my contribution"`.
5. 通过运行： `poetry run semversioner add-change -t <major|minor|patch> -d <description>`创建并提交 semver 影响文档。
6. 将更改推送到 fork 存储库： `git push origin my-contribution`.
7. 新建对源库的拉取申请。

## 有关安全性问题的反馈
**请不要通过 GitHub Issues 公共板块报告安全漏洞！** 如有安全性漏洞，请向微软安全响应中心（MSRC）报告它们。有关更多信息请参照 [SECURITY.md](./SECURITY.md)。

## 协作开发：公共基本规则

在您开始参与开发协作之前，请先建立Issues档案。<br>
请遵循这个简单的规则，以便帮助我们避免产生一切不必要挫败感，以及精力浪费；确保能高效地利用每个人的时间————你的，我们的，以及其他一切社区成员的时间：

> 👉 如果你有疑问、且认为你发现了一个问题，或者想提出一个新功能等等；在你开始工作之前，希望您先在Issue板块检索、或提交一个Issue，来尝试修复/实施它（而不是自己一个人直接开干）。

### （提交新Issue之前）先搜索现有的Issues

在提交新 Issue 之前，请先搜索现有的未解决和已关闭的 Issue：这个项目进展很快！其他人可能已经发现了您看到的问题，并且有人可能正在处理或已经提供了修复程序！

如果没有现有项目描述您的问题/功能，那恭喜您发现了华点 - 请新建一个新Issue档案：

### 新建Issue档案

- 不知道您需要报告问题还是请求功能？新建Issue档案；
- Have a question that you don't see answered in docs, videos, etc.? File an issue
- Want to know if we're planning on building a particular feature? File an issue
- Got a great idea for a new feature? File an issue/request/idea
- Don't understand how to do something? File an issue
- Found an existing issue that describes yours? Great - upvote and add additional commentary / info / repro-steps / etc.

If from the previous guide you find yourself in the need of file an Issue please use the [issue tracker](https://github.com/microsoft/graphrag/issues).
Provide as much detail as possible to help us understand and address the problem.

### Add information

**Complete the new Issue form, providing as much information as possible**. The more information you provide, the more likely your issue/ask will be understood and implemented. Helpful information includes:

- What device you're running (inc. CPU type, memory, disk, etc.)
- What OS your device is running
- What tools and apps you're using (e.g. VS 2022, VSCode, etc.)
- **We LOVE detailed repro steps!** What steps do we need to take to reproduce the issue? Assume we love to read repro steps. As much detail as you can stand is probably _barely_ enough detail for us!
- Prefer error message text where possible or screenshots of errors if text cannot be captured
- **If you intend to implement the fix/feature yourself then say so!** If you do not indicate otherwise we will assume that the issue is our to solve, or may label the issue as `Help-Wanted`.

### DO NOT post "+1" comments

> ⚠ DO NOT post "+1", "me too", or similar comments - they just add noise to an issue.

If you don't have any additional info/context to add but would like to indicate that you're affected by the issue, upvote the original issue by clicking its [+😊] button and hitting 👍 (+1) icon. This way we can actually measure how impactful an issue is.

---

## Thank you

We appreciate your contributions to GraphRAG!
