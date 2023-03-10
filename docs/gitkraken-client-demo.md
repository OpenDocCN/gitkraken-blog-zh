# GitKraken | GitKraken 客户端演示

> 原文：<https://www.gitkraken.com/gitkon/gitkraken-client-demo>

[https://www.youtube.com/embed/SebnwzgARaw?feature=oembed](https://www.youtube.com/embed/SebnwzgARaw?feature=oembed)

视频

欢迎来到 GitKraken 客户端！在这个来自 2021 [GitKon Git conference](https://gitkon.com/) 的 GitKraken 客户端演示中，Jonathan Silva 展示了世界上最流行的 Git 工具之一的令人难以置信的功能。

GitKraken 客户端是一个 Git 生产力和团队协作工具，可以节省团队时间。无论你是一个经验丰富的用户还是一个新的面孔，GitKraken 客户端都有适合每个人的东西。

想要一个不断发展的 Git 工具，以高级特性应对用户挑战？免费下载 GitKraken 客户端，跟随乔纳森。

## **用户界面概述**

当你用应用程序打开你的 [Git 存储库](https://www.gitkraken.com/learn/git/tutorials/what-is-a-git-repository)时，GitKraken Client 会构建中心图，这是你的回购提交历史的可视化表示。

图表的每一行代表一个 [Git 提交](https://www.gitkraken.com/learn/git/commit)，图表的顶部将总是显示最新的更改。交互式//WIP(工作进行中)节点将显示自上次提交以来工作目录是否已更改。

左侧面板显示了您的本地 [Git 分支](https://www.gitkraken.com/learn/git/branch)、远程、拉请求、问题跟踪集成、团队等等。

通过在左侧面板顶部的筛选器/搜索栏中键入内容，可以快速筛选所有这些部分。从每个部分中，您可以访问其他操作。例如，您可以从“分支操作”菜单中隐藏或单独显示分支。

要查看提交后的更改，您将使用图表右侧的提交面板。

提交面板显示了所选提交更改了哪些文件，以及其他详细信息。例如，如果您设置了 GPG 签名，右侧的提交面板将显示哪些提交已经签名并通过绿色注释验证📝提交名称旁边的图标。

在提交图中，单击选定提交中的任何文件名，以快速查看文件差异。从这里，您可以轻松地在大块视图、嵌入式视图或拆分视图之间切换。GitKraken 客户端还提供了单词区分、文件小地图和跳转到下一个修改的箭头。

在中间的图中，您可以使用`shift`或`cmd/ctrl`键选择多个提交来获得一个组合的差异，这对于比较提交或分支之间的差异非常有用。

默认情况下，文件以路径名显示，但如果您愿意，可以切换到树视图，或单击“查看所有文件”快速访问存储库中的所有文件。

选择图中的 WIP 节点将在提交面板中显示工作目录文件的更改。在这里，您可以在提交之前暂存、取消暂存或放弃更改。为了获得更高的粒度，在 diff 视图中，还可以通过块或行来暂存、取消暂存或丢弃更改。

您也可以直接在 GitKraken 客户端的编辑器中点击编辑文件，对您的文件进行其他更改。

## 【GitKraken 客户端分支

在 GitKraken 客户端中，本地和远程分支易于创建、管理和交互。

如果你在中间的图中右击一个提交，你会得到选项[创建一个 Git 分支](https://www.gitkraken.com/learn/git/problems/create-git-branch)，[选择一个提交](https://www.gitkraken.com/learn/git/cherry-pick)，重置一个分支到一个特定的提交，或者[恢复一个 Git 提交](https://www.gitkraken.com/learn/git/problems/revert-git-commit)。

如果右键单击作为分支头部的提交，您将有更多的选项，包括推和拉当前未签出的分支，以及合并、重置和启动一个 [Git pull 请求](https://www.gitkraken.com/learn/git/tutorials/what-is-a-pull-request-in-git)。

如果其中任何一项出错，如果您没有将回购推送到 [Git remote](https://www.gitkraken.com/learn/git/git-remote) ，那么`Undo`按钮会将您带回到回购的先前状态。如果您不正确地提交或执行了一个合并，并且想要返回，这真的很方便。

在 GitKraken 客户端的工具栏内，可以看到`Push`和`Pull`按钮。`Push`按钮会将当前分支推到其指定的远程，而`Pull`按钮可以获取或拉出远程分支。您可以通过点击`Pull`按钮旁边的下拉菜单，然后选择每个选项旁边的一个图标，来设置 GitKraken 客户端对每次 Git pull 将采取的默认操作，如下所示。

在 GitKraken 客户端点击 UI 右上角的魔棒图标将会弹出命令面板，在这里您可以快速访问诸如 [Git checkout](https://www.gitkraken.com/learn/git/git-checkout) 、push、pull、open a repo、 [clone a repo](https://www.gitkraken.com/learn/git/git-clone) 等操作。您也可以使用键盘快捷键`Cmd/Ctrl + P`来调出命令面板，而无需离开键盘。

## **拖放和交互式重设基础**

拖放使得 Git 操作更容易理解和执行。

在 GitKraken Client 中，您可以将一个分支拖放到另一个分支上，以生成一系列可能的操作，例如: [Git merge](https://www.gitkraken.com/learn/git/git-merge) ，rebase， [interactive rebase](https://www.gitkraken.com/learn/git/problems/git-interactive-rebase) ，如果您的存储库托管在一个受支持的集成上，甚至可以启动一个 pull 请求。

您还可以通过检出一个分支，然后右键单击图形或左侧面板中的目标分支，来获得类似的操作列表。

如果您选择交互式 rebase 选项，GitKraken 客户端将打开交互式 Rebase 视图，您可以在其中为每个提交选择一个操作。

*   在左侧–在“挑选”、“重绕”、“挤压”等选项之间进行选择。
*   使用向上或向下键导航提交
*   使用键盘快捷键执行以下任一操作
*   您也可以双击提交来改写
*   和拖放来向上或向下移动提交

如果您希望重启，只需点击`Reset`即可恢复您的更改。

一旦您做出选择，您就可以开始交互式重置基础，当它完成时，图形将会更新以反映您的更改。很不错，对吧？

GitKraken 是解决新问题的 Git 工具的完美范例，具有交互式拉请求管理、合并冲突检测和解决、深度链接等高级功能。

**合并工具**

## 当您拖放执行合并时，GitKraken 客户端将检测到[合并冲突](https://www.gitkraken.com/learn/git/tutorials/how-to-resolve-merge-conflict-in-git)并指导您解决问题。

如果发生合并冲突，右侧提交面板顶部会出现“检测到合并冲突”消息，以及冲突文件列表。单击提交面板中列出的任何文件都会打开合并工具。

If a merge conflict occurs, a “Merge conflict detected” message will appear on top of the commit panel on the right, along with a list of the conflicted files. Clicking on any of the listed files in the commit panel will open the merge tool.

GitKraken 客户端中的合并工具将向您显示两个分支之间的冲突变更，并在底部显示一个`Output`。选中您希望保留的每段代码的复选框，或者一次选择一行。

The merge tool in GitKraken Client will show you the conflicting changes between two branches along with an `Output` at the bottom. Check the box for each hunk of code you wish to keep, or select one line at a time.

您甚至可以在`Output`框中键入内容来进一步微调代码。一旦你对修改满意了，点击`Save`，或者输入`Ctrl/Cmd + S`，退出合并工具，继续下一个冲突的文件。解决所有冲突后，您可以继续进行合并。

有了 GitKraken Client，合并冲突就不那么可怕，也更容易解决，现在有了 GitKraken Client 的团队功能，您可以完全避免合并冲突——敬请关注更多相关内容。

With GitKraken Client, merge conflicts are less scary and easier to untangle, and now with GitKraken Client’s team features you can avoid merge conflicts all together – stay tuned for more on that.

**Git 回购拉取请求整合**

## GitKraken 客户端与 [GitHub](https://www.gitkraken.com/integrations/github) 、GitHub Enterprise、 [GitLab](https://www.gitkraken.com/integrations/gitlab) 、GitLab Self-Managed、 [Bitbucket](https://www.gitkraken.com/integrations/bitbucket) 、Bitbucket Server 和 [Azure DevOps](https://www.gitkraken.com/integrations/azure-devops) 的集成，使得在不离开 Git 客户端的情况下轻松创建和管理拉请求。

GitKraken Client’s integrations with [GitHub](https://www.gitkraken.com/integrations/github), GitHub Enterprise, [GitLab](https://www.gitkraken.com/integrations/gitlab), GitLab Self-Managed, [Bitbucket](https://www.gitkraken.com/integrations/bitbucket), Bitbucket Server, and [Azure DevOps](https://www.gitkraken.com/integrations/azure-devops) make it easy to create and manage pull requests without leaving the Git client.

从图中，将一个分支拖放到另一个分支上，以访问“创建拉取请求”选项。

这将触发一个模式，您可以在其中设置拉请求标题、描述和一些更多的细节。一旦您对细节满意，点击`Create Pull Request`，PR 将在主界面的左侧面板中可用。

如果您正在使用 GitHub.com 集成，您可以利用 pull request 视图查看 [GitHub pull requests](https://www.gitkraken.com/learn/git/problems/github-pull-requests) ，通过消除在 PR 过程中切换到 GitHub 的需要，进一步提高您的生产力。

在左侧面板中选择一个 GitHub pull 请求，打开 pull request 视图，GitHub 用户可以:

编辑提取请求标题、描述、审核者、受托人、里程碑和标签

*   对拉请求的注释:提交[代码评审](https://www.gitkraken.com/blog/code-review)，批准拉请求，或者请求变更
*   合并拉取请求
*   ProTip:如果双击 PR 视图右下方的分支名称，GitKraken 客户端会自动检出该分支，并在图形中打开它。这使得在本地测试 PR 的所有更改变得容易，而不必在应用程序之间来回切换。

**问题跟踪集成** s

GitKraken 客户端集成了流行的问题跟踪器，如[吉拉](https://www.gitkraken.com/integrations/jira)、GitHub 问题、GitLab 问题和 Trello。

## 导航至`Preferences` → `Issue Tracker`，然后选择您希望与当前打开的回购整合的问题跟踪器。您也可以将此设置为其他回购的默认值。

将问题跟踪器与 GitKraken 客户端连接后，您可以在左侧面板中选择项目来查看和过滤问题。

将鼠标悬停在某个问题上以预览详细信息，或者选择一个问题以:

查看问题详细信息

编辑状态/列

*   添加受让人
*   添加评论
*   创建与问题相关的分支(问题 ID 和标题将成为分支名称)
*   Add comments
*   GitKraken 客户端还允许用户创建新问题，设置问题类型、名称、描述、标签和代理人，而无需离开 Git 客户端。此外，在左侧面板中，您可以单击出现在问题面板中问题名称末尾的`⋮`菜单，直接在问题跟踪器或复制问题链接中查看问题。

**团队 Git**

当你和团队一起工作时，GitKraken 客户端会更强大。

GitKraken Client Pro 和企业云帐户的用户可以在其组织内创建和管理团队。导航至`Preferences` → `Your organization name`查看您的组织成员列表。这也是帐户管理员可以:

## 邀请用户加入组织

向组织成员分配角色

Users on GitKraken Client Pro and Enterprise Cloud accounts can create and manage teams within their organization. Navigate to `Preferences` → `Your organization name` to view the list of your organization members. This is also where account admins can:

*   如果您是 GitKraken 客户端团队的一员，左侧面板中的“团队”窗格将显示您所属的所有团队的下拉列表。
*   选择一个团队将显示该团队中所有成员的列表，您将能够看到每个成员正在处理的分支和文件。

If you are part of a team in GitKraken Client, the Teams pane in the left panel will populate with a dropdown list of all the teams you belong to. 

GitKraken 客户端还会警告你与队友之间潜在的合并冲突，通过用警告图标⚠️指示你和另一个团队成员当前正在处理的任何文件，为你的团队节省解决冲突的头痛。

如果您为图表启用了`Author`列，您可以按团队或个人贡献者过滤图表。按团队或作者过滤图表将突出显示任何符合您的过滤器的贡献者所做的提交，这将使图表更容易扫描您的团队的工作。

GitKraken 客户端提供的团队特性使得与 Git 的协作更加安全、简单和强大，并且使得新团队成员的加入速度更快。

If you have the `Author` column enabled for the graph, you may filter the graph by team or by individual contributors.  Filtering the graph by team or author will highlight the commits made by any contributors matching your filter, which should make the graph easier to scan for work by your team.

**将所有这些放在一起**

[观看视频](https://youtu.be/SebnwzgARaw?t=570)中的片段，了解 GitKraken 客户端中常见的工作流程场景。

现在你还在等什么？

## 您现在已经准备好为 Windows、Mac 和 Linux 使用传说中的 [GitKraken 客户端](https://www.gitkraken.com/git-client)![立即免费下载](https://www.gitkraken.com/git-client/try-free)释放您回购的全部潜力。

[Watch this clip from the video](https://youtu.be/SebnwzgARaw?t=570) to see a common workflow scenario in GitKraken Client.

Now what are you waiting for?

You’re now ready to use the legendary [GitKraken Client](https://www.gitkraken.com/git-client) for Windows, Mac, and Linux! [Download it free today](https://www.gitkraken.com/git-client/try-free) to unleash the full potential of your repo.