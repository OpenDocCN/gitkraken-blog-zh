# Git 的最佳工具

> 原文：<https://www.gitkraken.com/blog/best-tools-git>

在深入 Git 之前，从高层次理解版本控制的概念是很重要的。虽然不是所有的软件开发人员都使用版本控制，也不是只有软件开发行业使用版本控制，但它每年都变得越来越主流。你可以打赌，作为一名开发人员，如果你曾经在一个 workplace 团队或开源项目中与其他人合作，你将会面临版本控制。

版本控制是一种跟踪文件和文件集随时间变化的系统，目的是重新调用特定版本以供审查。需要时，您还可以恢复到文件的以前版本。感觉就像回到了过去。

此外，使用[版本控制系统](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) (VCS)可以让您看到谁在什么时间对哪个文件做了什么更改。这使得它在开发团队工作或与同学合作项目时非常有价值。它增加了宝贵的透明度，提供了问责制和更好的组织。

有多种 VCS——本地的、集中式的和分布式的——但是出于本文的目的，我们将关注 Git，一种分布式版本控制系统(DVCS)。

**Git 是什么？**

## 最初由 Linux 内核的创造者 Linus Torvalds 开发，并于 2005 年发布，Git 已经成为当今世界上使用最广泛的 VCS。

使用 Git，开发人员的工作代码是一个精确克隆的存储库，包含了所有的变更历史，而不是像 Subversion 这样的集中式系统那样，只有一个地方存放项目的版本历史。

自 2005 年问世以来，Git 一直致力于改善全球开发人员的工作流程，因此越来越受欢迎。值得庆幸的是，痴迷 Git 的开发人员，比如 GitKraken 的 truly，近年来一直在努力工作，为您带来增强 Git 体验的软件工具。

Since its arrival in 2005, Git has continued to improve developers’ workflows worldwide, hence its ever-increasing popularity. And thankfully, Git-obsessed developers, like yours truly at GitKraken, have been working hard in recent years to bring you software tools to enhance your Git experience. 

**Git 的最佳开发工具**

## **GitHub**

在开始使用 Git 之前，您需要决定在哪里托管您的存储库。流行的托管服务包括托管和自托管版本的 [GitHub](https://www.gitkraken.com/github) 、 [GitLab](https://www.gitkraken.com/gitlab) 、 [Azure DevOps](https://www.gitkraken.com/azure-devops) 和 [Bitbucket](https://www.gitkraken.com/bitbucket) ，所有这些都由 GitKraken Git GUI 支持。

### ***了解 Git 托管服务如何融入 DevOps 生命周期。***

[**2020 DevOps 工具报告**](https://www.gitkraken.com/resources/devops-report-2020#hosting-services)

你可能想知道为什么。正如行业专家 Jenny Bryan 在她的白皮书中解释的那样:

如果你不知道我在说什么，就把(你的托管服务)想象成 DropBox，但要好得多。

就像一个存放代码的安全地方。即使你一个人在做一个个人项目，通过将你的工作推到一个远程位置来备份你的代码仍然是一个好主意。

> 无论你或你的团队选择使用哪种托管服务进行日常工作，我们都鼓励任何使用 Git 的开发者拥有一个 [GitHub](https://github.com/) 账户并参与到平台中，因为有大量的开源代码可用。基本上，如果你正在使用 Git，你将在某个时候使用 GitHub。
> 
> – Jenny Bryan, [Happy Git and GitHub for the user](https://happygitwithr.com/big-picture.html)

并且考虑暴露于全球开发者社区。如果有人需要审查你的作品，他们可以通过 GitHub 直接轻松访问。同样，假设你想评估一个受尊敬的影响者如何通过他们的公共项目工作；任何用户都可以在他们的 GitHub 个人资料上看到这些信息。或者，假设你想为 GitHub 上的一个开源项目做贡献；下载一个工作副本，提交一个拉取请求，然后开始协作。这就像一个软件开发的社交媒体平台。

*需要注意的是，GitHub 也支持私有存储库，相关代码不公开。*

**去 GUI** 去

贵由可能会问什么是饭桶？这是一个图形用户界面，它使使用 Git 的体验比在命令行上执行操作更加流畅。

*看看 GitKraken 的 [Git GUI 与命令行](/blog/git-gui-vs-cli)相比如何。*

### 具体来说，使用 Git GUI 的视觉体验比 CLI 更吸引人、更直观。下面，你可以看到一个文件的工作项目历史的可视化比较，显示在命令行和 [GitKraken Git GUI](https://www.gitkraken.com/git-client) 中。

在 GitKraken 中，您可以清楚地看到哪些提交是由谁在哪个分支上进行的。您甚至可以清楚地看到每个提交的上下文，单个 gravatars 显示谁对什么更改负责；您可以在快速快照中获得所有信息，而无需剖析代码行。

Git GUIs 本质上是代表您执行 Git 操作，有些比其他的更健壮。GitKraken Git GUI 提供了拖放功能(对于不太喜欢使用鼠标的开发人员😉).您还可以在 UI 中获得重要的上下文，包括右边的 commit 面板和左边的面板，显示所有项目的远程、拉请求、子模块等等。

GitKraken Git GUI 受到全世界数百万开发人员的喜爱有很多原因，但 Git 爱好者尤其喜欢 GitKraken [Diff 工具](https://support.gitkraken.com/working-with-commits/diff/)，它可以向用户显示随着时间的推移对文件做了哪些修改。

另一个粉丝的最爱，GitKraken [合并工具](https://support.gitkraken.com/working-with-repositories/branching-and-merging/#merge-conflict-editor)允许用户提交两个不同的分支并将它们合并。但是，假设两次提交对同一个文件有冲突的更改。不要害怕饭桶学徒！GitKraken 会提醒你冲突，并指导你如何最好地解决它。

g itKraken 是跨平台的，这意味着它可以在 Windows、Mac 和 Linux 上与 Git 一起使用。它还内置了与 GitHub、GitLab、Azure DevOps 和 Bitbucket 的集成，以简化存储库管理和工作流程。

立即免费下载 GitKraken Git GUI！

Another fan favorite, the GitKraken [Merge Tool](https://support.gitkraken.com/working-with-repositories/branching-and-merging/#merge-conflict-editor) allows users to take commits on two difference branches and combine them. But, let’s say the two commits have conflicting changes to the same file. Fear not Git apprentice! GitKraken will alert you of the conflict and direct you on how best to resolve it.

**发行跟踪板**

与任何项目一样，使用 Git 时，组织和任务跟踪可以派上用场。虽然 Git 确实在帮助您组织您的文件历史和代码变更，但是您仍然需要一个工具来在高层次上跟踪特定的项目任务，以确保您在下一个发布截止日期前按时完成。

### GitKraken issue boards 是同类软件中唯一的看板软件，专为开发人员和开发团队打造。与 GitHub 动作、拉请求和里程碑的集成使它成为使用 Git 和 GitHub 的开发人员的完美工具。开始使用 [GitKraken 发布板](https://www.gitkraken.com/glo)来管理你的 Git 项目。

通过 [GitKraken 与 GitHub Actions](/blog/gitkraken-glo-boards-support-github-actions) 的集成，你可以自动操作你的板上的卡片。例如，在 GitHub 中合并了一个 pull 请求后，您可以触发一张卡移动到您的 Deployed 列中。很酷，对吧？

类似地，您可以设置一个集成来[将 GitKraken 板连接到 GitHub Pull 请求](/blog/github-pull-request-integration-glo)。您可以映射您的自动化流程，根据 GitHub 中的 PR 状态将卡片移动到特定的列，无论是打开、关闭&合并、关闭还是合并。

最后，将 GitHub 里程碑与 GitKraken 同步，以便根据项目里程碑的截止日期跟踪您的任务。当您在 GitKraken 或 GitHub 中关闭、编辑或删除您的里程碑时，您可以立即在两个系统中看到更新。

Through [GitKraken’s integration with GitHub Actions](/blog/gitkraken-glo-boards-support-github-actions), you can automate the manipulation of cards on your boards. For example, you can trigger a card to move into your Deployed column after a pull request is merged in GitHub. Pretty cool, right? 

**成为 Git Boss**

当您刚刚开始时，Git 可能会让人不知所措，这些工具将帮助您在作为开发人员的日常工作流程中变得更加自信。

成为真正的#GitBoss，用这些推荐的 Git 工具提升你的开发水平。

## **Become a Git Boss**

Git can be overwhelming when you’re just getting started, and these tools will help you become more confident in your daily workflow as a developer.

Become a true #GitBoss and level up your dev game with these recommended Git tools.