# 为 LinuxGSM 做贡献

👍🎉 感谢您抽出宝贵的时间来贡献自己的力量！ 🎉👍

以下是一组帮助 LinuxGSM 的指导原则，LinuxGSM 托管在 GitHub 上的[GameServerManagers Organization](https://github.com/gameservermanagers) 组织中。这些基本上是指导方针，而不是规则。使用您的最佳判断，并在请求中随时提出对此文档的更改。

## 行为守则

本项目和所有参与项目的人都受 [LinuxGSM 行为守则](https://github.com/GameServerManagers/linuxgsm/blob/master/CODE_OF_CONDUCT.md) 的约束。通过参与，您将维护本准则。请将不可接受的行为报告给 [daniel.gibbs@linuxgsm.com](mailto:daniel.gibbs@linuxgsm.com)。

## 目录

[为 LinuxGSM 做贡献](#为-LinuxGSM-做贡献)
* [目录](#目录)
* [行为守则](#行为守则)
* [🎉 Bug/增强功能 贡献 🐛](#Bug-增强功能-贡献)
	+ [🐛 Bugs 报告](#Bugs-报告)
		- [提交错误报告之前](#提交错误报告之前)
		- [我如何提交（良好）错误报告](#我如何提交（良好）错误报告)
	+ [🎉功能建议](#功能建议)
		- [提交功能建议之前](#提交功能建议之前)
		- [如何提交（良好）功能建议](#如何提交（良好）功能建议)
	+ [🎮 游戏服务器请求](#游戏服务器请求)
		- [提交游戏服务器请求之前](#提交游戏服务器请求之前)
		- [如何提交（良好）游戏服务器请求](#如何提交（良好）游戏服务器请求)
	+ [🎮 游戏服务器特定问题](#游戏服务器特定问题)
* [💻 代码贡献](#代码贡献)
	+ [拉取请求](#拉取请求)
		- [拉取请求命名约定](#拉取请求命名约定)
	+ [测试](#测试)
		- [拉取请求状态检查](#拉取请求状态检查)
		- [测试环境](#测试环境)
	+ [:wine_glass: 风格指南](#-wine-glass--风格指南)
		- [Git 提交消息](#Git-提交消息)
		- [BASH 样式指南](#BASH-样式指南)
* [:blue_book: 文档贡献](#-blue-book--文档贡献)
	+ [文档样式指南](#文档样式指南)
* [发出和拉取请求标签](#发出和拉取请求标签)


## 🎉 Bug/增强功能 贡献 🐛

### 🐛 Bugs 报告

本节指导您提交 LinuxGSM 的错误报告。遵循这些准则有助于维护人员和社区理解您的报告📝，重现行为💻，并找到相关报告🔎.

在创建错误报告之前，请检查 [此列表](https://github.com/GameServerManagers/linuxgsm/blob/master/CONTRIBUTING.md#before-submitting-a-bug-report) ，因为您可能会发现不需要创建错误报告。当你创建一个错误报告，请 [包括尽可能多的细节](https://github.com/GameServerManagers/linuxgsm/blob/master/CONTRIBUTING.md#how-do-i-submit-a-good-bug-report) 。填写 [所需的模板]([https://github.com/GameServerManagers/LinuxGSM/issues/new/choose](https://github.com/GameServerManagers/LinuxGSM/issues/new/choose)) ，它要求的信息可以帮助我们更快地解决问题。

#### 提交错误报告之前

* **检查 [文档](https://docs.linuxgsm.com)**。你也许能找到问题的原因，自己解决问题。
* **检查问题是否与指向其他支持选项的链接的支持页[**支持页**](https://linuxgsm/com/support) 无关**
* **查看**[**支持页**](https://linuxgsm/com/support) 以获取指向其他支持选项的链接。
* **执行** [**粗略搜索**](https://github.com/search?q=org:GameServerManagers%20type:issues&type=Issues) 以查看是否已报告问题。如果有，但问题仍然存在，请在现有问题上添加评论，并对其竖起大拇指，而不是打开新问题。

#### 我如何提交（良好）错误报告

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue and provide the following information by filling in [the issues form](https://github.com/GameServerManagers/LinuxGSM/issues/new/choose).

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Complete the user story** to give a summary of the issue.
* **Provide basic info** to help us understand the context of the issue.
* **Provide further info** to give specifics and more detail.
* **Give steps to reproduce** the issue, allowing developers to follow steps that lead to the issue.
* **Explain what you expect** to happen, so we know what you think should occur.

### 🎉 功能建议

本节指导您提交 LinuxGSM 的功能建议，包括全新的功能和对现有功能的细微改进。根据这些指引，有助维护者及社会人士了解您的建议📝，并🔎找到有关建议。

#### 提交功能建议之前

* **Check the** [**documentation**](https://docs.linuxgsm.com/%5D(https://docs.linuxgsm.com/)) to confirm that the enhancement doesn’t already exist.
* **Check your** [**LinuxGSM version**](https://docs.linuxgsm.com/commands/update-lgsm)**.** A newer version of LinuxGSM may already have your enhancement.
* **Perform a** [**cursory search**](https://github.com/search?q=org:GameServerManagers%20type:issues&type=Issues) to see if the enhancement has already been suggested. If it has **and the enhancement is still open**, add a comment to the existing issue and give it a thumbs up instead of opening a new one.

#### 如何提交（良好）功能建议

Features are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue and provide the following information by filling in [the issues form](https://github.com/GameServerManagers/LinuxGSM/issues/new/choose).

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Complete the user story** to give a summary of the issue.
* **Provide basic info** to help us understand the context of the enhancement.
* **Provide further info** to give specifics and more detail.
* **Provide any further reading** materials that might assist in developing the enhancement.

### 🎮 游戏服务器请求

This section guides you through submitting a game server request for LinuxGSM, Following these guidelines help maintainers and the community understand your game server request 📝.
#### 提交游戏服务器请求之前

* **Check for existing** [**game server requests**](https://github.com/GameServerManagers/LinuxGSM/labels/type%3A%20game%20server%20request) to see if the new game server has already been suggested. If it has **and if the new game server is still open**, give it a thumbs.
* **Check the game server is supported on Linux**, this does not include Wine servers which we do not support.
#### 如何提交（良好）游戏服务器请求
* The title should be as follows: **[Server Request] Game Name**
*  **Provide Steam App ID** if applicable
* **Supply any documentation/how-to guides** for the game server.

### 🎮 游戏服务器特定问题

LinuxGSM is a management script that acts as a wrapper around game servers. These game servers are developed by different game developers such as Valve, Epic and Facepunch to name a few.

LinuxGSM has no control over the development and limited knowledge of issues directly relating to the game servers themselves. The same also applies for any mods, add-ons, maps etc.

If there is an issue with a specific game server or mod the best action may be to contact the game/mod developers on there support forums. If it is unclear some community members should be able to help.

A [list](https://docs.linuxgsm.com/support/game-server) of known game developer forums is available on the [LinuxGSM docs](https://docs.linuxgsm.com/support/game-server).

## 💻 代码贡献

### 拉取请求

The process described here has several goals:

* Maintain LinuxGSM quality.
* Fix problems that are important to users.
* Engage the community in working toward the best possible LinuxGSM.
* Enable a sustainable system for LinuxGSM maintainers to review contributions.

Please follow these steps to have your contribution considered by the maintainers:

1.  Follow all check-list in [the template](https://github.com/GameServerManagers/LinuxGSM/blob/master/.github/pull_request_template.md)
2.  Follow the [style guides](#styleguides)
3.  After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing

What if the status checks are failing? If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.

While the prerequisites above must be satisfied before having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

#### 拉取请求命名约定

When naming a pull request to ensure that it is following [Conventional Commits](https://www.conventionalcommits.org/) standards; as your pull request commits will be squashed, with the PR subject becoming the commit that is used for generating the [changelog](https://github.com/GameServerManagers/LinuxGSM/releases) for the next release.

The pull request subject line should always be able to complete the following sentence:

If applied, this commit will _your subject line here_

For example:

* If applied, this commit will **refactor subsystem X for readability**
* If applied, this commit will **update getting started documentation**
* If applied, this commit will **remove deprecated methods**
* If applied, this commit will **release version 1.0.0**
* If applied, this commit will **merge pull request #123 from user/branch**

Notice how this doesn’t work for the other non-imperative forms:

* If applied, this commit will **fixed bug with Y**
* If applied, this commit will **change the behaviour of X**
* If applied, this commit will **more fixes for broken stuff**
* If applied, this commit will **sweet new API methods**

Below is an example of the subject line for a pull request:

**feat(alerts): add slack support to alerts**

**fix(csgoserver): remove SteamCMD auth requirement 32-bit workaround**

### 测试

#### 拉取请求状态检查

提交拉取请求后，将进行一系列状态检查测试。这些测试将评估代码质量，完成CI测试等。要使PR合并，必须通过这些状态检查。

#### 测试环境

建议您有一个测试环境可用于在开发过程中测试您的代码。要测试自己的代码，必须在 `linuxgsm.sh` 文件中更改一些变量。这将强制使用您自己的代码分支。

```bash
## GitHub Branch Select
# Allows for the use of different function files
# from a different repo and/or branch.
githubuser="GameServerManagers"
githubrepo="LinuxGSM"
githubbranch="master"
```

### :wine_glass: 风格指南

#### Git 提交消息

LinuxGSM使用传统的提交标准，允许其他开发人员在开发时获得易于理解的描述性提交消息。虽然建议您在提交时使用此标准，但由于在合并 PR 时，您的提交最终会被压扁，因此此标准对于提交并不严格执行，但是，建议对于更复杂的提交使用此标准。

#### BASH 样式指南

LinuxGSM 使用[ShellCheck](https://www.shellcheck.net/)来遵循 BASH 最佳实践。建议您使用绒毛工具为您的文本编辑器，如[linter-shellcheck](https://atom.io/packages/linter-shellcheck)。LinuxGSM 使用 [Codacy](https://app.codacy.com/manual/GameServerManagers/LinuxGSM/dashboard) 分析任何拉力请求，为您提供有关代码标准的反馈。

LinuxGSM 也有一些应遵循的风格标准。这些在[开发文档](https://dev-docs.linuxgsm.com/)中可用

## :blue_book: 文档贡献

除了代码贡献之外，还可以通过编写和改进文档来做出贡献。文档贡献也可以通过提交 Pull 请求来提交。

### 文档样式指南

LinuxGSM 拥有各种文档，可用于帮助[用户](https://docs.linuxgsm.com) 和[开发人员](dev-docs.linuxgsm.com)。LinuxGSM 主要使用使用[标记](https://www.markdownguide.org/) 文档标准的[GitBook](http://gitbook.com/) 。LinuxGSM 使用 [Codacy](https://app.codacy.com/manual/GameServerManagers/LinuxGSM/dashboard)  分析任何拉力请求，为您提供有关加价标准的反馈。

## 发出和拉取请求标签

本节列出了帮助我们跟踪和管理问题和请求的标签。

[GitHub search](https://help.github.com/articles/searching-issues/) 使您可以轻松地使用标签查找您感兴趣的问题组或请求。有几种类型的标签可用：

**命令** 标签
也突出显示了 Issue/PR 关联的 LinuxGSM 命令。

**信息** 标签
标签也可以帮助您查明问题或 PR 的相关内容。

变体：
* _distro_
* _engine_
* _game_
* _info_

**结果** 标签
标识为什么关闭问题的标签。

**状态** 标签
用于向人们更新问题状态的标签。

**类型** 标签
标识问题类型的标签，例如错误，功能，重构等。
