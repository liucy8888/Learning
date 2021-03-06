构建软件：

(1)过早优化是万恶之源。不要低估这个说法。
(2) 您很少需要从头开始构建某些东西。几乎每个用例都有库和依赖项。所以握住你的键盘，不要重新发明轮子。
(3) 了解问题的范围是您在找到解决方案之前需要做的第一步。我们错过了第一步而直接跳入解决方案是很常见的。
(4) 不要太完美主义者。首先，让它工作，然后让它干净。软件交付始终具有最高优先级。
(5) 糟糕的程序员担心代码。优秀的程序员担心数据结构及其关系。- 莱纳斯·托瓦兹
(6) 使用代码注释来解释你为什么要做某事，而不是你在做什么。不要过度描述并在代码注释中开始写小说。
(7) 拥有有意义的错误日志可以节省大量调试问题的时间。在错误消息中提供所有相关信息，而不是仅仅说“函数 X 中发生错误！”。并且永远不要记录任何敏感或个人信息。
(8) 100% 行/分支覆盖率并不意味着您的代码没有错误。编写测试以涵盖所有功能需求，而不是涵盖行/分支。
(9) 如果你正在修复一个bug，写一个相应的测试用例，这样以后就不会发生了。错误的发生通常是由于错误假设，为所有这些错误假设编写测试用例将使应用程序更加健壮。
(10) 当有人阅读你的代码时，他们不应该需要记住超过 7 件事来理解它。嗯，因为在我们的短期记忆中，我们的大脑一次不能保存超过 7 件东西。这也是许多代码 linter 在函数中警告超过 7 个参数的原因之一。
(11) 不要仅仅因为有人要求你做某事就以特定的方式做某事，明白为什么，如果你不相信，那就挑战现状。
(12) 解决问题是每个工程师应该真正擅长的最重要的技能。您的组织存在很多问题。开始解决它们，不是所有的都能解决，甚至20%都解决不了。但是在尝试解决的过程中，您会学到很多东西。
 

设计系统：

(13) 最好的系统设计通常是最简单的。保持简单愚蠢！(KISS)
(14) 设计模式和最佳实践并不是适用于任何地方的魔法药水。优秀的工程师知道最佳实践，但高级工程师知道何时打破最佳实践。
(15) 理解抽象。代码中不必要的复杂性通常是由于抽象不佳而引入的。
(16) 一个系统的强弱取决于它的最弱点。聚焦瓶颈。
(17) 离主要源头的步骤越多，一切都变得越腐败。尽量减少中间步骤，这适用于技术和非技术环境。
(18) 没有完美的解决方案，只有权衡。列出优点和缺点，以及做出正确权衡的要求。
(19) 您在项目中引入的每项技术都伴随着风险。衡量风险并制定减轻风险的计划。不要在没有救生衣的情况下跳入大海。
(20) 避免过早的抽象。解决您现在遇到的问题，仅此而已。当您看到类似的问题出现并且您看到一种模式出现时，那么您应该考虑围绕它构建抽象。
(21) “构建软件设计有两种方法：一种方法是简单到没有明显缺陷，另一种方法是复杂到没有明显缺陷。第一种方法是困难得多。简单很难。” - 托尼·霍尔。
(22) 不要太偏向于语言或框架，如果你喜欢某种语言，就不要一直崇拜它，不要开始到处使用它。如果你讨厌它，也不要一直抱怨它。每种语言或框架都是为特定用例设计的。作为工程师，您的工作是为用例选择正确的工具。
(23) 如果当你弄清楚某些东西是如何工作的时候，你已经忘记了为什么部分，那么代码中有很多不必要的抽象和复杂性需要清理。
(24) 复杂性一旦累积，就很难消除。不要认为您当前的更改引入的一点点复杂性没什么大不了的。如果每个开发人员都遵循相同的方法，那么复杂性会呈指数级累积。
(25) 如果您决定重写组件/服务，请务必重新考虑您的决定。阅读代码比编写代码更难，这就是为什么“我应该重写它！” 在软件开发中很常见。
(26) 不要犹豫挑战你的高级工程师或架构师提出的设计，有时你的设计会更好。提出有效的令人信服的观点并客观地进行比较。只是不要因为过于自信的混蛋而把这带到极端。
(27) 大多数情况下，静态类型语言比动态类型语言要好，尽管静态类型系统会带来开销。这就解释了为什么 TypeScript 是最受欢迎的语言之一。
 

其他提示：

(28) 优化您的代码以提高可理解性。无聊冗长的 20 行代码总是比巧妙编写的单行代码要好。
(29) 新手与他们编写的代码建立情感联系是很常见的。但在敏捷环境中，需求和代码不断变化。习惯于修改和删除旧代码。
(30) 为任何问题想出不止一种解决方案。试图找到多种解决方案会迫使您以不同的方式思考，一旦您有了不同的解决方案，您就可以通过选择正确的权衡来做出决定。
(31) 你处理的模块越多，你获得的领域知识就越多。您拥有的领域知识越多，您需要加入的会议就越多。您加入的会议越多，您编写的代码就越少。通过记录和共享领域知识来打破链条，这样您就不是唯一的联系点。我知道说比实施它容易。
(32) 当你被某个问题困在某个问题上很长时间没有任何进展时，重新表述这个问题或向某人解释这个问题，这在大多数情况下都很有效。为什么你认为rubber duck调试如此受欢迎。
(33) 您不需要了解整个代码库才可以开始处理它。了解架构和生命周期，并开始使用您的模块。不要浪费你的时间去试图理解每个类。
(34) 代码是负债而不是资产。您拥有的代码越多，就越需要阅读、理解、测试和维护。最好的代码是没有代码。
(35) 了解如何在 StackOverflow 上发布问题。您很少需要发布问题，但这是一项有用的技能，当您在文档和用户有限的库/框架上工作时，它会派上用场。
(36) 如果您在其他模块中偶然发现您没有处理的问题或错误，请通知相应的开发人员，或在 scrum 中提及。请不要说：我不对其他模块负责。
(37) 您编写的函数应该具有零/最小的副作用。这使得该功能可以轻松且独立地进行测试。
(38) 看在上帝的份上，请不要编写自己的日期格式/解析函数。每种编程语言都有许多流行的日期库，只需使用它们即可。日期和时区比您想象的要复杂得多。
 

安全：

(39) 每个开发人员都应该知道如何编写安全代码。编写具有糟糕设计/抽象的代码是可以的，但编写具有安全漏洞的代码绝对不行。阅读OWASP Top 10文档以开始使用。
(40) 当您想快速格式化或验证某些 JSON/XML/YAML 数据时，不要使用在线格式化程序或验证程序。特别是如果您正在处理一些机密的生产数据，则对任何在线工具都是严格禁止的。请改用任何本地编辑器或命令行工具。不要冒险将您公司的数据泄露到某个随机站点。（推荐工具：Cyber​​Chef - 下载离线使用）
(41) 永远，永远不要在你的代码库中推送任何敏感信息。在提交和推送之前，请务必仔细检查您的代码是否包含电子邮件地址、电话号码、密码、身份验证令牌、私钥等。
(42) 始终验证和清理用户输入。永远不要假设或期望用户会以正确的格式发送某些输入。并且在验证时总是更喜欢白名单而不是黑名单。
 

拉取请求：

(43) 猜猜看！您还可以在拉取请求评论中给予赞美。我们在复习的时候总是专注于不好的部分，小小的赞赏可以给你的同行带来微笑。下次试试。
(44) 将阅读拉取请求和理解其他开发人员的评论作为日常实践，以获得对功能和编码标准的不同观点。
(45) 代码格式和其他标准应该自动化。使用代码格式化程序和 linter 构建您的项目开发管道，以便整个代码库保持一致和干净。请停止在公关评论中争论标签与空格的问题！
(46) 创建简短的拉取请求。如果您正在处理多个功能，请将它们分成多个 PR。并且给审稿人足够的审稿时间，不要在部署前一小时创建PR。
 

学习：

(47) 作为一名程序员，你应该从根本上享受学习和探索。如果你不喜欢它们，你应该认真考虑其他职业选择。
(48) 你不需要学习进入市场的每一种技术。随时了解趋势，但在需要时学习和使用它们。
(49) 从一个刚毕业的大学实习生那里也能学到很多东西。永远不要将您的学习范围仅限于担任更高职位的人。
(50) 阅读您使用的不同开源项目的源代码，以了解和学习干净的代码实践和代码组织。
(51) 学习某些技术的最好方法是自己构建一个高度简化的版本。( https://github.com/danistefanovic/build-your-own-x )
(52) 几天之内学一门语言很容易。但了解其生态系统需要数月或数年的时间。
(53) 探索不同的编程语言以理解不同的范式。了解不同的编程范式将帮助您为您的用例选择正确的语言。
(54) 学习 Git。不只是 git pull 和 git commit，了解所有高级概念。无论您使用何种技术，git 都将保持普遍。
(55) 鉴于大多数开发人员的工作都集中在网络/网络编程上。了解网络系统中的底层协议很有帮助：HTTP、HTTPS、SSL/TLS、DNS、SMTP、IPv4、IPv6 等。
(56) 拥有良好的 CSS 专业知识将使您看起来像个巫师！如果您是一名全栈 Web 开发人员，花几天时间掌握 CSS 将节省“我不知道自己在做什么”的时间。
(57) 吸引人的 UI 设计比强大的系统架构更容易给人们留下深刻印象（显然不是指领域专家）。因此，当您进行概念验证时，拥有良好的设计技能会派上用场。（只是不要通过在 HTML 中硬编码所有内容来滥用它）
 

生产率：

(58) 创建细粒度的子任务来跟踪您的进度，尤其是当您正在处理一项巨大的任务时。很难描述检查某事完成后的幸福感，这反过来又会激励你保持正轨。
(59) 不要试图同时处理多项任务。专注于一项任务并尽量减少上下文切换。上下文切换的成本高于您的预期。
(60) 改进和自定义您的工作流程（IDE、调试工具、生产力工具、CI/CD），以便您可以更快地迭代。迭代越快，失败的速度就越快。你失败得越快，你学得就越快。
(61) 花时间在自动化日常任务上。如果你做的事情不止两次，那就写一个工具让它第三次自动化。同时，不要浪费数小时/数天来自动化一项几乎不需要几分钟的简单任务。找到正确的平衡点！
(62) 用文件夹和标签组织您的工作邮件（个人邮件也是如此）。每天组织邮件的小努力将帮助您在需要时快速找到重要的文档或对话。
(63) <Esc> + :q! + 退出 Vi 编辑器！认真地说，学习基本的 Vi 绑定，即使 Vi 不是您的默认编辑器，您也可以在几乎所有可用的文本编辑器中使用 Vi 绑定，相信我，在那之后您的工作效率会飙升。
(64) 文档技能在这个行业中被严重低估。学习如何编写设计文档、更改提案等。开始使用笔记工具来组织和记录几乎所有内容 - 妈妈、个人目标、职业目标、随机想法、书籍摘要，等等。（推荐工具：Notion）
(65) 在对您的任务进行估算时，请始终保留一些缓冲时间。你永远不知道在一个未开发的洞穴中会遇到什么怪物。
(66) 最好听器乐或lo-fi 节拍或平静的声音，而不是带歌词的音乐。就我个人而言，我觉得我在器乐方面更有效率，而且科学也支持它并不奇怪。
 

自己：

(67) 立即在办公桌前调整您的身体姿势！
(68) 工作之余有不同的爱好是好事。仅仅因为您是开发人员，您就不需要 24x7 编码。
(69) 善待每一个人！时刻保持冷静！最重要的是，要谦虚！
(70) 记得定期休息。不要烧坏自己。
(71) 投资于良好的工作站设置。鉴于您大部分时间都在办公桌前度过（尤其是在这些远程工作日期间）。在高质量的产品上多花几分钱是值得的。
(72) 阅读不同的认知偏差。它不仅会帮助您做出更好的个人决策，还会帮助您做出更好的技术决策。
(73) 在你的职业生涯早期就开始投资。了解复利的力量，相信我，它很神奇。同时不要过度储蓄，当你不享受现在的时候，储蓄一切又有什么意义呢？就是这样，没有更多的财务建议。
 

人际关系：

(74) 人际交往能力与您的技术技能一样重要。练习指导、公开演讲、领导项目等。开发人员不需要遵循社交无能的刻板印象。
(75) 不是每个人都会有和你一样的动机。永远不要指望别人会因为你这样做而对任何话题感到兴奋和表现出兴趣。不同的人对不同的动机做出反应。
(76) 不要用你的同事（实际上是任何人）不知道的东西来判断他们。
(77) 学习如何推销自己。您可能在很多方面都非常熟练，但如果您没有在正确的平台上展示这些技能，那么没有人会欣赏它。
(78) 帮助周围的人变得更好。教授或分享您学到的东西。对你所学的东西进行教学或写作会让你更好地理解它。
(79) 永远不要犹豫说“我不知道”。你可能是一个很好的骗子，但我们的大脑在发现某人是否在撒谎或假装方面是惊人的。更糟糕的是，伪造会导致更高的期望。
(80) 你的团队中总会有一位摇滚明星开发者，他几乎可以解决任何问题。不要被他们的技能吓倒，而是阅读他们的拉取请求，进行技术聊天，并定期从他们那里获得反馈以提高自己。
(81) 你很有可能在工作中遇到你的BFF。不要向同事敞开心扉。（请自行决定是否采纳此建议）
 

沟通：

(82) 一直在听，我再说一遍：听！
(83) 开会没有什么要说的也没关系，不要乱说话，浪费别人的时间。
(84) 不要只用 Hi/Hello/Good Morning! 给别人 IM，然后等待他们的回复。给他们你为什么 ping 的原因。没有人只想听到你的问候或祝福。https://www.nohello.com/
(85) 在解释您的设计时，尽可能使用图表。一张图片胜过千言万语。它也可用于记录。（推荐工具：draw.io）
(86) 在向某人解释某些设计或概念时，减少行话的使用。并非每个人都熟悉所有技术术语。以适当的平衡使用它们。
(87) 提出一个你认为微不足道或愚蠢的问题，你不应该感到羞耻。
(88) 如果您想在几分钟内完成工作，请致电。如果你想在几个小时内完成工作，那么 IM。如果你永远不想完成工作，那么电子邮件（人们在 2021 年仍然使用电子邮件吗？）。
(89) 当你就某个问题向某人寻求帮助时，不要只是四处说“嘿 X 不起作用，你能帮帮我吗？”，而是说“嘿，当我运行 X 时，我正面临错误Y，我已经研究并尝试了解决方案 Z，但它似乎也不起作用，你能帮我解决这个问题吗？”。在接受别人的帮助之前做你的研究，请不要因为你的代码中的一些错字而浪费别人的时间，认真！
(90) 不要成为自行车棚效应的牺牲品。在会议或讨论中，将复杂/关键项目置于琐碎项目之上。
 

职业：

(91) 做自己不喜欢的事情是可以的，但做自己讨厌的事情是不可接受的。
(92) 在职业生涯早期，将学习和机会置于薪酬、福利等之上。在学习率高的活动或工作上投入更多时间。学习化合物，你必须尽早开始才能获得它的好处。
(93) 你在工作中的纯粹动机应该是为团队和项目增加价值，而不是为了给任何人留下更高的薪水或升职。如果处理好前者，后者只是副产品。
(94) 花时间在简历上并始终保持最新状态。建议拥有一个描述您的项目和经验的作品集网站。
(95) 你解决的问题越是模糊不清，你的角色就越高。适应不确定性和模糊性。
(96) 每六个月问自己这些问题：
我是否正在学习新技能并拓宽我的专业领域？
我是否在组织中产生影响？
我的技能和经验是否足够好？
如果你的答案都是否定的，那么你必须考虑更换公司或团队。如果你已经在现在的公司工作了 2-3 年以上，并且你的答案都是肯定的，那么你仍然应该考虑换公司，或者至少对它持开放态度。除非你一直在寻找，否则你永远不会知道你错过了什么。

(97) 如果仔细观察，编程与写作非常相似。编程语言类似于人类语言，程序员类似于作家/诗人。任何人都可以成为作家，但要成为一名优秀的作家需要付出很多努力和时间。
(98) 定期与您的经理进行一对一交流并寻求反馈。不要等到您的年度审查才突然出现惊喜。
(99) 如果你的经理不对你的失败负责，并没有责怪你，那么你在他们手下工作是在冒着个人和职业发展的风险。
(100) 年的经验只是一个数字。有时您会发现初级工程师比高级工程师更熟练。不要误会我的意思，经验教给你的不仅仅是技能，所以是的，工作经验很重要，但这不是唯一的因素。
