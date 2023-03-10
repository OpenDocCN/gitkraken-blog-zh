# GitKraken v1.5.4 -更快更完美| Axosoft

> 原文：<https://www.gitkraken.com/blog/gitkraken-v1-5-4>

我们每天都会收到大量来自 GitKraken 用户的推文和电子邮件。我们喜欢看到这样来自亚采克的作品:

> @GitKraken 让我开心了一天。使用起来很愉快。合并提交从来没有这么有趣过！有史以来最好的 [#git](https://twitter.com/hashtag/git?src=hash) GUI！https://t.co/HGYKyKarcE
> 
> —亚采克·沃兹尼亚克(@ spik3s)[2016 年 8 月 24 日](https://twitter.com/spik3s/status/768529020627582976)

 <picture decoding="async" class="wp-image-4532" title="<script>">![<script>](img/01109a0493da953d7706a7687e4725e4.png)</picture> window.addEventListener('DOMContentLoaded', function() {

另一方面，我们讨厌看到来自 *Bonzo Apps* 的令人心碎的推文:

> [@GitKraken](https://twitter.com/GitKraken) 当 GitKraken 从致命错误复位时失去远程 repos！如何重新连接到驱动器上的现有远程存储库？HALP！！！🙁
> 
> —Bonozo Apps(@ Bonozo Apps)[2016 年 5 月 2 日](https://twitter.com/BonozoApps/status/727274929935126528)

 <picture decoding="async" class="wp-image-4533" title="<script>">![<script>](img/95b6ad39d75b38944ea1d04ac345a11f.png)</picture> 

不管怎样，我们喜欢反馈，我们在倾听！在 [v1.5.4](https://www.gitkraken.com/release-notes#v1-5-4) 中，我们修复了您告诉我们的 5 个主要问题！因此，如果你最近在我们的 Git 客户端中遇到了一些讨厌的问题，并且不明白发生了什么，或者更重要的是，不知道如何修复它们，那么这个版本就是为你准备的。

## **5 大改进:**

### **1)错误处理**

我们承认——确实有一些恼人的、令人困惑的错误信息出现在一些 GitKraken 用户面前。我们没有很好地解释为什么有些事情会失败。现在，我们解释发生了什么，并给你一个有用的信息，告诉你该做什么和如何解决它。

这是为像 *Major_Cookie* 这样的人准备的！

> [@GitKraken](https://twitter.com/GitKraken) 你好。然后我试着结账时看到了这条信息。这个错误可能与什么有关？【pic.twitter.com/hl8RAwYQQp 号
> 
> —Major _ Cookie(@ Simple _ Mike _ C)[2016 年 7 月 9 日](https://twitter.com/Simple_Mike_C/status/751887778170929152)

### **2)组织访问**

许可:有时候，你不得不去要求。真麻烦！但是，这是必要的，尤其是对组织和公司而言。GitKraken 需要获得许可才能查看某些回购——尤其是当它们可能不完全公开时。

当用户试图连接到 GitHub 时，他们需要组织访问权限——这些存储库不属于用户，它们属于组织或公司。GitKraken 需要 GitHub 的许可。如果您出错，我们的 Git 客户端现在可以告诉您发生了什么。

是的，GitKraken 会提供步骤帮你解决。很抱歉那个*迷宫*！

> 我试着在工作中使用 GitKraken，但是当我尝试推送时，我得到一个错误“无法识别的允许类型:32”有什么想法吗？
> 
> —迷宫(@ Irazzer)[2016 年 4 月 28 日](https://twitter.com/Irazzer/status/725615126930403328)

### **3)存储库远程 URL**

当你的朋友用*权力的游戏*中的一个角色给他们的孩子取名时，该说什么:“你确定吗？名字很重要。当老师在点名时关切地喊出“丹妮莉丝·坦格利安，她名字的第一个，弥林女王，安达尔人和先民的女王，七国之主，王国的守护者，大草海的卡丽熙，龙之母”时，你认为你的孩子会怎么样”*尴尬…*

那么这和我们的 Git 客户端有什么关系呢？GitKraken 不能处理旧的 SSH 格式，因为它不能识别 URL 中的用户名。

> [@GitKraken](https://twitter.com/GitKraken) 有没有解释错误信息的文档？最新的 gitkraken 想和我们的 ssh 交流，但是不喜欢文件类型
> 
> —吉姆·麦克基本(@ Jonny 55555)[2016 年 6 月 6 日](https://twitter.com/jonny55555/status/739848895212093441)

 <picture decoding="async" class="wp-image-4535" title="<script>">![<script>](img/a9725eda09db30c7d94bcaa57ba698bd.png)</picture> 

所以现在，GitKraken 会提示你纠正这一点，再也不会打扰你了。我们通过解决用户可能不知道的问题来帮助他们。

我们也鼓励你在给你的孩子起名之前仔细思考。成交？

### **4)注意比特斗间隙**

> [@GitKraken](https://twitter.com/GitKraken) 无法使用 SSH key 访问 Bitbucket。总是收到错误消息:无效密钥。不是 base64 编码的。我该怎么办？
> 
> —威廉·诺托维达多(@ plus wn)[2016 年 5 月 31 日](https://twitter.com/pluswn/status/737683649705869313)

 <picture decoding="async" class="wp-image-4536" title="<script>">![<script>](img/993369d949961c9444144e337abde524.png)</picture> 

> [@GitKraken](https://twitter.com/GitKraken) 创建 BB 回购时，得到错误“服务集成需要请求更多权限。”想法？
> 
> -雷·哥苏多(@ ray gestudo)[2016 年 4 月 26 日](https://twitter.com/RayGesualdo/status/725041934683746309)

 <picture decoding="async" class="wp-image-4537" title="<script>">![<script>](img/0602438294c9e8ff50658bf267464f41.png)</picture> 

看起来我们在玩电话游戏，你在电话那头，却没有得到所有的信息。

GitKraken 给你看的和 Bitbucket 说你应该能看到的有差距。例如，Bitbucket 会向你显示一个允许你查看或编辑的回购大列表，而 GitKraken 不会显示所有的回购。

无需恐慌；我们已经解决了这个问题。GitKraken 已经成为一项更好的运动。所以，你在 Bitbucket 里看到的，应该在 GitKraken 里有所体现。只要确保您已经设置了与 Bitbucket 的集成，这样沟通的渠道就清晰了！

### 让标签指引你

这大概是该版本的最大特点。我们一直在努力让用户更容易理解我们的 Git 客户端是如何工作的，这应该会有所帮助。因为用户界面非常简洁，所以按钮上没有标签。我们意识到新用户可能想知道这些按钮的名称，因为他们不知道图标的含义。哦，王南钧告诉我们的…

> 测试 [@GitKraken](https://twitter.com/GitKraken) 。到目前为止玩得很开心！按钮可以使用一些工具提示，【https://t.co/PiAFvhUcrz】T2
> 
> -@克瑞斯塔纳斯基【】[2016 年 8 月 24 日】](https://twitter.com/krystman/status/768236825861300224)

 <picture decoding="async" class="wp-image-4538" title="<script>">![<script>](img/dfec0a056597f0cab495809e207d6edb.png)</picture> 

所以我们为工具栏中的按钮添加了标签！

提醒一下，这是没有标签的顶栏。

就像任何事情一样，这是可选的。所以，如果你是一个极简主义者，就去`Preferences`取消标签，继续推和藏。或者让它们开着。不管怎样，我们都会支持你的决定。