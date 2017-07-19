# 前端周刊第61期：你离 CTC 有多远？

> 最近<a href="http://www.sohu.com/a/150680910_612370">阿里云的美女工程师张秋怡被 Node.js 社区吸纳为 CTC（核心技术委员会）成员</a>，只有对 Node.js 社区有足够大贡献的人，才会被吸纳为 CTC 成员，张秋怡做了哪些贡献？如果你想参与开源社区，她是个很好的参照。本周信息量最大的部分非 <a href="https://conferences.oreilly.com/fluent/fl-ca/public/schedule/grid/public/2017-06-21?view=list">Fluent Conf 2017</a> 莫属了，我只是给了个入口，爱学习的同学自己去折腾吧。

### 技术动态

#### [Webpack 3 发布正式版](https://medium.com/webpack/webpack-3-official-release-15fd2dd8f07b)

虽然 Webpack 3 正式版发布两周了，但是是个非常值得收录的事件，本次发版完全是提供社区投票所产生的功能需求，并且不再像之前那样不同版本之间不相互兼容。本次发版的旗舰特性是 Scope Hoisting，目的是为了提高打包后代码的运行效率，其他特性更包括 Magic Comments，能让打包后的代码更易阅读，如果还有其他你想要的特性，可以去它的投票页面看看。

#### [Vue Conf 2017 国外版演讲精选](http://vuejsdevelopers.com/2017/06/25/vue-conf-2017/?jsdojo_id=revue_vcf&utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=Anthony%20Gore)

上周在波兰举行的 Vue Conf 2017 已经结束，与会人数超过 300 人，虽然声称是全球首届，但是实际上比国内的要晚一个月左右，这篇文章精选了本次大会中几个比较精彩的演讲，感兴趣的同学可以看看，想提高英语的同学，可以对照着中文看看尤雨溪的开题演讲。

#### [Fluent Conf 2017 日程表](https://conferences.oreilly.com/fluent/fl-ca/public/schedule/grid/public/2017-06-20?view=list)

那个用各种动物做书籍封面的出版社也喜欢组织各种技术交流大会，Fluent Conf 算是 WEB 领域综合性的技术交流大会，我连续看了几年，每次都收获不小。这个日程表上有很多演讲的讲稿，如果想看视频自己去搜吧，大会共 4 天，前 2 天是各种 Workshop、短期闭门培训，后 2 天演讲比较多。

#### [React Native 月刊第 1 期](http://facebook.github.io/react-native/blog/2017/06/21/react-native-monthly-1.html)

React Native 社区大玩家组织的月度会议纪要，诸如 Airbnb、Shouten、Wix 等公司都会通报他们遇到的问题、在解决的问题、工程经验，从中不难窥探出 React Native 大致的演化方向：模块化，也能看到这些大玩家在使用哪些工具更好的解决 React Native 应用的问题，比如打包工具、E2E 测试工具。

### 文章教程

#### [注释良好的 CSS 代码应该长啥样？](https://css-tricks.com/well-documented-css-codebase-look-like/?utm_source=CSS-Weekly&utm_campaign=Issue-271&utm_medium=email)

社区中就代码可维护性的讨论 JS 比 CSS 多太多，实际上 CSS 也是写起来容易，维护起来难的语种，注释和文档良好的 CSS 代码能够保障代码一致性，大幅度提高代码可维护性，帮助团队形成编码时的“共同语言”，那么注释良好的 CSS 代码该包含哪些要素呢？理解这篇文章再加以实践，相信能提高不少。

#### [为什么我选 React 而不是 Vue](https://medium.com/@CalinLeafshade/why-i-chose-react-over-vue-3dd9a230b507)

React 和 Vue 可以说是当下大热的前端框架，而笔者对 Vue 的第一印象是：它怎么既像 Angular 又像 React。本文作者用 React 和 Vue 做过几个项目之后，还是更加倾向于使用 React，并给出了他的三大理由，技术选型没有最好的，只有最合适的，如果你是 Vue 的死忠粉，更应该看看这个。

#### [React 组件解耦重构的技巧](https://medium.com/dailyjs/techniques-for-decomposing-react-components-e8a1081ef5da)

有没有写过 render 函数巨大无比的 React 组件？为啥别人的 React 组件代码看起来那么优美？可能是因为没意识到这样做的好处，也可能是因为没有掌握方法论，这篇文章奉上 3 个立即可用的 React 组件解耦重构方法。

#### [Express.js 中的 Session 是如何工作的？](http://nodewebapps.com/2017/06/18/how-do-nodejs-sessions-work/)

几乎所有需要维护用户数据、会话状态的 WEB 应用都需要使用 Session，作为开发者不光要知道如何使用 Session 还要知道它是如何工作的。这篇文章介绍了 Session 是什么？如何存储 Session 数据？如何确定 Session 的存储介质？常见的安全问题和对策。

#### [边学开发边赚钱的最佳姿势](https://hackernoon.com/the-best-way-to-learn-development-skills-while-getting-paid-in-the-process-a31bfb138287)

传统观念都会认为学技能是需要交学费的，有没有可能在学会技能的过程中就开始赚到钱呢？答案是肯定的，尤其是在这个时代，从事创造性劳动的都极有可能获得。这篇文章就介绍了如何在学习开发技能的同学赚到钱的思路，虽然作者只赚了 $11，但是这是一个质的提升。

#### [像产品一样优化你的交付流水线](https://medium.com/mydr-engineering/treat-your-build-pipeline-as-a-product-61a1b24ae538)

靠谱工程师应该具有的三观：技术观、产品观、数据观，本文介绍了如何将 13 条产品设计原则应用到软件交互流水线优化上，取得的效果是平均每天节省 13 个工程师工时，相当于两人日的资源，能做出这样事情的人，贡献的价值自然是巨大的。总之，这是篇道与术并存的文章，如果你只是想优化自己的交付流水线或者学习通用的产品设计原则，都是非常值得阅读的。

### 开发工具

#### [Pencil：类 Sketch 的开源图表软件](https://github.com/evolus/pencil)

Pencil 项目的愿景是提供所有人都可以免费试用的图表只做软件，完全基于 Electron 开发，目前提供的功能还算强大，如果你是个喜欢平面设计的前端工程师，这个仓库是个很不错的参与开源社区的机会。

#### [Detox：APP 端到端测试的利器](https://github.com/wix/detox)

Detox 是高性能的 APP 端到端测试框架，能够在真实设备上运行测试，如真是用户般和 APP 交互，并且提供了天然的 React Native 支持，能够很好的与你的持续集成环节结合起来，并且可以很方便的与 Mocha、Ava 结合使用。

#### [支持事务的 MongoDB 操作库](https://github.com/e-oj/Fawn)

不支持事务是 MongoDB 和其他数据库引擎相比的劣势，而这个仓库基于 MongoDB的两阶段提交特性提供了类似于事务的操作，你可以通过他指定一系列操作，要么全部成功，要么全部失败回滚，不理解事务是啥的同学可以去看看银行转账的例子。

#### [Vue 开发者工具火狐版](https://addons.mozilla.org/en-US/firefox/addon/vue-js-devtools/)

虽然现在身边几乎见不到使用火狐浏览器开发调试的同学了，这个工具还是值得发出来，是 Vue.js 原作者尤雨溪发布的。

### 精彩问答

#### [MongoDB 如何给所有的文档增加随机数？](https://stackoverflow.com/questions/27065279/update-all-documents-in-a-collection-with-random-numbers)

不需要编写复杂的脚本，因为 MongoDB 中可以执行 JS 代码，如果你恰巧也有类似的需求，此文可作为快速参考。

#### [React Native 中如何禁用屏幕旋转？](https://stackoverflow.com/questions/32176548/how-to-disable-rotation-in-react-native)

准确的表述问题应该是：如何在 XCode 配置应用不响应屏幕旋转，适用于 Native 和 React Native，配置方法很简单，还附带赠送了 Android 中的配置方法。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking

