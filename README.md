# 知识图谱-检索增强生成 GraphRAG

👉 [使用GraphRAG加速策划解决方案](https://github.com/Azure-Samples/graphrag-accelerator) <br/>
👉 [Microsoft Research Blog Post](https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/)<br/>
👉 [Read the docs](https://microsoft.github.io/graphrag)<br/>
👉 [GraphRAG Arxiv](https://arxiv.org/pdf/2404.16130)

<div align="left">
  <a href="https://pypi.org/project/graphrag/">
    <img alt="PyPI - Version" src="https://img.shields.io/pypi/v/graphrag">
  </a>
  <a href="https://pypi.org/project/graphrag/">
    <img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/graphrag">
  </a>
  <a href="https://github.com/microsoft/graphrag/issues">
    <img alt="GitHub Issues" src="https://img.shields.io/github/issues/microsoft/graphrag">
  </a>
  <a href="https://github.com/microsoft/graphrag/discussions">
    <img alt="GitHub Discussions" src="https://img.shields.io/github/discussions/microsoft/graphrag">
  </a>
</div>

## [分支新增]本页文件列表（2024.10.16ver）：

本节为像学习中的作者一样的初学者，作一些源文件中内容用途的注解：

[.github](https://github.com/Liphael/Graphrag_-/tree/main/.github)<br>
- **.github**文件夹包含Issues分区，拉取申请（pull request）分区和工作流分区；

[.semversioner](https://github.com/Liphael/Graphrag_-/tree/main/.semversioner)<br>
- **.semversioner**文件夹主要包含先前的发行版本文件，以及一个即将发布的包分区；

[.vscode](https://github.com/Liphael/Graphrag_-/tree/main/.vscode)<br>
- **.vscode**文件夹内含三个使用vscode时的配置文件，extension是推荐的vscode拓展插件清单，launch文件时GraphRAG的调试配置文件，settings包含所需的配置参数；

[docs](https://github.com/Liphael/Graphrag_-/tree/main/docs)<br>
- **docs**文件夹内含一系列官方的指导文档；详细的注解列表，将会在该文件夹README中给出；

[examples](https://github.com/Liphael/Graphrag_-/tree/main/examples)<br>
- **examples**正如其名，为一个示例资源；

[example_notebooks](https://github.com/Liphael/Graphrag_-/tree/main/examples_notebooks/community_contrib)<br>
- **example_notebooks**为社区贡献的开发笔记归档。注意：所有的笔记本将按原样提供，且不保证与最新版本的GraphRAG兼容！

[graphrag](https://github.com/Liphael/Graphrag_-/tree/main/graphrag)<br>
- **graphrag**为GraphRAG项目的主要源码，如无须作必要开发，不推荐**在没有基础的前提下**对此处代码作修改；

[scripts](https://github.com/Liphael/Graphrag_-/tree/main/scripts)<br>
- **scripts**包含三个基本运行脚本；包括版本检查（semvercheck），拼写检查（spellcheck）以及一个azurite模拟器启动脚本；

[tests](https://github.com/Liphael/Graphrag_-/tree/main/tests)<br>
- **tests**为运行测试文件；

## Overview

GraphRAG 项目是一个数据流转换工具，旨在利用大预言模型(LLMs)从**非结构化文本**中提取有意义的**结构化数据**。

要了解更多关于 GraphRAG 的信息，以及如何使用它来增强LLM对您的私人数据进行推理的能力，请访问 <a href="https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/" target="_blank">Microsoft Research Blog Post.</a>

## Quickstart

要开始使用 GraphRAG 系统，我们建议您尝试[Solution Accelerator](https://github.com/Azure-Samples/graphrag-accelerator)包，它提供了用户友好型 Azure 资源的端到端体验。

## Repository Guidance

此源库提供了一种使用知识图谱记忆结构来优化LLM输出的方法。注意，提供的源码仅用于展示，并非官方支持的 Microsoft 产品/服务。

⚠️ *Warning: GraphRAG indexing can be an expensive operation, please read all of the documentation to understand the process and costs involved, and start small.*

## Diving Deeper

- To learn about our contribution guidelines, see [CONTRIBUTING.md](./CONTRIBUTING.md)
- To start developing _GraphRAG_, see [DEVELOPING.md](./DEVELOPING.md)
- Join the conversation and provide feedback in the [GitHub Discussions tab!](https://github.com/microsoft/graphrag/discussions)

## Prompt Tuning

Using _GraphRAG_ with your data out of the box may not yield the best possible results.
We strongly recommend to fine-tune your prompts following the [Prompt Tuning Guide](https://microsoft.github.io/graphrag/posts/prompt_tuning/overview/) in our documentation.

## Responsible AI FAQ

See [RAI_TRANSPARENCY.md](./RAI_TRANSPARENCY.md)

- [What is GraphRAG?](./RAI_TRANSPARENCY.md#what-is-graphrag)
- [What can GraphRAG do?](./RAI_TRANSPARENCY.md#what-can-graphrag-do)
- [What are GraphRAG’s intended use(s)?](./RAI_TRANSPARENCY.md#what-are-graphrags-intended-uses)
- [How was GraphRAG evaluated? What metrics are used to measure performance?](./RAI_TRANSPARENCY.md#how-was-graphrag-evaluated-what-metrics-are-used-to-measure-performance)
- [What are the limitations of GraphRAG? How can users minimize the impact of GraphRAG’s limitations when using the system?](./RAI_TRANSPARENCY.md#what-are-the-limitations-of-graphrag-how-can-users-minimize-the-impact-of-graphrags-limitations-when-using-the-system)
- [What operational factors and settings allow for effective and responsible use of GraphRAG?](./RAI_TRANSPARENCY.md#what-operational-factors-and-settings-allow-for-effective-and-responsible-use-of-graphrag)

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Privacy

[Microsoft Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement)
