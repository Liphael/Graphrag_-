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

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.** Instead, please report them to the Microsoft Security Response Center (MSRC).
See [SECURITY.md](./SECURITY.md) for more information.

## Before you start, file an issue

Please follow this simple rule to help us eliminate any unnecessary wasted effort & frustration, and ensure an efficient and effective use of everyone's time - yours, ours, and other community members':

> 👉 If you have a question, think you've discovered an issue, would like to propose a new feature, etc., then find/file an issue **BEFORE** starting work to fix/implement it.

### Search existing issues first

Before filing a new issue, search existing open and closed issues first: This project is moving fast! It is likely someone else has found the problem you're seeing, and someone may be working on or have already contributed a fix!

If no existing item describes your issue/feature, great - please file a new issue:

### File a new Issue

- Don't know whether you're reporting an issue or requesting a feature? File an issue
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
