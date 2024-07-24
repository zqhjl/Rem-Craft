# 版本日志 | Changelog 


### [3.0.2](https://github.com/ba0gu0/Rem-Craft/compare/v3.0.1...v3.0.2) (2024-07-24)

### [3.0.1](https://github.com/ba0gu0/Rem-Craft/compare/v3.0.0...v3.0.1) (2024-07-24)

## 3.0.0 (2024-07-24)


### ⚠ BREAKING CHANGES

* 使用了scss @use 特性，重构了所有文件
* 参考TDesign的文件目录组织结构，添加色板和全局Token，提高代码的延展性

### ⚡ 性能提升 | Performance Improvements

* :zap: 修改行内超链接块写法，提高可维护性 ([fa4c050](https://github.com/ba0gu0/Rem-Craft/commit/fa4c0505c12dc9650227faf2378b62b9769e0306))
* :zap: 重构顶部页签栏，提升性能 ([2bc25e4](https://github.com/ba0gu0/Rem-Craft/commit/2bc25e40d7c744683d8957b11ae88ef7cd312b30))
* **components:** :zap: 重新构建list样式的依赖关系，减少编译后的代码量，增加代码可读性 ([908d10d](https://github.com/ba0gu0/Rem-Craft/commit/908d10da64553e5dce1b512c3d7df4676f9bce54))
* **layout:** :zap: 重新构建wnd样式的依赖关系，减少编译后的代码量，增加代码可读性 ([58fe087](https://github.com/ba0gu0/Rem-Craft/commit/58fe087fcae8e32dcc34f3ae04896da9e042a93a))
* 重新构建button样式的依赖关系，减少编译后的代码量，增加代码可读性 ([eb8beba](https://github.com/ba0gu0/Rem-Craft/commit/eb8beba1ba68c8567233d00555268ae3ab70990f))
* 重新构建menu样式的依赖关系，减少编译后的代码量，增加代码可读性 ([ae49b70](https://github.com/ba0gu0/Rem-Craft/commit/ae49b70217501ec9adf5e1df8798db04976dab16))
* 重新构建文本框样式的依赖关系，减少编译后的代码量，增加代码可读性 ([18fa89e](https://github.com/ba0gu0/Rem-Craft/commit/18fa89e5876c2051883eb7598da3db1acc9bb61e))


### ♻️ 代码重构 | Code Refactoring

* :recycle: 优化dock栏监听写法 ([69bbd4d](https://github.com/ba0gu0/Rem-Craft/commit/69bbd4de7d68e40fed8f9891a59234dd6f5e9392))
* :recycle: 优化scripts目录结构 ([77b4520](https://github.com/ba0gu0/Rem-Craft/commit/77b452090bec98b2d006e631d5bfd4a36531a113))
* :recycle: 初步重构顶部页签栏 ([a2f9247](https://github.com/ba0gu0/Rem-Craft/commit/a2f92479c6f337cd22684d9267ffaffd89b9bd6e)), closes [#67](https://github.com/ba0gu0/Rem-Craft/issues/67) [#72](https://github.com/ba0gu0/Rem-Craft/issues/72)
* :recycle: 将文档列表缩进代码抽出，实现用户自定义 ([8355802](https://github.com/ba0gu0/Rem-Craft/commit/83558024aac61439e775a1b48f11a952e177531b))
* :recycle: 覆写map.get函数，增加警告提示 ([b30083a](https://github.com/ba0gu0/Rem-Craft/commit/b30083a7cb126b0f563c61cd75c14eda67815965))
* :recycle: 重构base相关文件 ([8de2dea](https://github.com/ba0gu0/Rem-Craft/commit/8de2deaf9d683fa2e2093ece763d160c8c4e699b))
* :recycle: 重构component相关 ([ac174ce](https://github.com/ba0gu0/Rem-Craft/commit/ac174cefc6e0c7518902a5598fc6c3bf4f759bc0))
* :recycle: 重构css公共变量 ([a9ac479](https://github.com/ba0gu0/Rem-Craft/commit/a9ac4793124719c944961ca9fc0ca4cfdf014592))
* :recycle: 重构dialog相关 ([7459020](https://github.com/ba0gu0/Rem-Craft/commit/7459020f69e42488194ee7fd424d2e9ebba247e6))
* :recycle: 重构layout相关代码 ([9c916df](https://github.com/ba0gu0/Rem-Craft/commit/9c916dfbd175c8f67c0cf95525084ade3d5b41f7))
* :recycle: 重构panel相关 ([8a17e10](https://github.com/ba0gu0/Rem-Craft/commit/8a17e10cb5291f8728117b2301aeced8a1aa3ebe))
* :recycle: 重构protyle相关 ([32b89f6](https://github.com/ba0gu0/Rem-Craft/commit/32b89f690c736a0d25a13f7cda821680702bafd5))
* :recycle: 重构theme.js，增加scripts文件目录，提高可维护性 ([c9d25ba](https://github.com/ba0gu0/Rem-Craft/commit/c9d25baea4843b3372d87372c366ad4c88b96d9f))
* :recycle: 重构公共变量 ([fbfbbb6](https://github.com/ba0gu0/Rem-Craft/commit/fbfbbb67639d20203b066968c544ff0f181d6792))
* :recycle: 重构提示条代码 ([6de28e7](https://github.com/ba0gu0/Rem-Craft/commit/6de28e70a1b813651762b930f9aedbfddc868bed))
* :recycle: 重构文件目录，将link-icon转移到plugin目录下，并恢复wnd动画 ([9a22fac](https://github.com/ba0gu0/Rem-Craft/commit/9a22fac85f76f864c39724a7d5a0fec287dba106))
* :recycle: 重构目录结构 ([a314038](https://github.com/ba0gu0/Rem-Craft/commit/a314038a7030e4be2c4b320a4879045ccfc64c0a))
* :recycle: 重构边栏代码 ([3e5c248](https://github.com/ba0gu0/Rem-Craft/commit/3e5c248984ffdbd2595f3bd6c3a9ec31b37f8f22))
* :recycle: 重构静态资源加载方式 ([5fda915](https://github.com/ba0gu0/Rem-Craft/commit/5fda91536bc395e574a343c94f4233d6d9d6aaf6))
* :recycle: 重构顶栏代码 ([a072872](https://github.com/ba0gu0/Rem-Craft/commit/a07287225c5e7d339104149c8294a29537af3db5))
* 代码重构 ([83c0e43](https://github.com/ba0gu0/Rem-Craft/commit/83c0e437cf0330f824ad126c73834cbd7690dd22)), closes [#15](https://github.com/ba0gu0/Rem-Craft/issues/15) [#18](https://github.com/ba0gu0/Rem-Craft/issues/18) [#21](https://github.com/ba0gu0/Rem-Craft/issues/21)


### ✨ 新增功能 | Features

* :sparkles: 为非最大化窗口添加边框 ([0605908](https://github.com/ba0gu0/Rem-Craft/commit/0605908addfe9abc38ae62c282cd3415d857186f))
* :sparkles: 优化Dock栏样式 ([60884f4](https://github.com/ba0gu0/Rem-Craft/commit/60884f4e1398d634a54fef23fd2db73f0b958bf4)), closes [#51](https://github.com/ba0gu0/Rem-Craft/issues/51)
* :sparkles: 优化list的竖向滚动条显示 ([cd713c4](https://github.com/ba0gu0/Rem-Craft/commit/cd713c4ab5da096a33b0777828da8c3a0f602574))
* :sparkles: 优化块嵌入样式，提高可读性 ([f8f7ff3](https://github.com/ba0gu0/Rem-Craft/commit/f8f7ff3de44c1aa606718ba69000864fa8ab6ae8))
* :sparkles: 优化行内图片的按钮样式 ([204bcb9](https://github.com/ba0gu0/Rem-Craft/commit/204bcb9582a4f9c3a25117425ad42e504337155d))
* :sparkles: 参考obsidian改进页签 ([afa3053](https://github.com/ba0gu0/Rem-Craft/commit/afa3053527d8aac86fe01a2e9b68d89a495a8899))
* :sparkles: 在无子元素的列表项前增加圆点，增强可读性 ([738208a](https://github.com/ba0gu0/Rem-Craft/commit/738208a0725cd314b19923176e95133546ef607e))
* :sparkles: 增加子弹流列表辅助线功能 ([cec3bfb](https://github.com/ba0gu0/Rem-Craft/commit/cec3bfb96e981ccd1fde0720cc0de27481a32266))
* :sparkles: 增加新的超链接块图标 ([d5d6f1a](https://github.com/ba0gu0/Rem-Craft/commit/d5d6f1a5c723b06061b427863f1f2f4cc6acb03a))
* :sparkles: 增加日历面板 ([f097ff3](https://github.com/ba0gu0/Rem-Craft/commit/f097ff321409d167b2d5e1fccb2bd91e5481f5e1)), closes [#69](https://github.com/ba0gu0/Rem-Craft/issues/69)
* :sparkles: 完善one-dark暗黑模式风格 ([3b7e8df](https://github.com/ba0gu0/Rem-Craft/commit/3b7e8dfcdb8f29887003611b2cc58a749a8b9925))
* :sparkles: 将主题css变量与样式主文件解耦 ([91d68cc](https://github.com/ba0gu0/Rem-Craft/commit/91d68cccc1a8e09e2ece63f881748adf53de2854))
* :sparkles: 将页签栏固定在顶栏，并修改相应布局样式 ([8bf2f1c](https://github.com/ba0gu0/Rem-Craft/commit/8bf2f1c2e7e147c293691b8f120c6c39165d34d8))
* :sparkles: 整合siyuan-comment功能 ([210cffb](https://github.com/ba0gu0/Rem-Craft/commit/210cffbfb4748819d89cf17ef50ed069bdf95a0f)), closes [#46](https://github.com/ba0gu0/Rem-Craft/issues/46)
* :sparkles: 明暗切换 ([b73e3be](https://github.com/ba0gu0/Rem-Craft/commit/b73e3be3e205ba2da677d999cf812ed7c6c9d183))
* :sparkles: 更换日历插件 ([6b704f6](https://github.com/ba0gu0/Rem-Craft/commit/6b704f694d96cd04f961c0001c3c698352bef72c))
* :sparkles: 更改iframe块样式 ([8af8609](https://github.com/ba0gu0/Rem-Craft/commit/8af86099a0b416c67961ebf0f2f1bb4b16ffef88))
* :sparkles: 更改渲染块操作菜单样式 ([5a6b3b3](https://github.com/ba0gu0/Rem-Craft/commit/5a6b3b34133502d68a305112a711f02f6ca45e26))
* **components:** :sparkles: 修改文档树、书签的一级列表项和大纲标题的样式 ([5e34ccb](https://github.com/ba0gu0/Rem-Craft/commit/5e34ccb117a43065cad146490aa16a392d2b931c))
* **components:** :sparkles: 更新滑条动画，缩小滑块大小 ([8c02a02](https://github.com/ba0gu0/Rem-Craft/commit/8c02a02763183c4fafd37b260af576686f19c202))
* pDF导出弹窗样式更新 ([a7d0a6e](https://github.com/ba0gu0/Rem-Craft/commit/a7d0a6e4ea30d57d5da8b07f070fc41d1e3f1f49))
* 优化低层阴影样式 ([83dfbd3](https://github.com/ba0gu0/Rem-Craft/commit/83dfbd3c51205582456e0b20287faba91ebc6f26))
* 优化滑条样式 ([1fd2c9a](https://github.com/ba0gu0/Rem-Craft/commit/1fd2c9aa085d5ca5b347743fc5e05dcba999e0a9))
* 修改数据历史界面样式 ([505d94d](https://github.com/ba0gu0/Rem-Craft/commit/505d94d67de249418c53c797e98c9dbc482b0b7e))
* 兼容最新版本底栏 ([3f26e0b](https://github.com/ba0gu0/Rem-Craft/commit/3f26e0bb6f644b9fa1b5623adf675c510e94053c))
* 兼容最新版本顶栏 ([0f4aadf](https://github.com/ba0gu0/Rem-Craft/commit/0f4aadf661d7adf3806310585394460833e310c2))
* 完善小弹窗的内容样式 ([c698ac3](https://github.com/ba0gu0/Rem-Craft/commit/c698ac39b5bdd147301950b7c2e4264e44ddf420))
* 更新全屏后的顶栏样式 ([4150ffe](https://github.com/ba0gu0/Rem-Craft/commit/4150ffe6cbe8784a68e410b51f15978c15da2b79))
* 更新关系图设置面板样式 ([7d1dda8](https://github.com/ba0gu0/Rem-Craft/commit/7d1dda8a00273243ed80906227e3d73ba6261df0))
* 更新底栏各项目颜色 ([6c5718c](https://github.com/ba0gu0/Rem-Craft/commit/6c5718c4eab4b1ab0697cd7370863c983d3f4a3b))
* 更新数据历史界面样式 ([0208658](https://github.com/ba0gu0/Rem-Craft/commit/02086586a6c245ae4ca0b1b2814e7991a01b06c3))
* 更新计数块样式 ([a8db2cf](https://github.com/ba0gu0/Rem-Craft/commit/a8db2cfaf16e6a7eb85d4ab3a59921145b764600))
* 添加最新版本底栏样式 ([16aeffd](https://github.com/ba0gu0/Rem-Craft/commit/16aeffd14b9b5c181d10c271af280e1ca22cb136))
* 调整数据历史界面样式 ([9b1f951](https://github.com/ba0gu0/Rem-Craft/commit/9b1f951c4f4311f97041cf2f1ce6b6e4a7fde6ad))
* 调整标签搜索界面搜索按钮的样式 ([dc9fd11](https://github.com/ba0gu0/Rem-Craft/commit/dc9fd110923adf2ac54c473b7dec0d878fba76fe))


### ✏️ 文档更新 | Documentation

* :memo: 更新 readme ([1608684](https://github.com/ba0gu0/Rem-Craft/commit/16086846c7110102c43e84a6d5bebaedb4adc304))
* :memo: 更新readme ([27a8a83](https://github.com/ba0gu0/Rem-Craft/commit/27a8a8389f34babe78639dd0185b482e74dabf48))
* :memo: 更新readme ([71cfbae](https://github.com/ba0gu0/Rem-Craft/commit/71cfbae99683f3a911002b045f0318a8d4a3253f))
* :memo: 更新readme ([46840de](https://github.com/ba0gu0/Rem-Craft/commit/46840de79720f0c9426a16417eb8bf8e25837f84))
* :memo: 更新readme ([ca94fe1](https://github.com/ba0gu0/Rem-Craft/commit/ca94fe17f3f81ee8e443a60a9f75cd026c2ca24c))
* :memo: 更新readme ([0ac3bdf](https://github.com/ba0gu0/Rem-Craft/commit/0ac3bdfbb06ed73f8ad75174236cbafee96af5ea))
* :memo: 更新Readme ([4f198d0](https://github.com/ba0gu0/Rem-Craft/commit/4f198d08c7cfd996975b9e341803bb0c5fc37b15))
* :memo: 更新Readme ([f6a42fe](https://github.com/ba0gu0/Rem-Craft/commit/f6a42fe7efcfff1c1d7b9c1cd1d043470d7b5185))
* :memo: 更新Readme ([1a75134](https://github.com/ba0gu0/Rem-Craft/commit/1a7513456c8b37c7c1896c4b5e21778b96c04e03))
* :memo: 更新Readme，增加英文Readme及集市icon ([6f43c71](https://github.com/ba0gu0/Rem-Craft/commit/6f43c71b156f1f8b7c184447369ba7e10add02a3))
* :memo: 更新readme及预览图 ([d14d0e2](https://github.com/ba0gu0/Rem-Craft/commit/d14d0e2591dfac2bd14b5530a50345d00a2f3ca2))
* :memo: 更新readme和preview.png ([66db598](https://github.com/ba0gu0/Rem-Craft/commit/66db5986d16804d330b9290433cdd6e8325b2942))
* :memo: 更新readme和preview.png ([5612bab](https://github.com/ba0gu0/Rem-Craft/commit/5612babd562207ff548f15bbc43a3f7d99d22054))
* :memo: 更新Readme和preview.png ([d4ac738](https://github.com/ba0gu0/Rem-Craft/commit/d4ac738505ff99a6cdabeeefbff9f100c61b5099))
* :memo: 更新Readme和preview.png ([35a109d](https://github.com/ba0gu0/Rem-Craft/commit/35a109d0f4f1c3ef4148f4b4862cc2d41d70d2e9))
* :memo: 更新readme和preview.png，修改.versionrc ([7b252fd](https://github.com/ba0gu0/Rem-Craft/commit/7b252fd9d8e717f11727aa36ea18232a236f2fe2))
* :memo: 更新styles目录说明文档 ([021dd02](https://github.com/ba0gu0/Rem-Craft/commit/021dd02bda26edf87d15a903d08b179012980e63))
* 修改style目录下的文件说明 ([031b5da](https://github.com/ba0gu0/Rem-Craft/commit/031b5dabb231e7a1e9ae59234866becc23cf3fdb))
* 更新readme ([97bdbe3](https://github.com/ba0gu0/Rem-Craft/commit/97bdbe36bc03ed5cacff905b17192d59fb39bf2f))
* 更新readme ([3abd270](https://github.com/ba0gu0/Rem-Craft/commit/3abd270f8299da58a849d4fc7a729d7a8ad1f2af))
* 更新Readme ([9fda5b9](https://github.com/ba0gu0/Rem-Craft/commit/9fda5b939d90d9d996c01cfdc4300abb21957597))
* 更新Readme、preview.png、theme.json、package.json、样式文件目录说明 ([056e9b3](https://github.com/ba0gu0/Rem-Craft/commit/056e9b34a4fd9861fb15be1c5346e2b3540df35c))
* 更新预览图 ([a5f45a9](https://github.com/ba0gu0/Rem-Craft/commit/a5f45a9022ff2edf4e574f4673e888330f09e3ce))


### 📦‍ 构建相关 | Build System

* :package: 换用pnpm ([111e67e](https://github.com/ba0gu0/Rem-Craft/commit/111e67e246f65bfe304316c6624c53482b4a3b63))
* :package: 更新依赖 ([e6c7db4](https://github.com/ba0gu0/Rem-Craft/commit/e6c7db486baa211c83a20a47c28c7f926edb3706))
* :package: 更新依赖 ([4ac76c4](https://github.com/ba0gu0/Rem-Craft/commit/4ac76c4d0265d06cd2a7c106d5150c33b72c4af1))
* :package: 更新依赖 ([5bf56ee](https://github.com/ba0gu0/Rem-Craft/commit/5bf56ee2a36a52574bb15d44b33074a755c74412))
* **npm:** 更新 standard-version 和 sass 的依赖版本 ([be57e10](https://github.com/ba0gu0/Rem-Craft/commit/be57e1074c679dfdf441d92692ae5aef97430f78))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 优化block，减少重复代码 ([c9855ec](https://github.com/ba0gu0/Rem-Craft/commit/c9855ecbb839177031ae1351711be462d4af6e90))
* :bug: 优化ctrl + tab菜单 ([03d2d66](https://github.com/ba0gu0/Rem-Craft/commit/03d2d6656f28e7c7d22b8ed97993390b8ffa69d7))
* :bug: 优化link样式，减少重复代码 ([3a1918c](https://github.com/ba0gu0/Rem-Craft/commit/3a1918c523e1c402e6a737e62ad38d7137ec4b20))
* :bug: 优化mark的样式，增加可读性 ([d3d8be9](https://github.com/ba0gu0/Rem-Craft/commit/d3d8be90ff9f38293c386bf2e5666bf07355d8fb))
* :bug: 优化one dark暗黑模式细节 ([ba76aa7](https://github.com/ba0gu0/Rem-Craft/commit/ba76aa771169f54ed4cc33a5c838f053cf9a6e0f))
* :bug: 优化protyle-toolbar样式 ([b2fadae](https://github.com/ba0gu0/Rem-Craft/commit/b2fadaea93a587c1706c5dc46ad9a13e0aeaec62))
* :bug: 优化quote和gutter样式 ([5779060](https://github.com/ba0gu0/Rem-Craft/commit/5779060a84cb7033bd5df5b416fba1588c976182))
* :bug: 优化small-dialog代码 ([0b97c47](https://github.com/ba0gu0/Rem-Craft/commit/0b97c4733ca4a38231f15c8b316085e046d6bc44))
* :bug: 优化svg-div ([272819a](https://github.com/ba0gu0/Rem-Craft/commit/272819a59b754e20d77fec852729c4d15ad453e3))
* :bug: 优化tanBar写法，暂时删除边窗动画 ([dc0f0ee](https://github.com/ba0gu0/Rem-Craft/commit/dc0f0eee0f9fb957bb460d6d37bff01f57ac667c))
* :bug: 优化tooltips行高 ([768b3dd](https://github.com/ba0gu0/Rem-Craft/commit/768b3dd6f4fb5dd35ca7fbb5e90f8acc7b8883cd)), closes [#66](https://github.com/ba0gu0/Rem-Craft/issues/66)
* :bug: 优化win-control按钮样式，去掉编辑区域的overlay ([e5948d4](https://github.com/ba0gu0/Rem-Craft/commit/e5948d40d635848b8c76d061583d58e3405f298d))
* :bug: 优化一部分反链面板问题 ([5a032a4](https://github.com/ba0gu0/Rem-Craft/commit/5a032a4d285433f75d9a569bb265beea688d3b64))
* :bug: 优化中性色 ([8f8e396](https://github.com/ba0gu0/Rem-Craft/commit/8f8e396c1f0d1f47e9b038d545cc785b1a20d643))
* :bug: 优化了编辑器内各拖拽时的阴影 ([1d7c086](https://github.com/ba0gu0/Rem-Craft/commit/1d7c08648665e1b00f8a0c8101ae43f4414080d2))
* :bug: 优化代码块样式 ([2189e42](https://github.com/ba0gu0/Rem-Craft/commit/2189e4278fe3f5a0c4d296f94d3696610b5cf822))
* :bug: 优化代码块样式 ([ac3bcea](https://github.com/ba0gu0/Rem-Craft/commit/ac3bcea063975131467b4cf5fb1e5870f7e862c1))
* :bug: 优化代码语言选择按钮的样式 ([d89c15b](https://github.com/ba0gu0/Rem-Craft/commit/d89c15b30c75f4446fa58db55f39cc2ee0844be3))
* :bug: 优化代码选择语言弹窗列表的样式 ([14d2eaf](https://github.com/ba0gu0/Rem-Craft/commit/14d2eafcdda15fc294bfdc02a86af30924dfcab4))
* :bug: 优化分割线的样式 ([8c3804f](https://github.com/ba0gu0/Rem-Craft/commit/8c3804fd0df4fcf91de2d0e5002659d057533eb8))
* :bug: 优化列表块标按钮的样式 ([034b63e](https://github.com/ba0gu0/Rem-Craft/commit/034b63e8e11dbb4d286622a4f49e07c20830f5f5))
* :bug: 优化反链界面字号 ([90f1c9c](https://github.com/ba0gu0/Rem-Craft/commit/90f1c9cd44b920cde74d11164670dc38cf70599b))
* :bug: 优化反链编辑器内块标按钮样式 ([1bfe457](https://github.com/ba0gu0/Rem-Craft/commit/1bfe4572279a68aeb55b6defccf214e65c5b0473))
* :bug: 优化反链面板样式 ([439cd36](https://github.com/ba0gu0/Rem-Craft/commit/439cd36c5ae002daffcb8cfcb69ddaacad98bbde))
* :bug: 优化反链面板面包屑样式 ([0436218](https://github.com/ba0gu0/Rem-Craft/commit/04362183216d6830a7af2463bd07e665182fdb3b))
* :bug: 优化各块折叠后的样式问题 ([eae51de](https://github.com/ba0gu0/Rem-Craft/commit/eae51de93d59640f50d976b19a49c9fded056b1b))
* :bug: 优化各处编辑区域的左右padding ([f719b4c](https://github.com/ba0gu0/Rem-Craft/commit/f719b4c592dec2bc194d881e828e630bc6fbd055))
* :bug: 优化块元信息样式 ([e2f9664](https://github.com/ba0gu0/Rem-Craft/commit/e2f96646be318c5a849418d92892647cf8a55276))
* :bug: 优化块引用菜单列表项内命名、别名等元信息的样式 ([b5d0bf1](https://github.com/ba0gu0/Rem-Craft/commit/b5d0bf10130eec34fec1f24e968633560e5459f0))
* :bug: 优化大弹窗左侧tab栏 ([0ea1bc6](https://github.com/ba0gu0/Rem-Craft/commit/0ea1bc64b81076aef35f83e880a9548e7f718090))
* :bug: 优化字体 ([b0fc6cf](https://github.com/ba0gu0/Rem-Craft/commit/b0fc6cf32a78f8fd61e902da3a7d6f963ae264f8))
* :bug: 优化字体 ([4ce0f18](https://github.com/ba0gu0/Rem-Craft/commit/4ce0f1881bed558a7d7d4cc8869baa4d9ec82418))
* :bug: 优化字体菜单按钮样式 ([15fc6db](https://github.com/ba0gu0/Rem-Craft/commit/15fc6db1c8045e5fb07051206e2e9e1034c5c7b8))
* :bug: 优化导出为图片弹窗样式 ([a2bb46f](https://github.com/ba0gu0/Rem-Craft/commit/a2bb46f33d24abdf6320de580c98e5069525c4bd))
* :bug: 优化小弹窗样式 ([5cfd005](https://github.com/ba0gu0/Rem-Craft/commit/5cfd00541fe5a87fc93e56342c7e751fcb1e2a1d))
* :bug: 优化嵌入块样式 ([d084455](https://github.com/ba0gu0/Rem-Craft/commit/d0844558560841f56bb50503a8a43b914109b85b))
* :bug: 优化已关闭的笔记本按钮样式 ([d40f8f6](https://github.com/ba0gu0/Rem-Craft/commit/d40f8f6a8231056b44929d8fd9a3332918ece128))
* :bug: 优化已关闭笔记本的样式 ([f285598](https://github.com/ba0gu0/Rem-Craft/commit/f285598a2a379b78b9eb571bd091877b45a2cae6))
* :bug: 优化底部状态栏的样式 ([91b13ef](https://github.com/ba0gu0/Rem-Craft/commit/91b13ef53f26c0426801beca1a513b7b06caf8ee))
* :bug: 优化开关样式 ([ab8ec4c](https://github.com/ba0gu0/Rem-Craft/commit/ab8ec4c34ba223df782b761f5594c29e24511fd1))
* :bug: 优化开关样式，更贴合win11风格 ([9630104](https://github.com/ba0gu0/Rem-Craft/commit/9630104aafff694937cf536f05e83bc8ed53cc97))
* :bug: 优化引述块内首个标题块的样式 ([28e0864](https://github.com/ba0gu0/Rem-Craft/commit/28e08649f1563458b6b0c5dc1f3637266cf9d6b7))
* :bug: 优化引述块和块标按钮的样式 ([93ebcec](https://github.com/ba0gu0/Rem-Craft/commit/93ebcec09b472c9602e08392e56dcc012090b9fd))
* :bug: 优化引述块样式 ([d3d11ed](https://github.com/ba0gu0/Rem-Craft/commit/d3d11ede2e62ce9cebec896bc63ea8bcb33c5bc9)), closes [#58](https://github.com/ba0gu0/Rem-Craft/issues/58)
* :bug: 优化引述块样式 ([53662e2](https://github.com/ba0gu0/Rem-Craft/commit/53662e255a6b35c59cc10e7ecf72f22c83e197e8))
* :bug: 优化快捷键设置页面的样式 ([fd1e375](https://github.com/ba0gu0/Rem-Craft/commit/fd1e3751627a89b631191fd6994e8928e7eb1f4b))
* :bug: 优化搜索筛选菜单 ([91d5d48](https://github.com/ba0gu0/Rem-Craft/commit/91d5d484775387e76c54b2d0557662f48ac0bff9))
* :bug: 优化搜索行高度 ([f234c85](https://github.com/ba0gu0/Rem-Craft/commit/f234c85f96da822ed1778b3e76c83693df6fc4e3))
* :bug: 优化数据历史界面样式 ([b509cbc](https://github.com/ba0gu0/Rem-Craft/commit/b509cbc92dfce8d8e60c8897fa90485025638dee))
* :bug: 优化文档区域底部空白面积 ([09416e4](https://github.com/ba0gu0/Rem-Craft/commit/09416e4b4aa242a5a8d98495a6437dd170683e92))
* :bug: 优化文档按钮组的样式 ([1606599](https://github.com/ba0gu0/Rem-Craft/commit/16065990d0c2eed9c707c2727d61b50c7667887f))
* :bug: 优化日历挂件 ([5883b91](https://github.com/ba0gu0/Rem-Craft/commit/5883b918b200833f6b946373dc968ef82321bcec))
* :bug: 优化日历挂件样式 ([01c1dc8](https://github.com/ba0gu0/Rem-Craft/commit/01c1dc893344c839522f5c04aa3545511451ba28))
* :bug: 优化日历样式 ([6909c79](https://github.com/ba0gu0/Rem-Craft/commit/6909c7987e128b066614e47691ebcfb13811bbbf)), closes [#120](https://github.com/ba0gu0/Rem-Craft/issues/120)
* :bug: 优化暗黑模式下的关闭按钮样式 ([0553410](https://github.com/ba0gu0/Rem-Craft/commit/0553410aaf92c5fab6ce86bac234525f89c2b98c))
* :bug: 优化有序列表序号样式 ([cdde49a](https://github.com/ba0gu0/Rem-Craft/commit/cdde49afcfec9aa8b2968ac5950d0f661d419279)), closes [#66](https://github.com/ba0gu0/Rem-Craft/issues/66)
* :bug: 优化标签块的可读性 ([5b56cfd](https://github.com/ba0gu0/Rem-Craft/commit/5b56cfde1a77ef9fc441e598abab723094bfb8e7))
* :bug: 优化标记本文样式 ([4134bfc](https://github.com/ba0gu0/Rem-Craft/commit/4134bfc06990804a2fb0d885b670030dee2a817d)), closes [#111](https://github.com/ba0gu0/Rem-Craft/issues/111)
* :bug: 优化标题图标样式 ([0f904d4](https://github.com/ba0gu0/Rem-Craft/commit/0f904d40d5e33257a92166fd7d7aea838483eab2))
* :bug: 优化模板选择弹窗样式 ([1c43ad3](https://github.com/ba0gu0/Rem-Craft/commit/1c43ad3034b95a545ee3eefb5a8257b52c70add5))
* :bug: 优化添加标签菜单无标签时的样式 ([cfdca70](https://github.com/ba0gu0/Rem-Craft/commit/cfdca70b934488e627bc36ebc2ecdbb6ff511c5f))
* :bug: 优化渲染块输入界面util的样式 ([69d480d](https://github.com/ba0gu0/Rem-Craft/commit/69d480dc43f3b0e25657b6d62e3817f4c9bd94ca))
* :bug: 优化滚动条颜色 ([15264be](https://github.com/ba0gu0/Rem-Craft/commit/15264beefb58697a6607e3edf3d747187f013249))
* :bug: 优化特殊超级块样式 ([a48f961](https://github.com/ba0gu0/Rem-Craft/commit/a48f9619d07a5df4f22554f89da6f58d311b6d3a))
* :bug: 优化状态栏样式 ([1929e56](https://github.com/ba0gu0/Rem-Craft/commit/1929e56d7747dfd50576276b5d7076f5f78fd846)), closes [#75](https://github.com/ba0gu0/Rem-Craft/issues/75)
* :bug: 优化状态栏菜单交互 ([b379384](https://github.com/ba0gu0/Rem-Craft/commit/b37938432011c49126e903e43298ac8ec0b25a91))
* :bug: 优化笔记本和反链面板样式 ([8a0a41b](https://github.com/ba0gu0/Rem-Craft/commit/8a0a41b5425340e15c88c69ab1b6c0a9cc147ba1))
* :bug: 优化编辑区域行内工具栏样式 ([2f99d76](https://github.com/ba0gu0/Rem-Craft/commit/2f99d76989713ab9f3585b7748f774ade92f7e88)), closes [#56](https://github.com/ba0gu0/Rem-Craft/issues/56)
* :bug: 优化行内mark样式 ([1e9fe2b](https://github.com/ba0gu0/Rem-Craft/commit/1e9fe2b9d6c9f9a87bb1125951ea5c9afff69b27))
* :bug: 优化行内图片拖拽按钮的样式 ([6c96206](https://github.com/ba0gu0/Rem-Craft/commit/6c96206462d91dd794af4bfea693dc17d289339c))
* :bug: 优化行内图片样式 ([7ddeea2](https://github.com/ba0gu0/Rem-Craft/commit/7ddeea2c322b8649f6a80b5a0102392f743306b4))
* :bug: 优化行级元素外观菜单的清除样式按钮 ([fa74f27](https://github.com/ba0gu0/Rem-Craft/commit/fa74f27aad3943bb1e080f5d140fb20ae42386da))
* :bug: 优化设置界面按钮样式 ([b77e0f8](https://github.com/ba0gu0/Rem-Craft/commit/b77e0f8b71a65ca2339e09ee55b4098afd471696))
* :bug: 优化账户未登录界面 ([6f0902d](https://github.com/ba0gu0/Rem-Craft/commit/6f0902de614969dd03cfb817d327a2b8a0c4f0b9))
* :bug: 优化超级块的内外边距，与其他块统一 ([7294670](https://github.com/ba0gu0/Rem-Craft/commit/7294670a2e0a97e4f527263b9f6f03e4854e0848))
* :bug: 优化超级块的样式 ([db1ad3b](https://github.com/ba0gu0/Rem-Craft/commit/db1ad3b1ce12e2385773221e8dd4cbca650dd528))
* :bug: 优化输入框和代码选择语言菜单的样式 ([9019abb](https://github.com/ba0gu0/Rem-Craft/commit/9019abbd1a8a1d08c431a914630ad91218b97fc2))
* :bug: 优化边栏动画 ([749c5bd](https://github.com/ba0gu0/Rem-Craft/commit/749c5bdfe9c0b3311fdaabdca1a08ff63c7715d8))
* :bug: 优化边窗样式 ([d46b1d3](https://github.com/ba0gu0/Rem-Craft/commit/d46b1d34f360f612d5f4ae5685f359c8079b5633))
* :bug: 优化选中文字底色，提高可读性 ([13f6e80](https://github.com/ba0gu0/Rem-Craft/commit/13f6e800b74f78f1be975faf732cc6b46bd2ef15)), closes [#66](https://github.com/ba0gu0/Rem-Craft/issues/66)
* :bug: 优化钉住图标的动画 ([89f1c19](https://github.com/ba0gu0/Rem-Craft/commit/89f1c199072d42765a2afb07085fd427434cf399))
* :bug: 优化闪卡卡组预览界面 ([582d359](https://github.com/ba0gu0/Rem-Craft/commit/582d35923c385571d45f456ea703d1542232e895))
* :bug: 优化闪卡页面样式 ([84131f9](https://github.com/ba0gu0/Rem-Craft/commit/84131f9540b795c9d31640e3c43ff90529eafd50)), closes [#97](https://github.com/ba0gu0/Rem-Craft/issues/97)
* :bug: 优化集市卡片样式 ([68d6376](https://github.com/ba0gu0/Rem-Craft/commit/68d6376b3fa8921bde1a03cee9685de7dbc045d6))
* :bug: 优化集市排序图标的位置 ([a20c60d](https://github.com/ba0gu0/Rem-Craft/commit/a20c60d157e8b17a7cb722a9b4609dbd0a08ccfe))
* :bug: 优化面包屑的间隔符号样式 ([a879445](https://github.com/ba0gu0/Rem-Craft/commit/a87944541892a8f4ba8040c06f56eb67a6b23875))
* :bug: 优化页签栏显示和拖拽的兼容逻辑 ([808131d](https://github.com/ba0gu0/Rem-Craft/commit/808131d173b065381b37e5c9867086bdc04dfd73))
* :bug: 优化页签样式 ([73a36ce](https://github.com/ba0gu0/Rem-Craft/commit/73a36ce83cf78132c591244db44d43e9cfcdb991))
* :bug: 优化页签钉住时的样式 ([f2068ed](https://github.com/ba0gu0/Rem-Craft/commit/f2068ed72043a4d9a66e1c0343503445bca5aec4))
* :bug: 优化顶栏、页签、边栏的样式 ([089a199](https://github.com/ba0gu0/Rem-Craft/commit/089a199143293e6b7e7397a6a46ae57d8b611490))
* :bug: 优化顶栏页签的一系列样式问题 ([52b58ee](https://github.com/ba0gu0/Rem-Craft/commit/52b58ee8ee2dc48e30215f5eb2e5b8c202a8ea1b))
* :bug: 优化题头emoji ([51b00b1](https://github.com/ba0gu0/Rem-Craft/commit/51b00b1f13582bc1c221fa6900bb2dafd3463888))
* :bug: 优化题头emoji和文档按钮的位置 ([f44a64a](https://github.com/ba0gu0/Rem-Craft/commit/f44a64a1dd5ac9985c9209636bc974e57c8570a6))
* :bug: 修复 docker 环境兼容问题 ([3090370](https://github.com/ba0gu0/Rem-Craft/commit/30903700ea075dbec84df7af41911cebb6770b6d)), closes [#104](https://github.com/ba0gu0/Rem-Craft/issues/104) [#117](https://github.com/ba0gu0/Rem-Craft/issues/117)
* :bug: 修复block-icon、snackbar的样式问题 ([4d8514e](https://github.com/ba0gu0/Rem-Craft/commit/4d8514e3b8525cd6e40a178ebea39d5e8b2ac58a))
* :bug: 修复block-icon样式问题 ([24b3147](https://github.com/ba0gu0/Rem-Craft/commit/24b31479d74d4a6550f21d4a7a2d062d1dd084b5))
* :bug: 修复block-icon的样式问题 ([d27b4eb](https://github.com/ba0gu0/Rem-Craft/commit/d27b4eb64e98eb3346701669eb92d3b6a66a7087))
* :bug: 修复button样式问题 ([68288ef](https://github.com/ba0gu0/Rem-Craft/commit/68288efd29b487f5a746d78371e45bfc6b4dbe6f))
* :bug: 修复code-block的样式问题 ([9b5c843](https://github.com/ba0gu0/Rem-Craft/commit/9b5c8433cda61bb18dfe37c85ed76c942bb7eeaa)), closes [#43](https://github.com/ba0gu0/Rem-Craft/issues/43)
* :bug: 修复color-square和font-style的样式问题 ([856c8e4](https://github.com/ba0gu0/Rem-Craft/commit/856c8e45e5553fcf7b752101545c281230a8db6d))
* :bug: 修复drag动画缓慢的问题 ([d65c672](https://github.com/ba0gu0/Rem-Craft/commit/d65c6723000b69ef482064f1d0cd8a66d74321de))
* :bug: 修复emojis面板的几个问题 ([ae842fb](https://github.com/ba0gu0/Rem-Craft/commit/ae842fb9cb3b6f6998d3f09ad0f9c1b604c21ed7))
* :bug: 修复emoji菜单样式 ([484eb44](https://github.com/ba0gu0/Rem-Craft/commit/484eb44e15be2dda099b6737c715260d4e151704)), closes [#115](https://github.com/ba0gu0/Rem-Craft/issues/115)
* :bug: 修复full-screen的样式问题 ([ce81691](https://github.com/ba0gu0/Rem-Craft/commit/ce81691e8ccdfa28fe267bc00f0c81f9e0e460c4))
* :bug: 修复linux环境下日历按钮的位置 ([c9ac24f](https://github.com/ba0gu0/Rem-Craft/commit/c9ac24f2c269799ebc1605143f96f24248b6a451))
* :bug: 修复list-block样式 ([1b0891d](https://github.com/ba0gu0/Rem-Craft/commit/1b0891dd9930fd748eff312f6e19c606d3703371))
* :bug: 修复list和tab-bar上按钮的颜色变化问题 ([90413c4](https://github.com/ba0gu0/Rem-Craft/commit/90413c49ec0eb517f74d1eefb15c9e06046c1c06))
* :bug: 修复list的高度问题 ([98178bd](https://github.com/ba0gu0/Rem-Craft/commit/98178bdb2b5d1ca822cb0da939419dd33e785abe))
* :bug: 修复mark标记块的样式 ([8832f5e](https://github.com/ba0gu0/Rem-Craft/commit/8832f5edc606ffeb885fccd4c60b7f0933d99562))
* :bug: 修复menu-item--custom样式 ([4a46a8b](https://github.com/ba0gu0/Rem-Craft/commit/4a46a8b86a3e92a5c4eb06d7f506a8b34a2c719f))
* :bug: 修复pdf导出页边距的问题 ([a512a83](https://github.com/ba0gu0/Rem-Craft/commit/a512a8366474179d5e2378674a95b121beacbfc2))
* :bug: 修复readme页面中代码块和行内代码的样式 ([6b0717c](https://github.com/ba0gu0/Rem-Craft/commit/6b0717c960cd4465e0c06e43b6c39de6eef3d9f9))
* :bug: 修复readme预览图打开时的圆角 ([c922cb7](https://github.com/ba0gu0/Rem-Craft/commit/c922cb76692e79c0bc65f0b05165832dcc117bba))
* :bug: 修复tab-bar的样式问题 ([60d420e](https://github.com/ba0gu0/Rem-Craft/commit/60d420e478bb732c57c78bef4af2faff8b6e611c))
* :bug: 修复utils问题 ([c6ee8ed](https://github.com/ba0gu0/Rem-Craft/commit/c6ee8ed54a7d3248bb3a2dc3a2699b5db5804090))
* :bug: 修复主题重载时的资源地址问题 ([8a3feac](https://github.com/ba0gu0/Rem-Craft/commit/8a3feac5ddae469e5f56fc391951962b5709eebe))
* :bug: 修复代码块菜单内的特殊开关样式 ([61b6a3c](https://github.com/ba0gu0/Rem-Craft/commit/61b6a3c8f4c845082d63d5b422eedc0385c68809))
* :bug: 修复代码块菜单透明度的问题 ([210d1f5](https://github.com/ba0gu0/Rem-Craft/commit/210d1f5818e1dafb2e61ba5c142912935bbb0e51))
* :bug: 修复代码片段弹窗关闭按钮样式 ([26f14c0](https://github.com/ba0gu0/Rem-Craft/commit/26f14c066deadc0199fbd3132b3d92a4b8b326ca))
* :bug: 修复信息块中的行内标签样式 ([4d156a3](https://github.com/ba0gu0/Rem-Craft/commit/4d156a30dd0c52a5576864c8423e65795a4236d9))
* :bug: 修复光标丢失的问题 ([6bb0503](https://github.com/ba0gu0/Rem-Craft/commit/6bb050305ecc9dfc737aa0655d84c452b556ef41)), closes [#88](https://github.com/ba0gu0/Rem-Craft/issues/88)
* :bug: 修复公式块的样式问题 ([0e5ede7](https://github.com/ba0gu0/Rem-Craft/commit/0e5ede734c8da76ace1d193831dd819803063a36)), closes [#27](https://github.com/ba0gu0/Rem-Craft/issues/27)
* :bug: 修复关系图全屏下的样式问题 ([dad97e0](https://github.com/ba0gu0/Rem-Craft/commit/dad97e0a917fbaca0746bce43ff208c976a6b5ef))
* :bug: 修复关系图无法全屏的问题 ([3acbd87](https://github.com/ba0gu0/Rem-Craft/commit/3acbd8792cf2680181990682fd795b4189f54bff)), closes [#113](https://github.com/ba0gu0/Rem-Craft/issues/113)
* :bug: 修复关闭按钮失效的问题 ([2513c3b](https://github.com/ba0gu0/Rem-Craft/commit/2513c3bf6d746e2b9c9a6472829213fd8d011cb8)), closes [#85](https://github.com/ba0gu0/Rem-Craft/issues/85)
* :bug: 修复关闭顶部页签后空白页的样式 ([8caded7](https://github.com/ba0gu0/Rem-Craft/commit/8caded7837b785cc0c28ebab9f896045bbacd7b5))
* :bug: 修复分屏时的bug ([18d1ee7](https://github.com/ba0gu0/Rem-Craft/commit/18d1ee7f2da752d27a60608d4e7f036eac5e68a0))
* :bug: 修复分屏时顶部页签栏的拖拽问题 ([bf1e99b](https://github.com/ba0gu0/Rem-Craft/commit/bf1e99b8b407f6682355914e777aa54737337224))
* :bug: 修复列表块内标题块的样式 ([b722e81](https://github.com/ba0gu0/Rem-Craft/commit/b722e81878e24f145a19c4b939380bc20527d447))
* :bug: 修复列表块按钮和辅助线的显示问题 ([03a9b37](https://github.com/ba0gu0/Rem-Craft/commit/03a9b3766bfc9e6bc3b84956b2588bdf2ce0af5c))
* :bug: 修复列表块的宽度显示问题 ([4e044c2](https://github.com/ba0gu0/Rem-Craft/commit/4e044c22d4b51a60dbe2a5618a6b8398ad8c4925))
* :bug: 修复列表嵌套引述块的样式问题 ([626a384](https://github.com/ba0gu0/Rem-Craft/commit/626a384ad2e6fa645d5bad370059e678541c5b93))
* :bug: 修复列表嵌套标题块时辅助线的样式问题 ([e3906af](https://github.com/ba0gu0/Rem-Craft/commit/e3906af280bc6862e92e82e18172d4fbaa431042))
* :bug: 修复反链展开后图标位置错误的问题 ([a985d27](https://github.com/ba0gu0/Rem-Craft/commit/a985d27d086df9c892b32c2447d6d3c8573b2702))
* :bug: 修复反链界面的字体大小问题 ([3aab0cd](https://github.com/ba0gu0/Rem-Craft/commit/3aab0cdf1533ccb1a5697ae2b662088faeab1a89))
* :bug: 修复反链面板样式问题 ([828c546](https://github.com/ba0gu0/Rem-Craft/commit/828c546725da9f221f255b9337fd09d140f9adfb)), closes [#100](https://github.com/ba0gu0/Rem-Craft/issues/100)
* :bug: 修复右侧边栏被底栏遮挡的问题 ([763a58f](https://github.com/ba0gu0/Rem-Craft/commit/763a58fb63fc849d98548b251704d9806c54be0b)), closes [#121](https://github.com/ba0gu0/Rem-Craft/issues/121)
* :bug: 修复图片浏览界面缩放文字颜色 ([3502772](https://github.com/ba0gu0/Rem-Craft/commit/35027727e5e2b1bc96210acb8d1ba19847289e14))
* :bug: 修复块元信息导出显示样式 ([f24a302](https://github.com/ba0gu0/Rem-Craft/commit/f24a3023a53f76696ae346418e5ab65965264336))
* :bug: 修复块引用菜单输入框的样式问题 ([8218bc7](https://github.com/ba0gu0/Rem-Craft/commit/8218bc77905c45e8fefd6e9fdc89a29f3cedc62e))
* :bug: 修复块滚动条的样式问题 ([8c3c603](https://github.com/ba0gu0/Rem-Craft/commit/8c3c60378aa7cb907a0b2a9870540624f5954c8e)), closes [#73](https://github.com/ba0gu0/Rem-Craft/issues/73)
* :bug: 修复块菜单样式 ([8a8e6be](https://github.com/ba0gu0/Rem-Craft/commit/8a8e6be488325eede2b6942e348fcc35e63b37c7))
* :bug: 修复备注样式问题 ([37aad9f](https://github.com/ba0gu0/Rem-Craft/commit/37aad9f190e9ff7ada8167540c1e810f7c933acf))
* :bug: 修复大纲界面标题图标样式问题 ([1b45c4f](https://github.com/ba0gu0/Rem-Craft/commit/1b45c4f81ffc079d92371ea5571f336ca0719058))
* :bug: 修复大纲界面标题样式问题 ([46f7b00](https://github.com/ba0gu0/Rem-Craft/commit/46f7b0083b59428bc90f83312687605a878de1be))
* :bug: 修复子弹流与引用块的冲突问题 ([5f533b0](https://github.com/ba0gu0/Rem-Craft/commit/5f533b0e08841014673b859b9a05262420da0a1e))
* :bug: 修复子弹流样式问题 ([b7688ba](https://github.com/ba0gu0/Rem-Craft/commit/b7688ba62feff2c2fdefc01110db8a543fa6a31e))
* :bug: 修复子弹流的样式问题 ([b113f62](https://github.com/ba0gu0/Rem-Craft/commit/b113f62632c688385d8aa81b9100bd03054bb2b6))
* :bug: 修复导出预览界面脚注样式问题 ([d140973](https://github.com/ba0gu0/Rem-Craft/commit/d14097317ded144dbdefc80a32587ce616c3003c))
* :bug: 修复属性弹窗书签按钮图标居中问题 ([5af5a6b](https://github.com/ba0gu0/Rem-Craft/commit/5af5a6bc8708e1a84bdd6fd6f3efbdbcec3de661))
* :bug: 修复属性弹窗的样式 ([ddbb061](https://github.com/ba0gu0/Rem-Craft/commit/ddbb061ecfbd5fa0e94dc18ba36c295d181cd89a))
* :bug: 修复左侧边栏关闭时的样式缺陷 ([170f5ec](https://github.com/ba0gu0/Rem-Craft/commit/170f5ec981c2cd2feeb999009729bf4aa717251b))
* :bug: 修复并优化底部状态栏 ([cb08730](https://github.com/ba0gu0/Rem-Craft/commit/cb0873031ac6a27bc56e49270b7ca23483412e8d))
* :bug: 修复引号字体的问题 ([6023b8b](https://github.com/ba0gu0/Rem-Craft/commit/6023b8bd6b5b6e13867f634a166d727d40721e8e))
* :bug: 修复引述块嵌套表格块的问题 ([9b26ed2](https://github.com/ba0gu0/Rem-Craft/commit/9b26ed2acf0336275857b9e8d7efa48eb2f0ee49))
* :bug: 修复引述块折叠后的样式 ([9d3e853](https://github.com/ba0gu0/Rem-Craft/commit/9d3e853267a50536d3ee0815582b857d5f3bf58f))
* :bug: 修复引述块的样式问题 ([2ca2175](https://github.com/ba0gu0/Rem-Craft/commit/2ca21751ba579079c3295727d4f4b60a5e14a18a)), closes [#26](https://github.com/ba0gu0/Rem-Craft/issues/26)
* :bug: 修复弹窗按钮和右边栏的冲突问题 ([1b0e6e1](https://github.com/ba0gu0/Rem-Craft/commit/1b0e6e18680cd28d4867cb4f5d3c27d51e068e59)), closes [#95](https://github.com/ba0gu0/Rem-Craft/issues/95)
* :bug: 修复快捷菜单出现在屏幕右侧时的宽度问题 ([8449b94](https://github.com/ba0gu0/Rem-Craft/commit/8449b947a8c4b7660de55751e7e0f08cef0b928e))
* :bug: 修复快捷键设置界面样式问题 ([8a9e69f](https://github.com/ba0gu0/Rem-Craft/commit/8a9e69ff6e36fe2880b798624a0f9c7510c1b34a))
* :bug: 修复快捷键设置菜单样式 ([0e4ce9e](https://github.com/ba0gu0/Rem-Craft/commit/0e4ce9edf63a5a3432c905b73454bb9f38c3c693))
* :bug: 修复快捷键设置面板样式问题 ([fec4cd9](https://github.com/ba0gu0/Rem-Craft/commit/fec4cd94d24ccac4f5e5a84043ccbeb7a0fb78c6))
* :bug: 修复悬浮窗内块滚动条的样式 ([e8fdedb](https://github.com/ba0gu0/Rem-Craft/commit/e8fdedbe00d5081586d865b0474f49116a98a844))
* :bug: 修复按钮focus状态的底色 ([f720f34](https://github.com/ba0gu0/Rem-Craft/commit/f720f34bb622923f24d50aaf2b65c251740cc51d))
* :bug: 修复搜索列表emoji的问题 ([76ad2b4](https://github.com/ba0gu0/Rem-Craft/commit/76ad2b4f047bd950aaa5a7dc1bafb91bd3a15f8d))
* :bug: 修复搜索弹窗圆角 ([7f26bc9](https://github.com/ba0gu0/Rem-Craft/commit/7f26bc92bbc93f90ba12d0fe9f93bdf830909baf))
* :bug: 修复搜索界面右下角圆角 ([44522a4](https://github.com/ba0gu0/Rem-Craft/commit/44522a4ce63f0776bae4cefdec2214367c869940))
* :bug: 修复搜索界面结果展示的底部空白问题 ([5bdbb06](https://github.com/ba0gu0/Rem-Craft/commit/5bdbb066d79e6c176208f2d709e1759f6d62dbe4))
* :bug: 修复搜索结果为空时的样式问题 ([e3ce22c](https://github.com/ba0gu0/Rem-Craft/commit/e3ce22c1761b96d726f80a498d29d91ee9e16201))
* :bug: 修复搜索结果列表样式问题 ([472612f](https://github.com/ba0gu0/Rem-Craft/commit/472612fa99d3348c7bcce390bb53a0a6aa92a31a))
* :bug: 修复数据历史界面的样式问题 ([fce0a05](https://github.com/ba0gu0/Rem-Craft/commit/fce0a0546d7f1f1a6545b61c8b1022e86b35b835))
* :bug: 修复数据历史菜单样式 ([af515b9](https://github.com/ba0gu0/Rem-Craft/commit/af515b94a0d141ff21a627c3ec67a7269181fbb4))
* :bug: 修复数据快照界面显示问题 ([b7fe58c](https://github.com/ba0gu0/Rem-Craft/commit/b7fe58ca3b54e0a3cd8b647bfffbdc5cfda5b54f))
* :bug: 修复文件图标无法显示的问题 ([1cd944e](https://github.com/ba0gu0/Rem-Craft/commit/1cd944e4abd66517d5498556e4b6742bf4cd8923)), closes [#70](https://github.com/ba0gu0/Rem-Craft/issues/70)
* :bug: 修复文件图标无法显示的问题 ([635bc34](https://github.com/ba0gu0/Rem-Craft/commit/635bc345753a2696d2dce5ce0c899ea82ecbcaf2)), closes [#70](https://github.com/ba0gu0/Rem-Craft/issues/70)
* :bug: 修复文档树开启卡顿的问题 ([d2c0e98](https://github.com/ba0gu0/Rem-Craft/commit/d2c0e9887b6178257172dc687b597806a569f65e))
* :bug: 修复新版menu兼容问题 ([fc71f48](https://github.com/ba0gu0/Rem-Craft/commit/fc71f48b27fc14495de73d927058023398302377))
* :bug: 修复新版readme界面样式 ([00d9a30](https://github.com/ba0gu0/Rem-Craft/commit/00d9a30c657cee9ffae9215b1eeaf980261819f1))
* :bug: 修复新版状态栏导致的问题 ([8eacca0](https://github.com/ba0gu0/Rem-Craft/commit/8eacca00a4ee1e0287e1c137ccdfa7ebff44e25a))
* :bug: 修复新版状态栏引起的样式问题 ([84b3923](https://github.com/ba0gu0/Rem-Craft/commit/84b3923617d150bcd4d27481b3df5348b29fd891))
* :bug: 修复新窗口标签页的样式问题 ([6919037](https://github.com/ba0gu0/Rem-Craft/commit/6919037e831ec9e1736d937585199e3a042c0897))
* :bug: 修复日历挂件新建日记重复问题 ([94c7673](https://github.com/ba0gu0/Rem-Craft/commit/94c767313c2926fd9df53c43f8ebaf095a61f9a8))
* :bug: 修复暗黑模式下.block__logo的颜色问题 ([905ab85](https://github.com/ba0gu0/Rem-Craft/commit/905ab850e3ea1b5eaadd16a212f62a631459231e))
* :bug: 修复暗黑模式下list-meta的颜色显示问题 ([f49a283](https://github.com/ba0gu0/Rem-Craft/commit/f49a28360191240410073173c04d6cdcf3ce1fd3))
* :bug: 修复暗黑模式下日历的颜色问题 ([83cfc18](https://github.com/ba0gu0/Rem-Craft/commit/83cfc18da32152bc0b04b194712d614864ccfa04))
* :bug: 修复暗黑模式下的代码块样式问题 ([a8b71c4](https://github.com/ba0gu0/Rem-Craft/commit/a8b71c46f0a1659b81b78564bf0c3134d8b21cc4))
* :bug: 修复暗黑模式下的变量命名问题 ([2935f72](https://github.com/ba0gu0/Rem-Craft/commit/2935f72c32e105146871575270a75834efda0816))
* :bug: 修复暗黑模式下选中底色问题 ([2fd81d1](https://github.com/ba0gu0/Rem-Craft/commit/2fd81d1a17fcb1c740693b0f7e1112becdabcf2f)), closes [#96](https://github.com/ba0gu0/Rem-Craft/issues/96)
* :bug: 修复暗黑模式的日历插件颜色问题 ([dae323a](https://github.com/ba0gu0/Rem-Craft/commit/dae323a9d0138a9eb3397c6a5c015840742c3d51))
* :bug: 修复暗黑模式的菜单项显示问题 ([78e8315](https://github.com/ba0gu0/Rem-Craft/commit/78e8315f9298d39d78744f19b6147032cdf61d06))
* :bug: 修复替换弹窗的样式问题，并优化搜索结果列表 ([0399a14](https://github.com/ba0gu0/Rem-Craft/commit/0399a142d5752ea52d33e35b58c212868e6e993c)), closes [#76](https://github.com/ba0gu0/Rem-Craft/issues/76)
* :bug: 修复替换界面的高度显示问题 ([1d5929b](https://github.com/ba0gu0/Rem-Craft/commit/1d5929b6e26ec42d13b0aeb3053afbffaa4430b0))
* :bug: 修复标签页下拉菜单样式问题 ([5ec54a4](https://github.com/ba0gu0/Rem-Craft/commit/5ec54a40f5b3ba5b106a3f873906a6bddc93d68d))
* :bug: 修复标题为空时大纲界面显示的bug ([5959505](https://github.com/ba0gu0/Rem-Craft/commit/5959505a46dde2c18f7f3fb055ad17cf44c6e0b9))
* :bug: 修复段间距的问题 ([f5d468a](https://github.com/ba0gu0/Rem-Craft/commit/f5d468a370c0f952c630650d9678566f7e710508))
* :bug: 修复滑动条位置问题 ([086faa4](https://github.com/ba0gu0/Rem-Craft/commit/086faa4c52d30626691e71b7239dfeb7de33e662))
* :bug: 修复特殊超级块内代码块的样式 ([7f3ea2c](https://github.com/ba0gu0/Rem-Craft/commit/7f3ea2c1035b28da2437adc1fbf4aca56fe7369b))
* :bug: 修复状态栏的显示问题 ([7795975](https://github.com/ba0gu0/Rem-Craft/commit/77959752068f74b3c0c46d1ebcc3d20ba3e3f4a4))
* :bug: 修复状态栏遮挡问题 ([937f9f3](https://github.com/ba0gu0/Rem-Craft/commit/937f9f3964dcaa36d0bc40008a276cac6a1b0c4d)), closes [#59](https://github.com/ba0gu0/Rem-Craft/issues/59)
* :bug: 修复视频菜单资源栏输入框的长度问题 ([570ed75](https://github.com/ba0gu0/Rem-Craft/commit/570ed75759b670d5557e1ebc7c7ca15003c40937))
* :bug: 修复窗口失焦时页签文字颜色的问题 ([1622f57](https://github.com/ba0gu0/Rem-Craft/commit/1622f57b549df35f0d5d3059ab0349b68a558253))
* :bug: 修复编辑区域窄宽度显示横向滚动条的问题 ([564e945](https://github.com/ba0gu0/Rem-Craft/commit/564e9453fedf43b66e56584e013e6e1423ac4da6))
* :bug: 修复编辑区域被标题影响宽度的问题 ([bce70a3](https://github.com/ba0gu0/Rem-Craft/commit/bce70a3c43fbdd134c319a997f635cce7c8803a3))
* :bug: 修复编辑区域页面抖动的问题 ([ea97f01](https://github.com/ba0gu0/Rem-Craft/commit/ea97f01cbfbbc3bc50e0383bc762270d3e3556ff))
* :bug: 修复菜单read-only的样式 ([4614df9](https://github.com/ba0gu0/Rem-Craft/commit/4614df9570ebcdc52f3a049a936e8b78e4251070))
* :bug: 修复菜单项位于顶栏位置时无法点击的问题 ([5c02a1e](https://github.com/ba0gu0/Rem-Craft/commit/5c02a1e1f70afdfa7a723b17e5f290b6384c08ab))
* :bug: 修复菜单项的文本颜色 ([2bc2fcc](https://github.com/ba0gu0/Rem-Craft/commit/2bc2fccc70bd68fb54f310eae01550c1efd2ac60))
* :bug: 修复行内标签块换行问题 ([9de8d64](https://github.com/ba0gu0/Rem-Craft/commit/9de8d64dd1ae48600f23a65d41979f73c5f2c6e4)), closes [#60](https://github.com/ba0gu0/Rem-Craft/issues/60)
* :bug: 修复行内评论 ([4e326af](https://github.com/ba0gu0/Rem-Craft/commit/4e326afaf73658a7f9ae49a077f72889144b6bf8)), closes [#86](https://github.com/ba0gu0/Rem-Craft/issues/86)
* :bug: 修复行内超链接的样式问题 ([49d42f3](https://github.com/ba0gu0/Rem-Craft/commit/49d42f32a18a9bcfe35de3795bf72fece5ebc496))
* :bug: 修复表格块的线条显示问题 ([0c36ab4](https://github.com/ba0gu0/Rem-Craft/commit/0c36ab48dd90753efe91fc9cc7c91f85699b100f))
* :bug: 修复设置界面边栏列表的样式 ([680fc29](https://github.com/ba0gu0/Rem-Craft/commit/680fc29285502701ecf0a30be3852bbdb2949bd9))
* :bug: 修复设置菜单样式问题 ([7657d8a](https://github.com/ba0gu0/Rem-Craft/commit/7657d8ae049889a4bc32db95392b9eaf41fabb36)), closes [#99](https://github.com/ba0gu0/Rem-Craft/issues/99)
* :bug: 修复设置菜单相关样式 ([a232156](https://github.com/ba0gu0/Rem-Craft/commit/a232156b82881d822a516627d116fe729fbf69ab))
* :bug: 修复账号界面的部分显示问题 ([b7aaa4a](https://github.com/ba0gu0/Rem-Craft/commit/b7aaa4ac6f14cc21ba0fbb2f1fd87d9712860b03))
* :bug: 修复账号登陆弹窗的圆角问题 ([9e3783b](https://github.com/ba0gu0/Rem-Craft/commit/9e3783b47a240b65fb001d6ef782608aadf5984c))
* :bug: 修复超级块内各类块的内边距问题 ([ce4f3d1](https://github.com/ba0gu0/Rem-Craft/commit/ce4f3d121bca1cd8f9e0e75018cfc91b2ca03846))
* :bug: 修复超链接中行内代码块的样式 ([c7bfd39](https://github.com/ba0gu0/Rem-Craft/commit/c7bfd39868e9baeb8911c989dfecca271d9c5952))
* :bug: 修复超链接及上标导出样式 ([da4dd82](https://github.com/ba0gu0/Rem-Craft/commit/da4dd82157780a1a7e4bfa7a8fd1dc3e361f430c))
* :bug: 修复超链接图标的问题 ([8612bc7](https://github.com/ba0gu0/Rem-Craft/commit/8612bc72d2a84b59d87572ff5e2a8f31e734787e))
* :bug: 修复输入框样式无法查看的问题 ([94973b2](https://github.com/ba0gu0/Rem-Craft/commit/94973b2242b63409e53b4345b87e803e275b3d82))
* :bug: 修复输入框行高 ([7826f52](https://github.com/ba0gu0/Rem-Craft/commit/7826f526a29e7e8ee893252fe195a85037fb22b3))
* :bug: 修复边栏动画卡顿问题 ([3fedf12](https://github.com/ba0gu0/Rem-Craft/commit/3fedf122346a9a3cfe8c362dc499a4aab0076441))
* :bug: 修复边窗动画效果不匹配的问题 ([80ebca3](https://github.com/ba0gu0/Rem-Craft/commit/80ebca304d04208a2ba437c4f38ec5e881ba59fe))
* :bug: 修复部分emoji显示错误的问题 ([7fc38b8](https://github.com/ba0gu0/Rem-Craft/commit/7fc38b895dc47a1771e4972b66f14b7bb0882983))
* :bug: 修复钉住页签和未打开文档的空界面样式 ([4aeaa9a](https://github.com/ba0gu0/Rem-Craft/commit/4aeaa9a3169b652a5cf884dc52c907fd8a2c9d25))
* :bug: 修复钉住页签的图标样式 ([a7eb409](https://github.com/ba0gu0/Rem-Craft/commit/a7eb409651eaaef6886c15b3c5c0d89d4ee39d4c))
* :bug: 修复钉住页签的样式问题 ([53b90bd](https://github.com/ba0gu0/Rem-Craft/commit/53b90bdb5f7e241dc46553fdeba885bc01a7d853))
* :bug: 修复链接图标显示问题 ([544b6b0](https://github.com/ba0gu0/Rem-Craft/commit/544b6b009aa4ba0b9b8023d1c7021b69271d6262)), closes [#84](https://github.com/ba0gu0/Rem-Craft/issues/84)
* :bug: 修复闪卡使用和管理界面样式 ([71811df](https://github.com/ba0gu0/Rem-Craft/commit/71811df875126c4b33f3bfd78acfad3327ae2ccb))
* :bug: 修复集市tab宽度问题 ([b0872d4](https://github.com/ba0gu0/Rem-Craft/commit/b0872d4f0c7658791eeae0a6a7b1d7f73e708c57))
* :bug: 修复集市卡片按钮样式问题 ([9d76fb5](https://github.com/ba0gu0/Rem-Craft/commit/9d76fb57b201b8cd94cc8591fc0569339f7d5966))
* :bug: 修复集市卡片的样式 ([dfb6564](https://github.com/ba0gu0/Rem-Craft/commit/dfb65641a16edbc88e7bff94bb8c2fe320655e23))
* :bug: 修复面包屑和页签栏的几个小问题 ([d0d14f3](https://github.com/ba0gu0/Rem-Craft/commit/d0d14f3dc62e738e621b5aef276d83da052fccb8))
* :bug: 修复页签栏关闭动画卡顿问题 ([e70a953](https://github.com/ba0gu0/Rem-Craft/commit/e70a953b865c0b478975810002f056295c8615c6))
* :bug: 修复页签栏样式问题 ([2a1a4a1](https://github.com/ba0gu0/Rem-Craft/commit/2a1a4a17d0b5e1a4f665d8319231445fafbe4a19))
* :bug: 修复页签栏滚动时，顶栏无法拖拽窗口的问题 ([bb166ad](https://github.com/ba0gu0/Rem-Craft/commit/bb166ad4fadf2b656f155a31ede702c8b0033fac))
* :bug: 修复页签间隔线未能正常显示的问题 ([d9601b1](https://github.com/ba0gu0/Rem-Craft/commit/d9601b120d2b9bbd94396750bf5fc28b9d63a0a8))
* :bug: 修复顶栏拖拽，和兼容mac顶栏 ([b80c490](https://github.com/ba0gu0/Rem-Craft/commit/b80c4901c9fbac6374bbb2bba5e100850ccf5ded))
* :bug: 修复顶栏按钮悬浮样式 ([bfa9fc8](https://github.com/ba0gu0/Rem-Craft/commit/bfa9fc8685ecfaefaaa32504e6d98ab0382a3975))
* :bug: 修复顶栏页签问题 ([d971383](https://github.com/ba0gu0/Rem-Craft/commit/d971383f1efacf38abe07d16c63a86ed64ebf2c5))
* :bug: 修复顶部页签栏的边距问题 ([65ed8b0](https://github.com/ba0gu0/Rem-Craft/commit/65ed8b05cb7f4250735f00dd3d8687e9d74e02cf))
* :bug: 修复题头图使用:has导致的卡顿问题 ([abe83c5](https://github.com/ba0gu0/Rem-Craft/commit/abe83c5c14e2569d1502d3061fb000f4bdd233b0))
* :bug: 修复题头图按钮位置问题 ([fa89c4a](https://github.com/ba0gu0/Rem-Craft/commit/fa89c4a236596ceb4d20736fe1632faedefef88c)), closes [#132](https://github.com/ba0gu0/Rem-Craft/issues/132)
* :bug: 修复题头图标按钮组的样式问题 ([b570e9a](https://github.com/ba0gu0/Rem-Craft/commit/b570e9abd2a6c24937048f22c77927a6c0a15bcb))
* :bug: 修复题头图标签的hover样式 ([2ed9be5](https://github.com/ba0gu0/Rem-Craft/commit/2ed9be563150b9b32049fc05d66fcd6d60623638))
* :bug: 修复鼠标拖拽框的样式 ([8fa4f7f](https://github.com/ba0gu0/Rem-Craft/commit/8fa4f7fc7e80b7c87e0371a42e484b4ec76d88bf))
* :bug: 修改mark标记样式 ([1d58ce0](https://github.com/ba0gu0/Rem-Craft/commit/1d58ce02e5f842ee2c6fe8178bfd519d862bb6ac))
* :bug: 修改wnd圆角 ([9ea4339](https://github.com/ba0gu0/Rem-Craft/commit/9ea43397bb5d181a9d36bb515ce2e5d1d4439c3c))
* :bug: 修改块嵌入的样式 ([5f3dcba](https://github.com/ba0gu0/Rem-Craft/commit/5f3dcbadf315c122da5ff5d088b206c6c004e13d))
* :bug: 修改监听并去除部分:has ([7c51e57](https://github.com/ba0gu0/Rem-Craft/commit/7c51e57c58c38131b4f1ab721375637e6de0597b)), closes [#82](https://github.com/ba0gu0/Rem-Craft/issues/82) [#109](https://github.com/ba0gu0/Rem-Craft/issues/109)
* :bug: 修改菜单项样式 ([c0ccd4d](https://github.com/ba0gu0/Rem-Craft/commit/c0ccd4dd6a088511eafff77676913f401ffa3d88))
* :bug: 修改辅助条圆角 ([c5183bc](https://github.com/ba0gu0/Rem-Craft/commit/c5183bc112cbe878948e61e564d56cd4ba6d7390))
* :bug: 修改边栏按钮聚焦条的圆角 ([3ca4a85](https://github.com/ba0gu0/Rem-Craft/commit/3ca4a8588093f12f4f54d14ce05117f4996743b6))
* :bug: 修改边栏样式，使得可拖拽窗口 ([bdd041c](https://github.com/ba0gu0/Rem-Craft/commit/bdd041c6289be3371ce6b87cb01d1069a81fb8fd))
* :bug: 兼容2.4.1的外观更新 ([0d4a816](https://github.com/ba0gu0/Rem-Craft/commit/0d4a8161584a2c0b90e4cfb21448fba76e2583f2))
* :bug: 兼容最新版数据历史弹窗样式 ([7e35e1e](https://github.com/ba0gu0/Rem-Craft/commit/7e35e1e1ff3487f17d555cded4e86d1ae6c69aa0))
* :bug: 兼容最新版的pdf导出弹窗 ([b6368d8](https://github.com/ba0gu0/Rem-Craft/commit/b6368d88fedef1ac1102f8a7ecc40ee59eae1d90))
* :bug: 兼容思源 2.7.7 ([238f600](https://github.com/ba0gu0/Rem-Craft/commit/238f600fb8c57b04abd5d6482f77c2df95fb58ce))
* :bug: 兼容思源2.2.0行内元素的更新 ([72e13e6](https://github.com/ba0gu0/Rem-Craft/commit/72e13e6f8080cbb0ad0c91b344a42e64014dab33))
* :bug: 兼容思源2.7.0正式版 ([631b9a0](https://github.com/ba0gu0/Rem-Craft/commit/631b9a079bf6f2bddf9f254795c3e67e07d865b6))
* :bug: 兼容思源2.7.1 ([bde8953](https://github.com/ba0gu0/Rem-Craft/commit/bde895333f0f7c1ac662a6b983e8100cc9267845))
* :bug: 兼容思源2.7.2 ([128faf8](https://github.com/ba0gu0/Rem-Craft/commit/128faf84437e299dd651b1fcbc1a2f11c139d790))
* :bug: 兼容思源v2.8.7新集市样式 ([ae1318b](https://github.com/ba0gu0/Rem-Craft/commit/ae1318bffc6b0e6be27c38d45f6d70564a8e7c72))
* :bug: 兼容思源新版输入框和选择器样式 ([6856f41](https://github.com/ba0gu0/Rem-Craft/commit/6856f417fe85ee0c71efb8e1f46606ebca8f075e)), closes [#118](https://github.com/ba0gu0/Rem-Craft/issues/118)
* :bug: 兼容悬浮边栏 ([706cbea](https://github.com/ba0gu0/Rem-Craft/commit/706cbeae87bc94b593a7ebcb400f23d1a69f964f))
* :bug: 兼容新版.b3-list--border类选择器 ([6bd64f4](https://github.com/ba0gu0/Rem-Craft/commit/6bd64f4404907bfd55511943d4e317ce753fcb21))
* :bug: 兼容新版全屏拖拽，减少代码 ([f6f8a4a](https://github.com/ba0gu0/Rem-Craft/commit/f6f8a4a645f30590e8e79535b2d2fe007e22dcd2))
* :bug: 兼容新版列表块辅助线 ([dbf9303](https://github.com/ba0gu0/Rem-Craft/commit/dbf930354af65b040e75b6b11aedc37afe593e5f))
* :bug: 兼容新版反链面板 ([489aa3a](https://github.com/ba0gu0/Rem-Craft/commit/489aa3a8da72de820159b4c7fbc6913856ad7f67))
* :bug: 兼容新版底部状态栏 ([6db6ee7](https://github.com/ba0gu0/Rem-Craft/commit/6db6ee77bfbd5b7cf3314132405d460e1fe3cbdd))
* :bug: 兼容新版搜索界面 ([6280741](https://github.com/ba0gu0/Rem-Craft/commit/6280741063db3c693a403035eb43799c8eda198a))
* :bug: 兼容新版明暗切换 ([60ce82f](https://github.com/ba0gu0/Rem-Craft/commit/60ce82f39199a9be4ba0ed9ea4e632d57bbe4928))
* :bug: 兼容新版设置界面 ([7f7d465](https://github.com/ba0gu0/Rem-Craft/commit/7f7d465d140513aa69ef135703e8e433c8d33d2c))
* :bug: 兼容新版集市card样式 ([bfdf9b1](https://github.com/ba0gu0/Rem-Craft/commit/bfdf9b1a99b199a43f3ebf9647eb83a43b56b355))
* :bug: 兼容新版集市已下载tab按钮 ([bcf11b8](https://github.com/ba0gu0/Rem-Craft/commit/bcf11b8fd4041755f623ca4a2d6d0eeca5d56a65))
* :bug: 兼容新版页签栏 ([52cce7e](https://github.com/ba0gu0/Rem-Craft/commit/52cce7e6a8bc7f525628ce455a02463cfb9af900))
* :bug: 兼容新版页签栏按钮 ([e6f3d49](https://github.com/ba0gu0/Rem-Craft/commit/e6f3d497c88c30df6d3ad7fe23914f5ad16fa94e))
* :bug: 兼容新版顶栏 ([eca2ab8](https://github.com/ba0gu0/Rem-Craft/commit/eca2ab8567d3066f1e9932d2d125d89e4f1e9db2))
* :bug: 兼容新版顶栏 ([b263227](https://github.com/ba0gu0/Rem-Craft/commit/b263227b7a6e7bbe6f832c32276b416d1f93f94c))
* :bug: 兼容新的官方css变量 ([8305cc6](https://github.com/ba0gu0/Rem-Craft/commit/8305cc6852d51666a309477ebf577adcfa2ae4c9))
* :bug: 兼容新窗口顶部的钉住按钮 ([a1ae40d](https://github.com/ba0gu0/Rem-Craft/commit/a1ae40d1f1d04ffee634b342a738697bc9b262c0))
* :bug: 兼容自适应宽度功能 ([f4064db](https://github.com/ba0gu0/Rem-Craft/commit/f4064db9367c352a1e2a4e21fa1fce1678b2d9b2)), closes [#20](https://github.com/ba0gu0/Rem-Craft/issues/20)
* :bug: 兼容部分官方css变量 ([5388fe8](https://github.com/ba0gu0/Rem-Craft/commit/5388fe8a8cc710e9ba75162dac8ca51ba0d1a814))
* :bug: 减小编辑器内一级各类块的两侧内边距，优化阅读 ([d1d3b3a](https://github.com/ba0gu0/Rem-Craft/commit/d1d3b3a8712464c78c2a2089f1d91f60a5c4b2d7))
* :bug: 减少list-item的间距 ([a71e463](https://github.com/ba0gu0/Rem-Craft/commit/a71e463e711a44f0db118b61d1c377fd9fdc07d9)), closes [#62](https://github.com/ba0gu0/Rem-Craft/issues/62)
* :bug: 初步兼容2.7.0 ([e0d11e7](https://github.com/ba0gu0/Rem-Craft/commit/e0d11e749a7bad8a67bcf6ce50ad53aa6f9b1d87))
* :bug: 删除.img-select选择器 ([1525f0f](https://github.com/ba0gu0/Rem-Craft/commit/1525f0f023d3046506e757fa14048ed39d427b84))
* :bug: 删除不复用的mixin ([bc8a2bb](https://github.com/ba0gu0/Rem-Craft/commit/bc8a2bb16d50f835a4903b392aa06c0a28358de9))
* :bug: 删除了主题自带的日历功能，并适配了日历插件 ([672050b](https://github.com/ba0gu0/Rem-Craft/commit/672050b46750af9ade4d3137840b75595276ced3))
* :bug: 利用:has优化搜索等弹窗宽度 ([f275172](https://github.com/ba0gu0/Rem-Craft/commit/f275172d3c75b0f076734ccd0e8bacfd79aed586))
* :bug: 利用:has优化题头图样式代码 ([4da6017](https://github.com/ba0gu0/Rem-Craft/commit/4da601767ed86440dd233d7081f95f2efc81b03a))
* :bug: 去除新版readme界面中预览图的下外边距 ([040b92a](https://github.com/ba0gu0/Rem-Craft/commit/040b92af0a8554618dcb4be847c766b00971e08d))
* :bug: 增加Alt+B反链面板底部内边距 ([a50e055](https://github.com/ba0gu0/Rem-Craft/commit/a50e0554229f86bad9e36a15e50eb00311c0c2f4)), closes [#90](https://github.com/ba0gu0/Rem-Craft/issues/90)
* :bug: 增加移动端判断 ([789d8b7](https://github.com/ba0gu0/Rem-Craft/commit/789d8b75e1c7ceeacfa74f5bb0c7d76709a0fb04)), closes [#98](https://github.com/ba0gu0/Rem-Craft/issues/98)
* :bug: 增加顶栏监听 ([dafcf1d](https://github.com/ba0gu0/Rem-Craft/commit/dafcf1d8973b24f93f68419d697f431f3efcc0f9))
* :bug: 大纲辅助线鼠标移入块高亮 ([cf190e7](https://github.com/ba0gu0/Rem-Craft/commit/cf190e736fc918afc439771fead7b1a500b2a892)), closes [#33](https://github.com/ba0gu0/Rem-Craft/issues/33)
* :bug: 将状态栏换到左下角 ([18f1a6e](https://github.com/ba0gu0/Rem-Craft/commit/18f1a6ec79c18a0e0ea1c33619d5f94d3627fdd4))
* :bug: 将表格改成不换行 ([2698ee4](https://github.com/ba0gu0/Rem-Craft/commit/2698ee4a2956fdbef2d1ccec40954c0290a55ed7)), closes [#114](https://github.com/ba0gu0/Rem-Craft/issues/114)
* :bug: 左上角 logo 跟随边栏自动变化 ([8244392](https://github.com/ba0gu0/Rem-Craft/commit/82443921d4b908a3cf432fa215d6b11a42a9ce9c)), closes [#106](https://github.com/ba0gu0/Rem-Craft/issues/106)
* :bug: 提高list文字可见度 ([2ad0b1e](https://github.com/ba0gu0/Rem-Craft/commit/2ad0b1edc4babe06c0ddb503145215764126c267))
* :bug: 整理link-icon ([7af98cc](https://github.com/ba0gu0/Rem-Craft/commit/7af98cc81f12971234659020966fe4ca1dd8195a))
* :bug: 暂时搁置顶栏页签和拖拽兼容的方案 ([4301fa7](https://github.com/ba0gu0/Rem-Craft/commit/4301fa7721c56a6ad92592ebb32a95125acc965c))
* :bug: 更换字体，提高小号字体的可读性 ([52d0c2f](https://github.com/ba0gu0/Rem-Craft/commit/52d0c2f8fb2a5d129114ab13ed3b530308e5392e))
* :bug: 根据顶栏结构动态计算页签边距 ([c2f5c53](https://github.com/ba0gu0/Rem-Craft/commit/c2f5c536b645d2e88247eb3834fec0e2e30d6742)), closes [#67](https://github.com/ba0gu0/Rem-Craft/issues/67)
* :bug: 淡化块滑动条 ([fd68a85](https://github.com/ba0gu0/Rem-Craft/commit/fd68a8565174b85b4e566e238b2f24a4ba2c003d)), closes [#63](https://github.com/ba0gu0/Rem-Craft/issues/63)
* :bug: 目前分屏页签栏的最佳解决方案 ([cf98327](https://github.com/ba0gu0/Rem-Craft/commit/cf983278fb08985d362af2f7d94610da3e81bb2a))
* :bug: 简化list-border写法 ([eadd6e8](https://github.com/ba0gu0/Rem-Craft/commit/eadd6e8ad6f3c270c69ad720729ef1ecd1379542))
* :bug: 美化新版代码片段可视化界面 ([c88e388](https://github.com/ba0gu0/Rem-Craft/commit/c88e388d0580913d889b7b153e17891bdc9108d5))
* :bug: 解决页签滚动带来的拖拽问题 ([5dff76f](https://github.com/ba0gu0/Rem-Craft/commit/5dff76f0caf426dc87db6185236d5e5f5191c3e6))
* :bug: 解决顶栏拖动问题 ([1191d76](https://github.com/ba0gu0/Rem-Craft/commit/1191d76ceb59755514a02ec5f52d76ffc275519f))
* :bug: 调整5，6级标题字号 ([c17406f](https://github.com/ba0gu0/Rem-Craft/commit/c17406f1ecf6fe30434a51f80c08dad73f77ec09))
* :bug: 调整dialog宽度 ([cea3b7c](https://github.com/ba0gu0/Rem-Craft/commit/cea3b7cb7ba6364dcdf7565bb7e8fe4e9ccc3912))
* :bug: 调整顶部页签栏位置 ([bde2ae7](https://github.com/ba0gu0/Rem-Craft/commit/bde2ae7767d71e4349bd0ec99f7cc8d5b5551c81))
* :bug: 进一步解决顶栏拖拽问题 ([bc81b22](https://github.com/ba0gu0/Rem-Craft/commit/bc81b22adba65376f7880f77723b225325d0d06e))
* :bug: 适配mac顶栏 ([fe51ccc](https://github.com/ba0gu0/Rem-Craft/commit/fe51cccb94b23dd46eb6442d5cb096d7e290f45b))
* **components:** :bug: 修复menu的.b3-list-item样式 ([b3b24ab](https://github.com/ba0gu0/Rem-Craft/commit/b3b24ab30241fa7b727831ae673f2c848ef84373))
* **components:** :bug: 修复文档树定位问题 ([aa3dce5](https://github.com/ba0gu0/Rem-Craft/commit/aa3dce57c60225be4f077c80c522914147ef6aec))
* **components:** :bug: 修复通知栏警告、危险和成功样式 ([5f18afc](https://github.com/ba0gu0/Rem-Craft/commit/5f18afcef081caae1a428ea04fc8425a00240de1))
* **components:** :bug: 修改菜单分割线样式 ([33dc207](https://github.com/ba0gu0/Rem-Craft/commit/33dc20712023a75fdbabec58daa028dc2100b0aa))
* **components:** :bug: 页签阴影重置 ([3b3d38b](https://github.com/ba0gu0/Rem-Craft/commit/3b3d38b3276e81922653da18c225c08db8b0201c))
* **pages:** :bug: 修复历史界面的列表样式 ([634f704](https://github.com/ba0gu0/Rem-Craft/commit/634f7048fe6601a8dd05346bdbeffd2c8af46073))
* **pages:** :bug: 修复小弹窗按钮文本颜色样式 ([ace1d80](https://github.com/ba0gu0/Rem-Craft/commit/ace1d80ff2ea86a61dd879940cd172e54db69b95))
* **pages:** :bug: 修复样式工具窗按钮的样式 ([18c967e](https://github.com/ba0gu0/Rem-Craft/commit/18c967e496c8d9c1b9e08fd338db22cb8693fe2d))
* 修复github链接图标显示问题 ([ae285b5](https://github.com/ba0gu0/Rem-Craft/commit/ae285b5c4d84e0a5d4b3ed976319648a9b5e46c4))
* 修复Readme预览图不全屏时的圆角 ([2a70a86](https://github.com/ba0gu0/Rem-Craft/commit/2a70a86be95cddb7fc4bfc21dc8e1e827971fd59))
* 修复Readme预览图展示界面圆角 ([5663fa2](https://github.com/ba0gu0/Rem-Craft/commit/5663fa2e403884fd26a20eac79c64c8574de7fb1))
* 修复wolai链接图标显示问题 ([0e9381a](https://github.com/ba0gu0/Rem-Craft/commit/0e9381a05e63d4d85f9de7fd0f4ec80c7bad2c2a))
* 修复代码块行号和代码不对齐的问题 ([cdfcafe](https://github.com/ba0gu0/Rem-Craft/commit/cdfcafea566b248360af50e2d88e8c4d8fb0f552))
* 修复全局提示上按钮样式问题 ([112b5b8](https://github.com/ba0gu0/Rem-Craft/commit/112b5b8687d47d4194be88526e9c5ad1419ee213))
* 修复全局提示按钮样式问题 ([3d554a3](https://github.com/ba0gu0/Rem-Craft/commit/3d554a379e876f3e23c774b61b88a1fe223f170d))
* 修复全局提示高度问题 ([52e34f4](https://github.com/ba0gu0/Rem-Craft/commit/52e34f4394cf6894fdbff06819abf206ec30c607))
* 修复列表块线条的位置问题 ([676a159](https://github.com/ba0gu0/Rem-Craft/commit/676a159200f5191c1c7549bd784990024b8c176b))
* 修复导出预览页的列表线条位置问题 ([458a21a](https://github.com/ba0gu0/Rem-Craft/commit/458a21adc2b5be38ea8cb2f79a5ae1d520e8c5d4))
* 修复底栏的边栏设置按钮菜单的显示问题 ([a9342b7](https://github.com/ba0gu0/Rem-Craft/commit/a9342b79eb9876bce901a91fdbde7ef1b4dea63f))
* 修复待办列表完成后各子元素的样式问题 ([71b9334](https://github.com/ba0gu0/Rem-Craft/commit/71b9334c91caf9ba31b8e8d5297b39de22f27175))
* 修复待办列表完成时的超链接子块样式 ([d4260f1](https://github.com/ba0gu0/Rem-Craft/commit/d4260f178b9a944f6b5e1dd836703956eb2ffa9f))
* 修复按钮图标宽高及文字行高问题 ([be1bf69](https://github.com/ba0gu0/Rem-Craft/commit/be1bf694cc06eff6df84d69f3b13d3b2bbd80756))
* 修复文档右侧滑条位置偏移的问题 ([285252f](https://github.com/ba0gu0/Rem-Craft/commit/285252f911ab7286f1b8aa0153aa9a6a045f4c13))
* 修复标题为空时的样式 ([b5e88fb](https://github.com/ba0gu0/Rem-Craft/commit/b5e88fbadb2fa815524904cd661bc0af1be5b064))
* 修复移动弹窗搜索结果列表样式问题 ([32385c8](https://github.com/ba0gu0/Rem-Craft/commit/32385c8fe71b6ec9d2a9192d7c3a1d172c634f65))
* 修复超级块下一级列表的样式问题 ([1a5c54e](https://github.com/ba0gu0/Rem-Craft/commit/1a5c54e15456eb3e67c4651411c52aee01c1c4c9))
* 修复页签钉住时的样式问题 ([b4d59c9](https://github.com/ba0gu0/Rem-Craft/commit/b4d59c9fb2c00d919a4bc662d892fb94439b2672))
* 修复顶栏最大化按钮样式问题 ([49982f4](https://github.com/ba0gu0/Rem-Craft/commit/49982f4b2ef78a1d4b1397a6e944cc7e9145094d))
* 修改代码块字号问题 ([1c546b4](https://github.com/ba0gu0/Rem-Craft/commit/1c546b4db3cf2b62fc98c8b4e8862482a01e0c72))
* 修改代码行号颜色 ([5839b45](https://github.com/ba0gu0/Rem-Craft/commit/5839b453e1f4d07564d14db7ad7fe0b23646a8bf))
* 修改块标按钮样式 ([2582286](https://github.com/ba0gu0/Rem-Craft/commit/2582286274eb4a2709899a1eda42f6116d622266))
* 修改段落块的上下内边距 ([c1c6205](https://github.com/ba0gu0/Rem-Craft/commit/c1c6205c0c97b5a6c1cced788f35ba14c9988a74))
* 修改段落块的段间距和行高 ([8155d0b](https://github.com/ba0gu0/Rem-Craft/commit/8155d0beb7ee07b545c873ffbeb46769132fae18))
* 修改滚动条颜色，增加可见性 ([c814617](https://github.com/ba0gu0/Rem-Craft/commit/c814617fa6345227b9779eacb4244fa25afe64cb))
* 兼容最新版本顶栏 ([2937248](https://github.com/ba0gu0/Rem-Craft/commit/29372486b897db73e45f4633b40fedb55749cff5))
* 完善列表块按钮 ([673f7a0](https://github.com/ba0gu0/Rem-Craft/commit/673f7a097d990da97e836dbfd55062ce2b93f626))
* 解决列表块标使用的问题 ([948d035](https://github.com/ba0gu0/Rem-Craft/commit/948d035cf7788139d65214f437eeac2a6349c88e))
* 调整超级块横排间距 ([505018a](https://github.com/ba0gu0/Rem-Craft/commit/505018aed68282cca9a922dfae8d9945e6bb6cd4))

### [2.6.12](https://github.com/svchord/Rem-Craft/compare/v2.6.11...v2.6.12) (2023-07-09)


### 📦‍ 构建相关 | Build System

* :package: 更新依赖 ([e6c7db4](https://github.com/svchord/Rem-Craft/commit/e6c7db486baa211c83a20a47c28c7f926edb3706))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复设置菜单相关样式 ([a232156](https://github.com/svchord/Rem-Craft/commit/a232156b82881d822a516627d116fe729fbf69ab))
* :bug: 修复题头图按钮位置问题 ([fa89c4a](https://github.com/svchord/Rem-Craft/commit/fa89c4a236596ceb4d20736fe1632faedefef88c)), closes [#132](https://github.com/svchord/Rem-Craft/issues/132)
* :bug: 修复新窗口标签页的样式问题 ([6919037](https://github.com/svchord/Rem-Craft/commit/6919037e831ec9e1736d937585199e3a042c0897))

### [2.6.11](https://github.com/svchord/Rem-Craft/compare/v2.6.10...v2.6.11) (2023-06-18)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复段间距的问题 ([f5d468a](https://github.com/svchord/Rem-Craft/commit/f5d468a370c0f952c630650d9678566f7e710508))
* :bug: 修复块菜单样式 ([8a8e6be](https://github.com/svchord/Rem-Craft/commit/8a8e6be488325eede2b6942e348fcc35e63b37c7))

### [2.6.10](https://github.com/svchord/Rem-Craft/compare/v2.6.9...v2.6.10) (2023-05-17)

### [2.6.9](https://github.com/svchord/Rem-Craft/compare/v2.6.8...v2.6.9) (2023-05-17)

### [2.6.8](https://github.com/svchord/Rem-Craft/compare/v2.6.7...v2.6.8) (2023-05-17)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复新版readme界面样式 ([00d9a30](https://github.com/svchord/Rem-Craft/commit/00d9a30c657cee9ffae9215b1eeaf980261819f1))

### [2.6.7](https://github.com/svchord/Rem-Craft/compare/v2.6.6...v2.6.7) (2023-05-11)


### ✏️ 文档更新 | Documentation

* :memo: 更新Readme，增加英文Readme及集市icon ([6f43c71](https://github.com/svchord/Rem-Craft/commit/6f43c71b156f1f8b7c184447369ba7e10add02a3))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容思源v2.8.7新集市样式 ([ae1318b](https://github.com/svchord/Rem-Craft/commit/ae1318bffc6b0e6be27c38d45f6d70564a8e7c72))
* :bug: 修复闪卡使用和管理界面样式 ([71811df](https://github.com/svchord/Rem-Craft/commit/71811df875126c4b33f3bfd78acfad3327ae2ccb))
* :bug: 修复属性弹窗的样式 ([ddbb061](https://github.com/svchord/Rem-Craft/commit/ddbb061ecfbd5fa0e94dc18ba36c295d181cd89a))
* :bug: 修复数据历史菜单样式 ([af515b9](https://github.com/svchord/Rem-Craft/commit/af515b94a0d141ff21a627c3ec67a7269181fbb4))
* :bug: 修复题头图标按钮组的样式问题 ([b570e9a](https://github.com/svchord/Rem-Craft/commit/b570e9abd2a6c24937048f22c77927a6c0a15bcb))

### [2.6.6](https://github.com/svchord/Rem-Craft/compare/v2.6.5...v2.6.6) (2023-04-18)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新版设置界面 ([7f7d465](https://github.com/svchord/Rem-Craft/commit/7f7d465d140513aa69ef135703e8e433c8d33d2c))
* :bug: 修复悬浮窗内块滚动条的样式 ([e8fdedb](https://github.com/svchord/Rem-Craft/commit/e8fdedbe00d5081586d865b0474f49116a98a844))
* :bug: 优化快捷键设置页面的样式 ([fd1e375](https://github.com/svchord/Rem-Craft/commit/fd1e3751627a89b631191fd6994e8928e7eb1f4b))

### [2.6.5](https://github.com/svchord/Rem-Craft/compare/v2.6.4...v2.6.5) (2023-04-11)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复新版menu兼容问题 ([fc71f48](https://github.com/svchord/Rem-Craft/commit/fc71f48b27fc14495de73d927058023398302377))

### [2.6.4](https://github.com/svchord/Rem-Craft/compare/v2.6.3...v2.6.4) (2023-04-11)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 删除了主题自带的日历功能，并适配了日历插件 ([672050b](https://github.com/svchord/Rem-Craft/commit/672050b46750af9ade4d3137840b75595276ced3))
* :bug: 修复右侧边栏被底栏遮挡的问题 ([763a58f](https://github.com/svchord/Rem-Craft/commit/763a58fb63fc849d98548b251704d9806c54be0b)), closes [#121](https://github.com/svchord/Rem-Craft/issues/121)

### [2.6.3](https://github.com/svchord/Rem-Craft/compare/v2.6.2...v2.6.3) (2023-04-06)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复顶栏页签问题 ([d971383](https://github.com/svchord/Rem-Craft/commit/d971383f1efacf38abe07d16c63a86ed64ebf2c5))
* :bug: 修复滑动条位置问题 ([086faa4](https://github.com/svchord/Rem-Craft/commit/086faa4c52d30626691e71b7239dfeb7de33e662))
* :bug: 优化搜索行高度 ([f234c85](https://github.com/svchord/Rem-Craft/commit/f234c85f96da822ed1778b3e76c83693df6fc4e3))

### [2.6.2](https://github.com/svchord/Rem-Craft/compare/v2.6.1...v2.6.2) (2023-03-21)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容思源新版输入框和选择器样式 ([6856f41](https://github.com/svchord/Rem-Craft/commit/6856f417fe85ee0c71efb8e1f46606ebca8f075e)), closes [#118](https://github.com/svchord/Rem-Craft/issues/118)
* :bug: 优化钉住图标的动画 ([89f1c19](https://github.com/svchord/Rem-Craft/commit/89f1c199072d42765a2afb07085fd427434cf399))
* :bug: 优化日历挂件样式 ([01c1dc8](https://github.com/svchord/Rem-Craft/commit/01c1dc893344c839522f5c04aa3545511451ba28))
* :bug: 优化日历样式 ([6909c79](https://github.com/svchord/Rem-Craft/commit/6909c7987e128b066614e47691ebcfb13811bbbf)), closes [#120](https://github.com/svchord/Rem-Craft/issues/120)

### [2.6.1](https://github.com/svchord/Rem-Craft/compare/v2.6.0...v2.6.1) (2023-02-28)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容思源 2.7.7 ([238f600](https://github.com/svchord/Rem-Craft/commit/238f600fb8c57b04abd5d6482f77c2df95fb58ce))
* :bug: 将表格改成不换行 ([2698ee4](https://github.com/svchord/Rem-Craft/commit/2698ee4a2956fdbef2d1ccec40954c0290a55ed7)), closes [#114](https://github.com/svchord/Rem-Craft/issues/114)
* :bug: 修复 docker 环境兼容问题 ([3090370](https://github.com/svchord/Rem-Craft/commit/30903700ea075dbec84df7af41911cebb6770b6d)), closes [#104](https://github.com/svchord/Rem-Craft/issues/104) [#117](https://github.com/svchord/Rem-Craft/issues/117)
* :bug: 修复关系图无法全屏的问题 ([3acbd87](https://github.com/svchord/Rem-Craft/commit/3acbd8792cf2680181990682fd795b4189f54bff)), closes [#113](https://github.com/svchord/Rem-Craft/issues/113)
* :bug: 修复状态栏的显示问题 ([7795975](https://github.com/svchord/Rem-Craft/commit/77959752068f74b3c0c46d1ebcc3d20ba3e3f4a4))
* :bug: 修复emoji菜单样式 ([484eb44](https://github.com/svchord/Rem-Craft/commit/484eb44e15be2dda099b6737c715260d4e151704)), closes [#115](https://github.com/svchord/Rem-Craft/issues/115)
* :bug: 优化日历挂件 ([5883b91](https://github.com/svchord/Rem-Craft/commit/5883b918b200833f6b946373dc968ef82321bcec))

## [2.6.0](https://github.com/svchord/Rem-Craft/compare/v2.5.12...v2.6.0) (2023-02-14)


### ✨ 新增功能 | Features

* :sparkles: 更换日历插件 ([6b704f6](https://github.com/svchord/Rem-Craft/commit/6b704f694d96cd04f961c0001c3c698352bef72c))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新窗口顶部的钉住按钮 ([a1ae40d](https://github.com/svchord/Rem-Craft/commit/a1ae40d1f1d04ffee634b342a738697bc9b262c0))
* :bug: 兼容悬浮边栏 ([706cbea](https://github.com/svchord/Rem-Craft/commit/706cbeae87bc94b593a7ebcb400f23d1a69f964f))
* :bug: 修复暗黑模式的日历插件颜色问题 ([dae323a](https://github.com/svchord/Rem-Craft/commit/dae323a9d0138a9eb3397c6a5c015840742c3d51))
* :bug: 修改监听并去除部分:has ([7c51e57](https://github.com/svchord/Rem-Craft/commit/7c51e57c58c38131b4f1ab721375637e6de0597b)), closes [#82](https://github.com/svchord/Rem-Craft/issues/82) [#109](https://github.com/svchord/Rem-Craft/issues/109)
* :bug: 优化标记本文样式 ([4134bfc](https://github.com/svchord/Rem-Craft/commit/4134bfc06990804a2fb0d885b670030dee2a817d)), closes [#111](https://github.com/svchord/Rem-Craft/issues/111)
* :bug: 左上角 logo 跟随边栏自动变化 ([8244392](https://github.com/svchord/Rem-Craft/commit/82443921d4b908a3cf432fa215d6b11a42a9ce9c)), closes [#106](https://github.com/svchord/Rem-Craft/issues/106)

### [2.5.12](https://github.com/svchord/Rem-Craft/compare/v2.5.11...v2.5.12) (2023-02-03)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复文档树开启卡顿的问题 ([d2c0e98](https://github.com/svchord/Rem-Craft/commit/d2c0e9887b6178257172dc687b597806a569f65e))

### [2.5.11](https://github.com/svchord/Rem-Craft/compare/v2.5.10...v2.5.11) (2023-02-03)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容思源2.7.2 ([128faf8](https://github.com/svchord/Rem-Craft/commit/128faf84437e299dd651b1fcbc1a2f11c139d790))

### [2.5.10](https://github.com/svchord/Rem-Craft/compare/v2.5.9...v2.5.10) (2023-01-28)


### ♻️ 代码重构 | Code Refactoring

* :recycle: 重构静态资源加载方式 ([5fda915](https://github.com/svchord/Rem-Craft/commit/5fda91536bc395e574a343c94f4233d6d9d6aaf6))


### 📦‍ 构建相关 | Build System

* :package: 更新依赖 ([4ac76c4](https://github.com/svchord/Rem-Craft/commit/4ac76c4d0265d06cd2a7c106d5150c33b72c4af1))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容思源2.7.1 ([bde8953](https://github.com/svchord/Rem-Craft/commit/bde895333f0f7c1ac662a6b983e8100cc9267845))
* :bug: 修复顶栏按钮悬浮样式 ([bfa9fc8](https://github.com/svchord/Rem-Craft/commit/bfa9fc8685ecfaefaaa32504e6d98ab0382a3975))

### [2.5.9](https://github.com/svchord/Rem-Craft/compare/v2.5.8...v2.5.9) (2023-01-17)


### ♻️ 代码重构 | Code Refactoring

* :recycle: 优化dock栏监听写法 ([69bbd4d](https://github.com/svchord/Rem-Craft/commit/69bbd4de7d68e40fed8f9891a59234dd6f5e9392))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 初步兼容2.7.0 ([e0d11e7](https://github.com/svchord/Rem-Craft/commit/e0d11e749a7bad8a67bcf6ce50ad53aa6f9b1d87))
* :bug: 兼容思源2.7.0正式版 ([631b9a0](https://github.com/svchord/Rem-Craft/commit/631b9a079bf6f2bddf9f254795c3e67e07d865b6))
* :bug: 修复暗黑模式下日历的颜色问题 ([83cfc18](https://github.com/svchord/Rem-Craft/commit/83cfc18da32152bc0b04b194712d614864ccfa04))
* :bug: 优化模板选择弹窗样式 ([1c43ad3](https://github.com/svchord/Rem-Craft/commit/1c43ad3034b95a545ee3eefb5a8257b52c70add5))
* :bug: 增加顶栏监听 ([dafcf1d](https://github.com/svchord/Rem-Craft/commit/dafcf1d8973b24f93f68419d697f431f3efcc0f9))

### [2.5.8](https://github.com/svchord/Rem-Craft/compare/v2.5.7...v2.5.8) (2023-01-12)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新版顶栏 ([eca2ab8](https://github.com/svchord/Rem-Craft/commit/eca2ab8567d3066f1e9932d2d125d89e4f1e9db2))
* :bug: 修复反链面板样式问题 ([828c546](https://github.com/svchord/Rem-Craft/commit/828c546725da9f221f255b9337fd09d140f9adfb)), closes [#100](https://github.com/svchord/Rem-Craft/issues/100)
* :bug: 修复关系图全屏下的样式问题 ([dad97e0](https://github.com/svchord/Rem-Craft/commit/dad97e0a917fbaca0746bce43ff208c976a6b5ef))
* :bug: 优化闪卡卡组预览界面 ([582d359](https://github.com/svchord/Rem-Craft/commit/582d35923c385571d45f456ea703d1542232e895))

### [2.5.7](https://github.com/svchord/Rem-Craft/compare/v2.5.6...v2.5.7) (2023-01-05)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复设置菜单样式问题 ([7657d8a](https://github.com/svchord/Rem-Craft/commit/7657d8ae049889a4bc32db95392b9eaf41fabb36)), closes [#99](https://github.com/svchord/Rem-Craft/issues/99)
* :bug: 优化闪卡页面样式 ([84131f9](https://github.com/svchord/Rem-Craft/commit/84131f9540b795c9d31640e3c43ff90529eafd50)), closes [#97](https://github.com/svchord/Rem-Craft/issues/97)
* :bug: 增加移动端判断 ([789d8b7](https://github.com/svchord/Rem-Craft/commit/789d8b75e1c7ceeacfa74f5bb0c7d76709a0fb04)), closes [#98](https://github.com/svchord/Rem-Craft/issues/98)

### [2.5.6](https://github.com/svchord/Rem-Craft/compare/v2.5.5...v2.5.6) (2022-12-23)


### ✏️ 文档更新 | Documentation

* :memo: 更新readme ([27a8a83](https://github.com/svchord/Rem-Craft/commit/27a8a8389f34babe78639dd0185b482e74dabf48))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复暗黑模式下选中底色问题 ([2fd81d1](https://github.com/svchord/Rem-Craft/commit/2fd81d1a17fcb1c740693b0f7e1112becdabcf2f)), closes [#96](https://github.com/svchord/Rem-Craft/issues/96)
* :bug: 修复弹窗按钮和右边栏的冲突问题 ([1b0e6e1](https://github.com/svchord/Rem-Craft/commit/1b0e6e18680cd28d4867cb4f5d3c27d51e068e59)), closes [#95](https://github.com/svchord/Rem-Craft/issues/95)
* :bug: 修复列表块内标题块的样式 ([b722e81](https://github.com/svchord/Rem-Craft/commit/b722e81878e24f145a19c4b939380bc20527d447))
* :bug: 修复输入框样式无法查看的问题 ([94973b2](https://github.com/svchord/Rem-Craft/commit/94973b2242b63409e53b4345b87e803e275b3d82))
* :bug: 修复搜索弹窗圆角 ([7f26bc9](https://github.com/svchord/Rem-Craft/commit/7f26bc92bbc93f90ba12d0fe9f93bdf830909baf))
* :bug: 修复子弹流的样式问题 ([b113f62](https://github.com/svchord/Rem-Craft/commit/b113f62632c688385d8aa81b9100bd03054bb2b6))

### [2.5.5](https://github.com/svchord/Rem-Craft/compare/v2.5.4...v2.5.5) (2022-12-11)


### 📦‍ 构建相关 | Build System

* :package: 换用pnpm ([111e67e](https://github.com/svchord/Rem-Craft/commit/111e67e246f65bfe304316c6624c53482b4a3b63))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复超链接图标的问题 ([8612bc7](https://github.com/svchord/Rem-Craft/commit/8612bc72d2a84b59d87572ff5e2a8f31e734787e))
* :bug: 修复关闭按钮失效的问题 ([2513c3b](https://github.com/svchord/Rem-Craft/commit/2513c3bf6d746e2b9c9a6472829213fd8d011cb8)), closes [#85](https://github.com/svchord/Rem-Craft/issues/85)
* :bug: 修复光标丢失的问题 ([6bb0503](https://github.com/svchord/Rem-Craft/commit/6bb050305ecc9dfc737aa0655d84c452b556ef41)), closes [#88](https://github.com/svchord/Rem-Craft/issues/88)
* :bug: 修复行内评论 ([4e326af](https://github.com/svchord/Rem-Craft/commit/4e326afaf73658a7f9ae49a077f72889144b6bf8)), closes [#86](https://github.com/svchord/Rem-Craft/issues/86)
* :bug: 修复子弹流与引用块的冲突问题 ([5f533b0](https://github.com/svchord/Rem-Craft/commit/5f533b0e08841014673b859b9a05262420da0a1e))
* :bug: 增加Alt+B反链面板底部内边距 ([a50e055](https://github.com/svchord/Rem-Craft/commit/a50e0554229f86bad9e36a15e50eb00311c0c2f4)), closes [#90](https://github.com/svchord/Rem-Craft/issues/90)

### [2.5.4](https://github.com/svchord/Rem-Craft/compare/v2.5.3...v2.5.4) (2022-12-06)


### ⚡ 性能提升 | Performance Improvements

* :zap: 重构顶部页签栏，提升性能 ([2bc25e4](https://github.com/svchord/Rem-Craft/commit/2bc25e40d7c744683d8957b11ae88ef7cd312b30))


### ✏️ 文档更新 | Documentation

* :memo: 更新readme ([71cfbae](https://github.com/svchord/Rem-Craft/commit/71cfbae99683f3a911002b045f0318a8d4a3253f))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 淡化块滑动条 ([fd68a85](https://github.com/svchord/Rem-Craft/commit/fd68a8565174b85b4e566e238b2f24a4ba2c003d)), closes [#63](https://github.com/svchord/Rem-Craft/issues/63)
* :bug: 调整顶部页签栏位置 ([bde2ae7](https://github.com/svchord/Rem-Craft/commit/bde2ae7767d71e4349bd0ec99f7cc8d5b5551c81))
* :bug: 修复暗黑模式下.block__logo的颜色问题 ([905ab85](https://github.com/svchord/Rem-Craft/commit/905ab850e3ea1b5eaadd16a212f62a631459231e))
* :bug: 修复大纲界面标题图标样式问题 ([1b45c4f](https://github.com/svchord/Rem-Craft/commit/1b45c4f81ffc079d92371ea5571f336ca0719058))
* :bug: 修复代码片段弹窗关闭按钮样式 ([26f14c0](https://github.com/svchord/Rem-Craft/commit/26f14c066deadc0199fbd3132b3d92a4b8b326ca))
* :bug: 修复反链界面的字体大小问题 ([3aab0cd](https://github.com/svchord/Rem-Craft/commit/3aab0cdf1533ccb1a5697ae2b662088faeab1a89))
* :bug: 修复链接图标显示问题 ([544b6b0](https://github.com/svchord/Rem-Craft/commit/544b6b009aa4ba0b9b8023d1c7021b69271d6262)), closes [#84](https://github.com/svchord/Rem-Craft/issues/84)
* :bug: 修复数据历史界面的样式问题 ([fce0a05](https://github.com/svchord/Rem-Craft/commit/fce0a0546d7f1f1a6545b61c8b1022e86b35b835))
* :bug: 修复题头图使用:has导致的卡顿问题 ([abe83c5](https://github.com/svchord/Rem-Craft/commit/abe83c5c14e2569d1502d3061fb000f4bdd233b0))
* :bug: 修复图片浏览界面缩放文字颜色 ([3502772](https://github.com/svchord/Rem-Craft/commit/35027727e5e2b1bc96210acb8d1ba19847289e14))
* :bug: 修复子弹流样式问题 ([b7688ba](https://github.com/svchord/Rem-Craft/commit/b7688ba62feff2c2fdefc01110db8a543fa6a31e))
* :bug: 修改边栏样式，使得可拖拽窗口 ([bdd041c](https://github.com/svchord/Rem-Craft/commit/bdd041c6289be3371ce6b87cb01d1069a81fb8fd))
* :bug: 优化边窗样式 ([d46b1d3](https://github.com/svchord/Rem-Craft/commit/d46b1d34f360f612d5f4ae5685f359c8079b5633))
* :bug: 优化导出为图片弹窗样式 ([a2bb46f](https://github.com/svchord/Rem-Craft/commit/a2bb46f33d24abdf6320de580c98e5069525c4bd))
* :bug: 优化嵌入块样式 ([d084455](https://github.com/svchord/Rem-Craft/commit/d0844558560841f56bb50503a8a43b914109b85b))
* :bug: 优化行内mark样式 ([1e9fe2b](https://github.com/svchord/Rem-Craft/commit/1e9fe2b9d6c9f9a87bb1125951ea5c9afff69b27))
* :bug: 优化字体菜单按钮样式 ([15fc6db](https://github.com/svchord/Rem-Craft/commit/15fc6db1c8045e5fb07051206e2e9e1034c5c7b8))

### [2.5.3](https://github.com/svchord/Rem-Craft/compare/v2.5.2...v2.5.3) (2022-11-29)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复linux环境下日历按钮的位置 ([c9ac24f](https://github.com/svchord/Rem-Craft/commit/c9ac24f2c269799ebc1605143f96f24248b6a451))

### [2.5.2](https://github.com/svchord/Rem-Craft/compare/v2.5.1...v2.5.2) (2022-11-29)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 根据顶栏结构动态计算页签边距 ([c2f5c53](https://github.com/svchord/Rem-Craft/commit/c2f5c536b645d2e88247eb3834fec0e2e30d6742)), closes [#67](https://github.com/svchord/Rem-Craft/issues/67)
* :bug: 兼容新版搜索界面 ([6280741](https://github.com/svchord/Rem-Craft/commit/6280741063db3c693a403035eb43799c8eda198a))
* :bug: 修复关闭顶部页签后空白页的样式 ([8caded7](https://github.com/svchord/Rem-Craft/commit/8caded7837b785cc0c28ebab9f896045bbacd7b5))
* :bug: 修复集市卡片按钮样式问题 ([9d76fb5](https://github.com/svchord/Rem-Craft/commit/9d76fb57b201b8cd94cc8591fc0569339f7d5966))


### ✏️ 文档更新 | Documentation

* :memo: 更新readme ([46840de](https://github.com/svchord/Rem-Craft/commit/46840de79720f0c9426a16417eb8bf8e25837f84))
* :memo: 更新Readme ([4f198d0](https://github.com/svchord/Rem-Craft/commit/4f198d08c7cfd996975b9e341803bb0c5fc37b15))

### [2.5.1](https://github.com/svchord/Rem-Craft/compare/v2.5.0...v2.5.1) (2022-11-26)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复替换弹窗的样式问题，并优化搜索结果列表 ([0399a14](https://github.com/svchord/Rem-Craft/commit/0399a142d5752ea52d33e35b58c212868e6e993c)), closes [#76](https://github.com/svchord/Rem-Craft/issues/76)
* :bug: 修复引号字体的问题 ([6023b8b](https://github.com/svchord/Rem-Craft/commit/6023b8bd6b5b6e13867f634a166d727d40721e8e))
* :bug: 优化状态栏菜单交互 ([b379384](https://github.com/svchord/Rem-Craft/commit/b37938432011c49126e903e43298ac8ec0b25a91))

## [2.5.0](https://github.com/svchord/Rem-Craft/compare/v2.4.0...v2.5.0) (2022-11-26)


### ♻️ 代码重构 | Code Refactoring

* :recycle: 将文档列表缩进代码抽出，实现用户自定义 ([8355802](https://github.com/svchord/Rem-Craft/commit/83558024aac61439e775a1b48f11a952e177531b))


### ✨ 新增功能 | Features

* :sparkles: 增加子弹流列表辅助线功能 ([cec3bfb](https://github.com/svchord/Rem-Craft/commit/cec3bfb96e981ccd1fde0720cc0de27481a32266))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复边栏动画卡顿问题 ([3fedf12](https://github.com/svchord/Rem-Craft/commit/3fedf122346a9a3cfe8c362dc499a4aab0076441))
* :bug: 修复钉住页签的图标样式 ([a7eb409](https://github.com/svchord/Rem-Craft/commit/a7eb409651eaaef6886c15b3c5c0d89d4ee39d4c))
* :bug: 修复日历挂件新建日记重复问题 ([94c7673](https://github.com/svchord/Rem-Craft/commit/94c767313c2926fd9df53c43f8ebaf095a61f9a8))
* :bug: 修复新版状态栏导致的问题 ([8eacca0](https://github.com/svchord/Rem-Craft/commit/8eacca00a4ee1e0287e1c137ccdfa7ebff44e25a))
* :bug: 修复页签栏关闭动画卡顿问题 ([e70a953](https://github.com/svchord/Rem-Craft/commit/e70a953b865c0b478975810002f056295c8615c6))
* :bug: 优化中性色 ([8f8e396](https://github.com/svchord/Rem-Craft/commit/8f8e396c1f0d1f47e9b038d545cc785b1a20d643))
* :bug: 优化状态栏样式 ([1929e56](https://github.com/svchord/Rem-Craft/commit/1929e56d7747dfd50576276b5d7076f5f78fd846)), closes [#75](https://github.com/svchord/Rem-Craft/issues/75)

## [2.4.0](https://github.com/svchord/Rem-Craft/compare/v2.3.0...v2.4.0) (2022-11-21)


### ♻️ 代码重构 | Code Refactoring

* :recycle: 初步重构顶部页签栏 ([a2f9247](https://github.com/svchord/Rem-Craft/commit/a2f92479c6f337cd22684d9267ffaffd89b9bd6e)), closes [#67](https://github.com/svchord/Rem-Craft/issues/67) [#72](https://github.com/svchord/Rem-Craft/issues/72)
* :recycle: 优化scripts目录结构 ([77b4520](https://github.com/svchord/Rem-Craft/commit/77b452090bec98b2d006e631d5bfd4a36531a113))
* :recycle: 重构目录结构 ([a314038](https://github.com/svchord/Rem-Craft/commit/a314038a7030e4be2c4b320a4879045ccfc64c0a))
* :recycle: 重构文件目录，将link-icon转移到plugin目录下，并恢复wnd动画 ([9a22fac](https://github.com/svchord/Rem-Craft/commit/9a22fac85f76f864c39724a7d5a0fec287dba106))


### ✨ 新增功能 | Features

* :sparkles: 为非最大化窗口添加边框 ([0605908](https://github.com/svchord/Rem-Craft/commit/0605908addfe9abc38ae62c282cd3415d857186f))
* :sparkles: 优化Dock栏样式 ([60884f4](https://github.com/svchord/Rem-Craft/commit/60884f4e1398d634a54fef23fd2db73f0b958bf4)), closes [#51](https://github.com/svchord/Rem-Craft/issues/51)
* :sparkles: 增加日历面板 ([f097ff3](https://github.com/svchord/Rem-Craft/commit/f097ff321409d167b2d5e1fccb2bd91e5481f5e1)), closes [#69](https://github.com/svchord/Rem-Craft/issues/69)
* :sparkles: 整合siyuan-comment功能 ([210cffb](https://github.com/svchord/Rem-Craft/commit/210cffbfb4748819d89cf17ef50ed069bdf95a0f)), closes [#46](https://github.com/svchord/Rem-Craft/issues/46)


### ✏️ 文档更新 | Documentation

* :memo: 更新Readme和preview.png ([d4ac738](https://github.com/svchord/Rem-Craft/commit/d4ac738505ff99a6cdabeeefbff9f100c61b5099))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复顶部页签栏的边距问题 ([65ed8b0](https://github.com/svchord/Rem-Craft/commit/65ed8b05cb7f4250735f00dd3d8687e9d74e02cf))
* :bug: 修复块滚动条的样式问题 ([8c3c603](https://github.com/svchord/Rem-Craft/commit/8c3c60378aa7cb907a0b2a9870540624f5954c8e)), closes [#73](https://github.com/svchord/Rem-Craft/issues/73)
* :bug: 修复文件图标无法显示的问题 ([1cd944e](https://github.com/svchord/Rem-Craft/commit/1cd944e4abd66517d5498556e4b6742bf4cd8923)), closes [#70](https://github.com/svchord/Rem-Craft/issues/70)
* :bug: 修复文件图标无法显示的问题 ([635bc34](https://github.com/svchord/Rem-Craft/commit/635bc345753a2696d2dce5ce0c899ea82ecbcaf2)), closes [#70](https://github.com/svchord/Rem-Craft/issues/70)
* :bug: 修复页签栏滚动时，顶栏无法拖拽窗口的问题 ([bb166ad](https://github.com/svchord/Rem-Craft/commit/bb166ad4fadf2b656f155a31ede702c8b0033fac))
* :bug: 优化选中文字底色，提高可读性 ([13f6e80](https://github.com/svchord/Rem-Craft/commit/13f6e800b74f78f1be975faf732cc6b46bd2ef15)), closes [#66](https://github.com/svchord/Rem-Craft/issues/66)
* :bug: 优化有序列表序号样式 ([cdde49a](https://github.com/svchord/Rem-Craft/commit/cdde49afcfec9aa8b2968ac5950d0f661d419279)), closes [#66](https://github.com/svchord/Rem-Craft/issues/66)
* :bug: 优化tanBar写法，暂时删除边窗动画 ([dc0f0ee](https://github.com/svchord/Rem-Craft/commit/dc0f0eee0f9fb957bb460d6d37bff01f57ac667c))
* :bug: 优化tooltips行高 ([768b3dd](https://github.com/svchord/Rem-Craft/commit/768b3dd6f4fb5dd35ca7fbb5e90f8acc7b8883cd)), closes [#66](https://github.com/svchord/Rem-Craft/issues/66)

## [2.3.0](https://github.com/svchord/Rem-Craft/compare/v2.2.5...v2.3.0) (2022-11-06)


### ✨ 新增功能 | Features

* :sparkles: 参考obsidian改进页签 ([afa3053](https://github.com/svchord/Rem-Craft/commit/afa3053527d8aac86fe01a2e9b68d89a495a8899))


### ⚡ 性能提升 | Performance Improvements

* :zap: 修改行内超链接块写法，提高可维护性 ([fa4c050](https://github.com/svchord/Rem-Craft/commit/fa4c0505c12dc9650227faf2378b62b9769e0306))


### ♻️ 代码重构 | Code Refactoring

* :recycle: 重构theme.js，增加scripts文件目录，提高可维护性 ([c9d25ba](https://github.com/svchord/Rem-Craft/commit/c9d25baea4843b3372d87372c366ad4c88b96d9f))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 减少list-item的间距 ([a71e463](https://github.com/svchord/Rem-Craft/commit/a71e463e711a44f0db118b61d1c377fd9fdc07d9)), closes [#62](https://github.com/svchord/Rem-Craft/issues/62)
* :bug: 适配mac顶栏 ([fe51ccc](https://github.com/svchord/Rem-Craft/commit/fe51cccb94b23dd46eb6442d5cb096d7e290f45b))
* :bug: 修复钉住页签和未打开文档的空界面样式 ([4aeaa9a](https://github.com/svchord/Rem-Craft/commit/4aeaa9a3169b652a5cf884dc52c907fd8a2c9d25))
* :bug: 修复分屏时的bug ([18d1ee7](https://github.com/svchord/Rem-Craft/commit/18d1ee7f2da752d27a60608d4e7f036eac5e68a0))
* :bug: 修复行内标签块换行问题 ([9de8d64](https://github.com/svchord/Rem-Craft/commit/9de8d64dd1ae48600f23a65d41979f73c5f2c6e4)), closes [#60](https://github.com/svchord/Rem-Craft/issues/60)
* :bug: 修复状态栏遮挡问题 ([937f9f3](https://github.com/svchord/Rem-Craft/commit/937f9f3964dcaa36d0bc40008a276cac6a1b0c4d)), closes [#59](https://github.com/svchord/Rem-Craft/issues/59)
* :bug: 修复左侧边栏关闭时的样式缺陷 ([170f5ec](https://github.com/svchord/Rem-Craft/commit/170f5ec981c2cd2feeb999009729bf4aa717251b))
* :bug: 修复pdf导出页边距的问题 ([a512a83](https://github.com/svchord/Rem-Craft/commit/a512a8366474179d5e2378674a95b121beacbfc2))
* :bug: 优化顶栏、页签、边栏的样式 ([089a199](https://github.com/svchord/Rem-Craft/commit/089a199143293e6b7e7397a6a46ae57d8b611490))
* :bug: 优化顶栏页签的一系列样式问题 ([52b58ee](https://github.com/svchord/Rem-Craft/commit/52b58ee8ee2dc48e30215f5eb2e5b8c202a8ea1b))


### ✏️ 文档更新 | Documentation

* :memo: 更新readme和preview.png，修改.versionrc ([7b252fd](https://github.com/svchord/Rem-Craft/commit/7b252fd9d8e717f11727aa36ea18232a236f2fe2))

### [2.2.5](https://github.com/svchord/Rem-Craft/compare/v2.2.4...v2.2.5) (2022-10-31)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 美化新版代码片段可视化界面 ([c88e388](https://github.com/svchord/Rem-Craft/commit/c88e388d0580913d889b7b153e17891bdc9108d5))
* :bug: 修复菜单项位于顶栏位置时无法点击的问题 ([5c02a1e](https://github.com/svchord/Rem-Craft/commit/5c02a1e1f70afdfa7a723b17e5f290b6384c08ab))
* :bug: 修复块引用菜单输入框的样式问题 ([8218bc7](https://github.com/svchord/Rem-Craft/commit/8218bc77905c45e8fefd6e9fdc89a29f3cedc62e))
* :bug: 优化编辑区域行内工具栏样式 ([2f99d76](https://github.com/svchord/Rem-Craft/commit/2f99d76989713ab9f3585b7748f774ade92f7e88)), closes [#56](https://github.com/svchord/Rem-Craft/issues/56)
* :bug: 优化列表块标按钮的样式 ([034b63e](https://github.com/svchord/Rem-Craft/commit/034b63e8e11dbb4d286622a4f49e07c20830f5f5))
* :bug: 优化数据历史界面样式 ([b509cbc](https://github.com/svchord/Rem-Craft/commit/b509cbc92dfce8d8e60c8897fa90485025638dee))
* :bug: 优化引述块样式 ([d3d11ed](https://github.com/svchord/Rem-Craft/commit/d3d11ede2e62ce9cebec896bc63ea8bcb33c5bc9)), closes [#58](https://github.com/svchord/Rem-Craft/issues/58)

### [2.2.4](https://github.com/svchord/Rem-Craft/compare/v2.2.3...v2.2.4) (2022-10-27)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新版列表块辅助线 ([dbf9303](https://github.com/svchord/Rem-Craft/commit/dbf930354af65b040e75b6b11aedc37afe593e5f))
* :bug: 解决页签滚动带来的拖拽问题 ([5dff76f](https://github.com/svchord/Rem-Craft/commit/5dff76f0caf426dc87db6185236d5e5f5191c3e6))
* :bug: 修复编辑区域页面抖动的问题 ([ea97f01](https://github.com/svchord/Rem-Craft/commit/ea97f01cbfbbc3bc50e0383bc762270d3e3556ff))
* :bug: 修复块元信息导出显示样式 ([f24a302](https://github.com/svchord/Rem-Craft/commit/f24a3023a53f76696ae346418e5ab65965264336))
* :bug: 修复快捷键设置菜单样式 ([0e4ce9e](https://github.com/svchord/Rem-Craft/commit/0e4ce9edf63a5a3432c905b73454bb9f38c3c693))
* :bug: 修复属性弹窗书签按钮图标居中问题 ([5af5a6b](https://github.com/svchord/Rem-Craft/commit/5af5a6bc8708e1a84bdd6fd6f3efbdbcec3de661))
* :bug: 优化ctrl + tab菜单 ([03d2d66](https://github.com/svchord/Rem-Craft/commit/03d2d6656f28e7c7d22b8ed97993390b8ffa69d7))

### [2.2.3](https://github.com/svchord/Rem-Craft/compare/v2.2.2...v2.2.3) (2022-10-24)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新版全屏拖拽，减少代码 ([f6f8a4a](https://github.com/svchord/Rem-Craft/commit/f6f8a4a645f30590e8e79535b2d2fe007e22dcd2))
* :bug: 进一步解决顶栏拖拽问题 ([bc81b22](https://github.com/svchord/Rem-Craft/commit/bc81b22adba65376f7880f77723b225325d0d06e))
* :bug: 目前分屏页签栏的最佳解决方案 ([cf98327](https://github.com/svchord/Rem-Craft/commit/cf983278fb08985d362af2f7d94610da3e81bb2a))
* :bug: 修复顶栏拖拽，和兼容mac顶栏 ([b80c490](https://github.com/svchord/Rem-Craft/commit/b80c4901c9fbac6374bbb2bba5e100850ccf5ded))
* :bug: 修复集市tab宽度问题 ([b0872d4](https://github.com/svchord/Rem-Craft/commit/b0872d4f0c7658791eeae0a6a7b1d7f73e708c57))
* :bug: 修复快捷菜单出现在屏幕右侧时的宽度问题 ([8449b94](https://github.com/svchord/Rem-Craft/commit/8449b947a8c4b7660de55751e7e0f08cef0b928e))
* :bug: 修复搜索界面右下角圆角 ([44522a4](https://github.com/svchord/Rem-Craft/commit/44522a4ce63f0776bae4cefdec2214367c869940))
* :bug: 修复搜索列表emoji的问题 ([76ad2b4](https://github.com/svchord/Rem-Craft/commit/76ad2b4f047bd950aaa5a7dc1bafb91bd3a15f8d))
* :bug: 修复页签间隔线未能正常显示的问题 ([d9601b1](https://github.com/svchord/Rem-Craft/commit/d9601b120d2b9bbd94396750bf5fc28b9d63a0a8))
* :bug: 修复账号登陆弹窗的圆角问题 ([9e3783b](https://github.com/svchord/Rem-Craft/commit/9e3783b47a240b65fb001d6ef782608aadf5984c))
* :bug: 修复readme页面中代码块和行内代码的样式 ([6b0717c](https://github.com/svchord/Rem-Craft/commit/6b0717c960cd4465e0c06e43b6c39de6eef3d9f9))
* :bug: 修改菜单项样式 ([c0ccd4d](https://github.com/svchord/Rem-Craft/commit/c0ccd4dd6a088511eafff77676913f401ffa3d88))
* :bug: 优化块元信息样式 ([e2f9664](https://github.com/svchord/Rem-Craft/commit/e2f96646be318c5a849418d92892647cf8a55276))
* :bug: 优化题头emoji ([51b00b1](https://github.com/svchord/Rem-Craft/commit/51b00b1f13582bc1c221fa6900bb2dafd3463888))
* :bug: 优化引述块样式 ([53662e2](https://github.com/svchord/Rem-Craft/commit/53662e255a6b35c59cc10e7ecf72f22c83e197e8))
* :bug: 暂时搁置顶栏页签和拖拽兼容的方案 ([4301fa7](https://github.com/svchord/Rem-Craft/commit/4301fa7721c56a6ad92592ebb32a95125acc965c))


### ✏️ 文档更新 | Documentation

* :memo: 更新readme ([ca94fe1](https://github.com/svchord/Rem-Craft/commit/ca94fe17f3f81ee8e443a60a9f75cd026c2ca24c))
* :memo: 更新Readme ([f6a42fe](https://github.com/svchord/Rem-Craft/commit/f6a42fe7efcfff1c1d7b9c1cd1d043470d7b5185))

### [2.2.2](https://github.com/svchord/Rem-Craft/compare/v2.2.1...v2.2.2) (2022-10-19)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新版底部状态栏 ([6db6ee7](https://github.com/svchord/Rem-Craft/commit/6db6ee77bfbd5b7cf3314132405d460e1fe3cbdd))
* :bug: 兼容新版顶栏 ([b263227](https://github.com/svchord/Rem-Craft/commit/b263227b7a6e7bbe6f832c32276b416d1f93f94c))
* :bug: 兼容新版页签栏 ([52cce7e](https://github.com/svchord/Rem-Craft/commit/52cce7e6a8bc7f525628ce455a02463cfb9af900))
* :bug: 修复暗黑模式的菜单项显示问题 ([78e8315](https://github.com/svchord/Rem-Craft/commit/78e8315f9298d39d78744f19b6147032cdf61d06))
* :bug: 修复并优化底部状态栏 ([cb08730](https://github.com/svchord/Rem-Craft/commit/cb0873031ac6a27bc56e49270b7ca23483412e8d))
* :bug: 修复面包屑和页签栏的几个小问题 ([d0d14f3](https://github.com/svchord/Rem-Craft/commit/d0d14f3dc62e738e621b5aef276d83da052fccb8))
* :bug: 修复行内超链接的样式问题 ([49d42f3](https://github.com/svchord/Rem-Craft/commit/49d42f32a18a9bcfe35de3795bf72fece5ebc496))
* :bug: 修复full-screen的样式问题 ([ce81691](https://github.com/svchord/Rem-Craft/commit/ce81691e8ccdfa28fe267bc00f0c81f9e0e460c4))
* :bug: 修复readme预览图打开时的圆角 ([c922cb7](https://github.com/svchord/Rem-Craft/commit/c922cb76692e79c0bc65f0b05165832dcc117bba))
* :bug: 优化暗黑模式下的关闭按钮样式 ([0553410](https://github.com/svchord/Rem-Craft/commit/0553410aaf92c5fab6ce86bac234525f89c2b98c))
* :bug: 优化面包屑的间隔符号样式 ([a879445](https://github.com/svchord/Rem-Craft/commit/a87944541892a8f4ba8040c06f56eb67a6b23875))
* :bug: 优化页签栏显示和拖拽的兼容逻辑 ([808131d](https://github.com/svchord/Rem-Craft/commit/808131d173b065381b37e5c9867086bdc04dfd73))
* :bug: 优化账户未登录界面 ([6f0902d](https://github.com/svchord/Rem-Craft/commit/6f0902de614969dd03cfb817d327a2b8a0c4f0b9))

### [2.2.1](https://github.com/svchord/Rem-Craft/compare/v2.2.0...v2.2.1) (2022-10-18)


### ✏️ 文档更新 | Documentation

* :memo: 更新 readme ([1608684](https://github.com/svchord/Rem-Craft/commit/16086846c7110102c43e84a6d5bebaedb4adc304))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 调整5，6级标题字号 ([c17406f](https://github.com/svchord/Rem-Craft/commit/c17406f1ecf6fe30434a51f80c08dad73f77ec09))
* :bug: 将状态栏换到左下角 ([18f1a6e](https://github.com/svchord/Rem-Craft/commit/18f1a6ec79c18a0e0ea1c33619d5f94d3627fdd4))
* :bug: 解决顶栏拖动问题 ([1191d76](https://github.com/svchord/Rem-Craft/commit/1191d76ceb59755514a02ec5f52d76ffc275519f))
* :bug: 修复钉住页签的样式问题 ([53b90bd](https://github.com/svchord/Rem-Craft/commit/53b90bdb5f7e241dc46553fdeba885bc01a7d853))
* :bug: 修复分屏时顶部页签栏的拖拽问题 ([bf1e99b](https://github.com/svchord/Rem-Craft/commit/bf1e99b8b407f6682355914e777aa54737337224))
* :bug: 修复快捷键设置界面样式问题 ([8a9e69f](https://github.com/svchord/Rem-Craft/commit/8a9e69ff6e36fe2880b798624a0f9c7510c1b34a))
* :bug: 修复列表嵌套标题块时辅助线的样式问题 ([e3906af](https://github.com/svchord/Rem-Craft/commit/e3906af280bc6862e92e82e18172d4fbaa431042))
* :bug: 修复信息块中的行内标签样式 ([4d156a3](https://github.com/svchord/Rem-Craft/commit/4d156a30dd0c52a5576864c8423e65795a4236d9))
* :bug: 优化笔记本和反链面板样式 ([8a0a41b](https://github.com/svchord/Rem-Craft/commit/8a0a41b5425340e15c88c69ab1b6c0a9cc147ba1))
* :bug: 优化边栏动画 ([749c5bd](https://github.com/svchord/Rem-Craft/commit/749c5bdfe9c0b3311fdaabdca1a08ff63c7715d8))
* :bug: 优化底部状态栏的样式 ([91b13ef](https://github.com/svchord/Rem-Craft/commit/91b13ef53f26c0426801beca1a513b7b06caf8ee))
* :bug: 优化反链编辑器内块标按钮样式 ([1bfe457](https://github.com/svchord/Rem-Craft/commit/1bfe4572279a68aeb55b6defccf214e65c5b0473))
* :bug: 优化反链界面字号 ([90f1c9c](https://github.com/svchord/Rem-Craft/commit/90f1c9cd44b920cde74d11164670dc38cf70599b))
* :bug: 优化反链面板面包屑样式 ([0436218](https://github.com/svchord/Rem-Craft/commit/04362183216d6830a7af2463bd07e665182fdb3b))
* :bug: 优化反链面板样式 ([439cd36](https://github.com/svchord/Rem-Craft/commit/439cd36c5ae002daffcb8cfcb69ddaacad98bbde))
* :bug: 优化集市卡片样式 ([68d6376](https://github.com/svchord/Rem-Craft/commit/68d6376b3fa8921bde1a03cee9685de7dbc045d6))
* :bug: 优化行级元素外观菜单的清除样式按钮 ([fa74f27](https://github.com/svchord/Rem-Craft/commit/fa74f27aad3943bb1e080f5d140fb20ae42386da))
* :bug: 优化行内图片拖拽按钮的样式 ([6c96206](https://github.com/svchord/Rem-Craft/commit/6c96206462d91dd794af4bfea693dc17d289339c))
* :bug: 优化页签钉住时的样式 ([f2068ed](https://github.com/svchord/Rem-Craft/commit/f2068ed72043a4d9a66e1c0343503445bca5aec4))
* :bug: 优化已关闭的笔记本按钮样式 ([d40f8f6](https://github.com/svchord/Rem-Craft/commit/d40f8f6a8231056b44929d8fd9a3332918ece128))
* :bug: 优化引述块和块标按钮的样式 ([93ebcec](https://github.com/svchord/Rem-Craft/commit/93ebcec09b472c9602e08392e56dcc012090b9fd))
* :bug: 优化win-control按钮样式，去掉编辑区域的overlay ([e5948d4](https://github.com/svchord/Rem-Craft/commit/e5948d40d635848b8c76d061583d58e3405f298d))

## [2.2.0](https://github.com/svchord/Rem-Craft/compare/v2.1.9...v2.2.0) (2022-10-17)


### ✨ 新增功能 | Features

* :sparkles: 将页签栏固定在顶栏，并修改相应布局样式 ([8bf2f1c](https://github.com/svchord/Rem-Craft/commit/8bf2f1c2e7e147c293691b8f120c6c39165d34d8))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新的官方css变量 ([8305cc6](https://github.com/svchord/Rem-Craft/commit/8305cc6852d51666a309477ebf577adcfa2ae4c9))
* :bug: 修复快捷键设置面板样式问题 ([fec4cd9](https://github.com/svchord/Rem-Craft/commit/fec4cd94d24ccac4f5e5a84043ccbeb7a0fb78c6))


### ✏️ 文档更新 | Documentation

* :memo: 更新Readme和preview.png ([35a109d](https://github.com/svchord/Rem-Craft/commit/35a109d0f4f1c3ef4148f4b4862cc2d41d70d2e9))

### [2.1.9](https://github.com/svchord/Rem-Craft/compare/v2.1.8...v2.1.9) (2022-10-16)


### ✏️ 文档更新 | Documentation

* :memo: 更新Readme ([1a75134](https://github.com/svchord/Rem-Craft/commit/1a7513456c8b37c7c1896c4b5e21778b96c04e03))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容2.4.1的外观更新 ([0d4a816](https://github.com/svchord/Rem-Craft/commit/0d4a8161584a2c0b90e4cfb21448fba76e2583f2))
* :bug: 修复编辑区域被标题影响宽度的问题 ([bce70a3](https://github.com/svchord/Rem-Craft/commit/bce70a3c43fbdd134c319a997f635cce7c8803a3))
* :bug: 修复窗口失焦时页签文字颜色的问题 ([1622f57](https://github.com/svchord/Rem-Craft/commit/1622f57b549df35f0d5d3059ab0349b68a558253))
* :bug: 修复新版状态栏引起的样式问题 ([84b3923](https://github.com/svchord/Rem-Craft/commit/84b3923617d150bcd4d27481b3df5348b29fd891))
* :bug: 修复block-icon样式问题 ([24b3147](https://github.com/svchord/Rem-Craft/commit/24b31479d74d4a6550f21d4a7a2d062d1dd084b5))
* :bug: 优化一部分反链面板问题 ([5a032a4](https://github.com/svchord/Rem-Craft/commit/5a032a4d285433f75d9a569bb265beea688d3b64))
* :bug: 优化protyle-toolbar样式 ([b2fadae](https://github.com/svchord/Rem-Craft/commit/b2fadaea93a587c1706c5dc46ad9a13e0aeaec62))

### [2.1.8](https://github.com/svchord/Rem-Craft/compare/v2.1.7...v2.1.8) (2022-10-13)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 利用:has优化搜索等弹窗宽度 ([f275172](https://github.com/svchord/Rem-Craft/commit/f275172d3c75b0f076734ccd0e8bacfd79aed586))
* :bug: 利用:has优化题头图样式代码 ([4da6017](https://github.com/svchord/Rem-Craft/commit/4da601767ed86440dd233d7081f95f2efc81b03a))
* :bug: 修复页签栏样式问题 ([2a1a4a1](https://github.com/svchord/Rem-Craft/commit/2a1a4a17d0b5e1a4f665d8319231445fafbe4a19))

### [2.1.7](https://github.com/svchord/Rem-Craft/compare/v2.1.6...v2.1.7) (2022-10-08)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 大纲辅助线鼠标移入块高亮 ([cf190e7](https://github.com/svchord/Rem-Craft/commit/cf190e736fc918afc439771fead7b1a500b2a892)), closes [#33](https://github.com/svchord/Rem-Craft/issues/33)
* :bug: 兼容新版反链面板 ([489aa3a](https://github.com/svchord/Rem-Craft/commit/489aa3a8da72de820159b4c7fbc6913856ad7f67))
* :bug: 兼容新版明暗切换 ([60ce82f](https://github.com/svchord/Rem-Craft/commit/60ce82f39199a9be4ba0ed9ea4e632d57bbe4928))
* :bug: 兼容自适应宽度功能 ([f4064db](https://github.com/svchord/Rem-Craft/commit/f4064db9367c352a1e2a4e21fa1fce1678b2d9b2)), closes [#20](https://github.com/svchord/Rem-Craft/issues/20)
* :bug: 修复备注样式问题 ([37aad9f](https://github.com/svchord/Rem-Craft/commit/37aad9f190e9ff7ada8167540c1e810f7c933acf))
* :bug: 修复超链接及上标导出样式 ([da4dd82](https://github.com/svchord/Rem-Craft/commit/da4dd82157780a1a7e4bfa7a8fd1dc3e361f430c))
* :bug: 修复输入框行高 ([7826f52](https://github.com/svchord/Rem-Craft/commit/7826f526a29e7e8ee893252fe195a85037fb22b3))
* :bug: 修复搜索结果列表样式问题 ([472612f](https://github.com/svchord/Rem-Craft/commit/472612fa99d3348c7bcce390bb53a0a6aa92a31a))
* :bug: 修复menu-item--custom样式 ([4a46a8b](https://github.com/svchord/Rem-Craft/commit/4a46a8b86a3e92a5c4eb06d7f506a8b34a2c719f))
* :bug: 优化各处编辑区域的左右padding ([f719b4c](https://github.com/svchord/Rem-Craft/commit/f719b4c592dec2bc194d881e828e630bc6fbd055))
* :bug: 优化设置界面按钮样式 ([b77e0f8](https://github.com/svchord/Rem-Craft/commit/b77e0f8b71a65ca2339e09ee55b4098afd471696))
* :bug: 优化页签样式 ([73a36ce](https://github.com/svchord/Rem-Craft/commit/73a36ce83cf78132c591244db44d43e9cfcdb991))
* :bug: 优化svg-div ([272819a](https://github.com/svchord/Rem-Craft/commit/272819a59b754e20d77fec852729c4d15ad453e3))

### [2.1.6](https://github.com/svchord/Rem-Craft/compare/v2.1.5...v2.1.6) (2022-09-27)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复标签页下拉菜单样式问题 ([5ec54a4](https://github.com/svchord/Rem-Craft/commit/5ec54a40f5b3ba5b106a3f873906a6bddc93d68d))
* :bug: 修复导出预览界面脚注样式问题 ([d140973](https://github.com/svchord/Rem-Craft/commit/d14097317ded144dbdefc80a32587ce616c3003c))
* :bug: 修复code-block的样式问题 ([9b5c843](https://github.com/svchord/Rem-Craft/commit/9b5c8433cda61bb18dfe37c85ed76c942bb7eeaa)), closes [#43](https://github.com/svchord/Rem-Craft/issues/43)
* :bug: 修复color-square和font-style的样式问题 ([856c8e4](https://github.com/svchord/Rem-Craft/commit/856c8e45e5553fcf7b752101545c281230a8db6d))
* :bug: 修复drag动画缓慢的问题 ([d65c672](https://github.com/svchord/Rem-Craft/commit/d65c6723000b69ef482064f1d0cd8a66d74321de))
* :bug: 优化link样式，减少重复代码 ([3a1918c](https://github.com/svchord/Rem-Craft/commit/3a1918c523e1c402e6a737e62ad38d7137ec4b20))
* :bug: 优化small-dialog代码 ([0b97c47](https://github.com/svchord/Rem-Craft/commit/0b97c4733ca4a38231f15c8b316085e046d6bc44))

### [2.1.5](https://github.com/svchord/Rem-Craft/compare/v2.1.4...v2.1.5) (2022-09-22)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 调整dialog宽度 ([cea3b7c](https://github.com/svchord/Rem-Craft/commit/cea3b7cb7ba6364dcdf7565bb7e8fe4e9ccc3912))
* :bug: 兼容思源2.2.0行内元素的更新 ([72e13e6](https://github.com/svchord/Rem-Craft/commit/72e13e6f8080cbb0ad0c91b344a42e64014dab33))
* :bug: 简化list-border写法 ([eadd6e8](https://github.com/svchord/Rem-Craft/commit/eadd6e8ad6f3c270c69ad720729ef1ecd1379542))
* :bug: 修复block-icon的样式问题 ([d27b4eb](https://github.com/svchord/Rem-Craft/commit/d27b4eb64e98eb3346701669eb92d3b6a66a7087))
* :bug: 修复button样式问题 ([68288ef](https://github.com/svchord/Rem-Craft/commit/68288efd29b487f5a746d78371e45bfc6b4dbe6f))
* :bug: 修复list-block样式 ([1b0891d](https://github.com/svchord/Rem-Craft/commit/1b0891dd9930fd748eff312f6e19c606d3703371))
* :bug: 修复tab-bar的样式问题 ([60d420e](https://github.com/svchord/Rem-Craft/commit/60d420e478bb732c57c78bef4af2faff8b6e611c))
* :bug: 修复utils问题 ([c6ee8ed](https://github.com/svchord/Rem-Craft/commit/c6ee8ed54a7d3248bb3a2dc3a2699b5db5804090))
* :bug: 优化block，减少重复代码 ([c9855ec](https://github.com/svchord/Rem-Craft/commit/c9855ecbb839177031ae1351711be462d4af6e90))
* :bug: 优化quote和gutter样式 ([5779060](https://github.com/svchord/Rem-Craft/commit/5779060a84cb7033bd5df5b416fba1588c976182))

### [2.1.4](https://github.com/svchord/Rem-Craft/compare/v2.1.3...v2.1.4) (2022-09-16)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 更换字体，提高小号字体的可读性 ([52d0c2f](https://github.com/svchord/Rem-Craft/commit/52d0c2f8fb2a5d129114ab13ed3b530308e5392e))
* :bug: 删除.img-select选择器 ([1525f0f](https://github.com/svchord/Rem-Craft/commit/1525f0f023d3046506e757fa14048ed39d427b84))
* :bug: 提高list文字可见度 ([2ad0b1e](https://github.com/svchord/Rem-Craft/commit/2ad0b1edc4babe06c0ddb503145215764126c267))
* :bug: 修复列表嵌套引述块的样式问题 ([626a384](https://github.com/svchord/Rem-Craft/commit/626a384ad2e6fa645d5bad370059e678541c5b93))
* :bug: 修复题头图标签的hover样式 ([2ed9be5](https://github.com/svchord/Rem-Craft/commit/2ed9be563150b9b32049fc05d66fcd6d60623638))
* :bug: 修复block-icon、snackbar的样式问题 ([4d8514e](https://github.com/svchord/Rem-Craft/commit/4d8514e3b8525cd6e40a178ebea39d5e8b2ac58a))
* :bug: 优化小弹窗样式 ([5cfd005](https://github.com/svchord/Rem-Craft/commit/5cfd00541fe5a87fc93e56342c7e751fcb1e2a1d))


### ✏️ 文档更新 | Documentation

* :memo: 更新readme及预览图 ([d14d0e2](https://github.com/svchord/Rem-Craft/commit/d14d0e2591dfac2bd14b5530a50345d00a2f3ca2))

### [2.1.3](https://github.com/svchord/Rem-Craft/compare/v2.1.2...v2.1.3) (2022-09-11)


### ♻️ 代码重构 | Code Refactoring

* :recycle: 覆写map.get函数，增加警告提示 ([b30083a](https://github.com/svchord/Rem-Craft/commit/b30083a7cb126b0f563c61cd75c14eda67815965))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容最新版的pdf导出弹窗 ([b6368d8](https://github.com/svchord/Rem-Craft/commit/b6368d88fedef1ac1102f8a7ecc40ee59eae1d90))
* :bug: 兼容最新版数据历史弹窗样式 ([7e35e1e](https://github.com/svchord/Rem-Craft/commit/7e35e1e1ff3487f17d555cded4e86d1ae6c69aa0))

### [2.1.2](https://github.com/svchord/Rem-Craft/compare/v2.1.1...v2.1.2) (2022-09-08)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新版集市card样式 ([bfdf9b1](https://github.com/svchord/Rem-Craft/commit/bfdf9b1a99b199a43f3ebf9647eb83a43b56b355))
* :bug: 兼容新版页签栏按钮 ([e6f3d49](https://github.com/svchord/Rem-Craft/commit/e6f3d497c88c30df6d3ad7fe23914f5ad16fa94e))
* :bug: 修复emojis面板的几个问题 ([ae842fb](https://github.com/svchord/Rem-Craft/commit/ae842fb9cb3b6f6998d3f09ad0f9c1b604c21ed7))
* :bug: 优化大弹窗左侧tab栏 ([0ea1bc6](https://github.com/svchord/Rem-Craft/commit/0ea1bc64b81076aef35f83e880a9548e7f718090))
* :bug: 整理link-icon ([7af98cc](https://github.com/svchord/Rem-Craft/commit/7af98cc81f12971234659020966fe4ca1dd8195a))

### [2.1.1](https://github.com/svchord/Rem-Craft/compare/v2.1.0...v2.1.1) (2022-09-05)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容新版.b3-list--border类选择器 ([6bd64f4](https://github.com/svchord/Rem-Craft/commit/6bd64f4404907bfd55511943d4e317ce753fcb21))
* :bug: 兼容新版集市已下载tab按钮 ([bcf11b8](https://github.com/svchord/Rem-Craft/commit/bcf11b8fd4041755f623ca4a2d6d0eeca5d56a65))
* :bug: 修复大纲界面标题样式问题 ([46f7b00](https://github.com/svchord/Rem-Craft/commit/46f7b0083b59428bc90f83312687605a878de1be))
* :bug: 优化one dark暗黑模式细节 ([ba76aa7](https://github.com/svchord/Rem-Craft/commit/ba76aa771169f54ed4cc33a5c838f053cf9a6e0f))

## [2.1.0](https://github.com/svchord/Rem-Craft/compare/v2.0.0...v2.1.0) (2022-09-04)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 删除不复用的mixin ([bc8a2bb](https://github.com/svchord/Rem-Craft/commit/bc8a2bb16d50f835a4903b392aa06c0a28358de9))
* :bug: 修复按钮focus状态的底色 ([f720f34](https://github.com/svchord/Rem-Craft/commit/f720f34bb622923f24d50aaf2b65c251740cc51d))
* :bug: 修复暗黑模式下的变量命名问题 ([2935f72](https://github.com/svchord/Rem-Craft/commit/2935f72c32e105146871575270a75834efda0816))
* :bug: 修复list和tab-bar上按钮的颜色变化问题 ([90413c4](https://github.com/svchord/Rem-Craft/commit/90413c49ec0eb517f74d1eefb15c9e06046c1c06))


### ✨ 新增功能 | Features

* :sparkles: 将主题css变量与样式主文件解耦 ([91d68cc](https://github.com/svchord/Rem-Craft/commit/91d68cccc1a8e09e2ece63f881748adf53de2854))
* :sparkles: 完善one-dark暗黑模式风格 ([3b7e8df](https://github.com/svchord/Rem-Craft/commit/3b7e8dfcdb8f29887003611b2cc58a749a8b9925))

## [2.0.0](https://github.com/svchord/Rem-Craft/compare/v1.5.3...v2.0.0) (2022-09-03)


### ⚠ BREAKING CHANGES

* 使用了scss @use 特性，重构了所有文件

### 📦‍ 构建相关 | Build System

* :package: 更新依赖 ([5bf56ee](https://github.com/svchord/Rem-Craft/commit/5bf56ee2a36a52574bb15d44b33074a755c74412))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复暗黑模式下的代码块样式问题 ([a8b71c4](https://github.com/svchord/Rem-Craft/commit/a8b71c46f0a1659b81b78564bf0c3134d8b21cc4))
* :bug: 修复菜单项的文本颜色 ([2bc2fcc](https://github.com/svchord/Rem-Craft/commit/2bc2fccc70bd68fb54f310eae01550c1efd2ac60))
* :bug: 修复超级块内各类块的内边距问题 ([ce4f3d1](https://github.com/svchord/Rem-Craft/commit/ce4f3d121bca1cd8f9e0e75018cfc91b2ca03846))
* :bug: 修复超链接中行内代码块的样式 ([c7bfd39](https://github.com/svchord/Rem-Craft/commit/c7bfd39868e9baeb8911c989dfecca271d9c5952))
* :bug: 修复搜索结果为空时的样式问题 ([e3ce22c](https://github.com/svchord/Rem-Craft/commit/e3ce22c1761b96d726f80a498d29d91ee9e16201))
* :bug: 修复特殊超级块内代码块的样式 ([7f3ea2c](https://github.com/svchord/Rem-Craft/commit/7f3ea2c1035b28da2437adc1fbf4aca56fe7369b))
* :bug: 修复替换界面的高度显示问题 ([1d5929b](https://github.com/svchord/Rem-Craft/commit/1d5929b6e26ec42d13b0aeb3053afbffaa4430b0))
* :bug: 修复引述块折叠后的样式 ([9d3e853](https://github.com/svchord/Rem-Craft/commit/9d3e853267a50536d3ee0815582b857d5f3bf58f))
* :bug: 修复list的高度问题 ([98178bd](https://github.com/svchord/Rem-Craft/commit/98178bdb2b5d1ca822cb0da939419dd33e785abe))
* :bug: 优化代码块样式 ([2189e42](https://github.com/svchord/Rem-Craft/commit/2189e4278fe3f5a0c4d296f94d3696610b5cf822))
* :bug: 优化分割线的样式 ([8c3804f](https://github.com/svchord/Rem-Craft/commit/8c3804fd0df4fcf91de2d0e5002659d057533eb8))
* :bug: 优化开关样式 ([ab8ec4c](https://github.com/svchord/Rem-Craft/commit/ab8ec4c34ba223df782b761f5594c29e24511fd1))
* :bug: 优化搜索筛选菜单 ([91d5d48](https://github.com/svchord/Rem-Craft/commit/91d5d484775387e76c54b2d0557662f48ac0bff9))
* :bug: 优化特殊超级块样式 ([a48f961](https://github.com/svchord/Rem-Craft/commit/a48f9619d07a5df4f22554f89da6f58d311b6d3a))
* :bug: 优化文档区域底部空白面积 ([09416e4](https://github.com/svchord/Rem-Craft/commit/09416e4b4aa242a5a8d98495a6437dd170683e92))
* :bug: 优化行内图片样式 ([7ddeea2](https://github.com/svchord/Rem-Craft/commit/7ddeea2c322b8649f6a80b5a0102392f743306b4))
* :bug: 优化字体 ([4ce0f18](https://github.com/svchord/Rem-Craft/commit/4ce0f1881bed558a7d7d4cc8869baa4d9ec82418))


### ♻️ 代码重构 | Code Refactoring

* :recycle: 重构边栏代码 ([3e5c248](https://github.com/svchord/Rem-Craft/commit/3e5c248984ffdbd2595f3bd6c3a9ec31b37f8f22))
* :recycle: 重构顶栏代码 ([a072872](https://github.com/svchord/Rem-Craft/commit/a07287225c5e7d339104149c8294a29537af3db5))
* :recycle: 重构公共变量 ([fbfbbb6](https://github.com/svchord/Rem-Craft/commit/fbfbbb67639d20203b066968c544ff0f181d6792))
* :recycle: 重构提示条代码 ([6de28e7](https://github.com/svchord/Rem-Craft/commit/6de28e70a1b813651762b930f9aedbfddc868bed))
* :recycle: 重构base相关文件 ([8de2dea](https://github.com/svchord/Rem-Craft/commit/8de2deaf9d683fa2e2093ece763d160c8c4e699b))
* :recycle: 重构component相关 ([ac174ce](https://github.com/svchord/Rem-Craft/commit/ac174cefc6e0c7518902a5598fc6c3bf4f759bc0))
* :recycle: 重构css公共变量 ([a9ac479](https://github.com/svchord/Rem-Craft/commit/a9ac4793124719c944961ca9fc0ca4cfdf014592))
* :recycle: 重构dialog相关 ([7459020](https://github.com/svchord/Rem-Craft/commit/7459020f69e42488194ee7fd424d2e9ebba247e6))
* :recycle: 重构layout相关代码 ([9c916df](https://github.com/svchord/Rem-Craft/commit/9c916dfbd175c8f67c0cf95525084ade3d5b41f7))
* :recycle: 重构panel相关 ([8a17e10](https://github.com/svchord/Rem-Craft/commit/8a17e10cb5291f8728117b2301aeced8a1aa3ebe))
* :recycle: 重构protyle相关 ([32b89f6](https://github.com/svchord/Rem-Craft/commit/32b89f690c736a0d25a13f7cda821680702bafd5))


### ✏️ 文档更新 | Documentation

* :memo: 更新styles目录说明文档 ([021dd02](https://github.com/svchord/Rem-Craft/commit/021dd02bda26edf87d15a903d08b179012980e63))

### [1.5.3](https://github.com/svchord/Rem-Craft/compare/v1.5.2...v1.5.3) (2022-07-28)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复暗黑模式下list-meta的颜色显示问题 ([f49a283](https://github.com/svchord/Rem-Craft/commit/f49a28360191240410073173c04d6cdcf3ce1fd3))
* :bug: 修复表格块的线条显示问题 ([0c36ab4](https://github.com/svchord/Rem-Craft/commit/0c36ab48dd90753efe91fc9cc7c91f85699b100f))
* :bug: 修复部分emoji显示错误的问题 ([7fc38b8](https://github.com/svchord/Rem-Craft/commit/7fc38b895dc47a1771e4972b66f14b7bb0882983))
* :bug: 修复公式块的样式问题 ([0e5ede7](https://github.com/svchord/Rem-Craft/commit/0e5ede734c8da76ace1d193831dd819803063a36)), closes [#27](https://github.com/svchord/Rem-Craft/issues/27)
* :bug: 修复账号界面的部分显示问题 ([b7aaa4a](https://github.com/svchord/Rem-Craft/commit/b7aaa4ac6f14cc21ba0fbb2f1fd87d9712860b03))
* :bug: 修复mark标记块的样式 ([8832f5e](https://github.com/svchord/Rem-Craft/commit/8832f5edc606ffeb885fccd4c60b7f0933d99562))
* :bug: 优化超级块的样式 ([db1ad3b](https://github.com/svchord/Rem-Craft/commit/db1ad3b1ce12e2385773221e8dd4cbca650dd528))
* :bug: 优化代码块样式 ([ac3bcea](https://github.com/svchord/Rem-Craft/commit/ac3bcea063975131467b4cf5fb1e5870f7e862c1))
* :bug: 优化各块折叠后的样式问题 ([eae51de](https://github.com/svchord/Rem-Craft/commit/eae51de93d59640f50d976b19a49c9fded056b1b))
* :bug: 优化开关样式，更贴合win11风格 ([9630104](https://github.com/svchord/Rem-Craft/commit/9630104aafff694937cf536f05e83bc8ed53cc97))
* :bug: 优化输入框和代码选择语言菜单的样式 ([9019abb](https://github.com/svchord/Rem-Craft/commit/9019abbd1a8a1d08c431a914630ad91218b97fc2))
* :bug: 优化引述块内首个标题块的样式 ([28e0864](https://github.com/svchord/Rem-Craft/commit/28e08649f1563458b6b0c5dc1f3637266cf9d6b7))
* :bug: 优化字体 ([b0fc6cf](https://github.com/svchord/Rem-Craft/commit/b0fc6cf32a78f8fd61e902da3a7d6f963ae264f8))

### [1.5.2](https://github.com/svchord/Rem-Craft/compare/v1.5.1...v1.5.2) (2022-07-26)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复集市卡片的样式 ([dfb6564](https://github.com/svchord/Rem-Craft/commit/dfb65641a16edbc88e7bff94bb8c2fe320655e23))
* :bug: 修复主题重载时的资源地址问题 ([8a3feac](https://github.com/svchord/Rem-Craft/commit/8a3feac5ddae469e5f56fc391951962b5709eebe))
* :bug: 优化滚动条颜色 ([15264be](https://github.com/svchord/Rem-Craft/commit/15264beefb58697a6607e3edf3d747187f013249))

### [1.5.1](https://github.com/svchord/Rem-Craft/compare/v1.5.0...v1.5.1) (2022-07-26)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复引述块嵌套表格块的问题 ([9b26ed2](https://github.com/svchord/Rem-Craft/commit/9b26ed2acf0336275857b9e8d7efa48eb2f0ee49))

## [1.5.0](https://github.com/svchord/Rem-Craft/compare/v1.4.3...v1.5.0) (2022-07-26)


### ✨ 新增功能 | Features

* :sparkles: 明暗切换 ([b73e3be](https://github.com/svchord/Rem-Craft/commit/b73e3be3e205ba2da677d999cf812ed7c6c9d183))

### [1.4.3](https://github.com/svchord/Rem-Craft/compare/v1.4.2...v1.4.3) (2022-07-18)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复引述块的样式问题 ([2ca2175](https://github.com/svchord/Rem-Craft/commit/2ca21751ba579079c3295727d4f4b60a5e14a18a)), closes [#26](https://github.com/svchord/Rem-Craft/issues/26)
* :bug: 优化了编辑器内各拖拽时的阴影 ([1d7c086](https://github.com/svchord/Rem-Craft/commit/1d7c08648665e1b00f8a0c8101ae43f4414080d2))
* :bug: 优化题头emoji和文档按钮的位置 ([f44a64a](https://github.com/svchord/Rem-Craft/commit/f44a64a1dd5ac9985c9209636bc974e57c8570a6))

### [1.4.2](https://github.com/svchord/Rem-Craft/compare/v1.4.1...v1.4.2) (2022-07-14)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 减小编辑器内一级各类块的两侧内边距，优化阅读 ([d1d3b3a](https://github.com/svchord/Rem-Craft/commit/d1d3b3a8712464c78c2a2089f1d91f60a5c4b2d7))
* :bug: 修复标题为空时大纲界面显示的bug ([5959505](https://github.com/svchord/Rem-Craft/commit/5959505a46dde2c18f7f3fb055ad17cf44c6e0b9))
* :bug: 修复代码块菜单内的特殊开关样式 ([61b6a3c](https://github.com/svchord/Rem-Craft/commit/61b6a3c8f4c845082d63d5b422eedc0385c68809))
* :bug: 修复列表块的宽度显示问题 ([4e044c2](https://github.com/svchord/Rem-Craft/commit/4e044c22d4b51a60dbe2a5618a6b8398ad8c4925))
* :bug: 修复鼠标拖拽框的样式 ([8fa4f7f](https://github.com/svchord/Rem-Craft/commit/8fa4f7fc7e80b7c87e0371a42e484b4ec76d88bf))
* :bug: 优化标签块的可读性 ([5b56cfd](https://github.com/svchord/Rem-Craft/commit/5b56cfde1a77ef9fc441e598abab723094bfb8e7))
* :bug: 优化标题图标样式 ([0f904d4](https://github.com/svchord/Rem-Craft/commit/0f904d40d5e33257a92166fd7d7aea838483eab2))
* :bug: 优化超级块的内外边距，与其他块统一 ([7294670](https://github.com/svchord/Rem-Craft/commit/7294670a2e0a97e4f527263b9f6f03e4854e0848))
* :bug: 优化代码选择语言弹窗列表的样式 ([14d2eaf](https://github.com/svchord/Rem-Craft/commit/14d2eafcdda15fc294bfdc02a86af30924dfcab4))
* :bug: 优化代码语言选择按钮的样式 ([d89c15b](https://github.com/svchord/Rem-Craft/commit/d89c15b30c75f4446fa58db55f39cc2ee0844be3))
* :bug: 优化集市排序图标的位置 ([a20c60d](https://github.com/svchord/Rem-Craft/commit/a20c60d157e8b17a7cb722a9b4609dbd0a08ccfe))
* :bug: 优化块引用菜单列表项内命名、别名等元信息的样式 ([b5d0bf1](https://github.com/svchord/Rem-Craft/commit/b5d0bf10130eec34fec1f24e968633560e5459f0))
* :bug: 优化添加标签菜单无标签时的样式 ([cfdca70](https://github.com/svchord/Rem-Craft/commit/cfdca70b934488e627bc36ebc2ecdbb6ff511c5f))
* :bug: 优化文档按钮组的样式 ([1606599](https://github.com/svchord/Rem-Craft/commit/16065990d0c2eed9c707c2727d61b50c7667887f))
* :bug: 优化已关闭笔记本的样式 ([f285598](https://github.com/svchord/Rem-Craft/commit/f285598a2a379b78b9eb571bd091877b45a2cae6))

### [1.4.1](https://github.com/svchord/Rem-Craft/compare/v1.4.0...v1.4.1) (2022-07-12)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 去除新版readme界面中预览图的下外边距 ([040b92a](https://github.com/svchord/Rem-Craft/commit/040b92af0a8554618dcb4be847c766b00971e08d))
* :bug: 修复数据快照界面显示问题 ([b7fe58c](https://github.com/svchord/Rem-Craft/commit/b7fe58ca3b54e0a3cd8b647bfffbdc5cfda5b54f))
* :bug: 修复搜索界面结果展示的底部空白问题 ([5bdbb06](https://github.com/svchord/Rem-Craft/commit/5bdbb066d79e6c176208f2d709e1759f6d62dbe4))


### ✏️ 文档更新 | Documentation

* :memo: 更新readme和preview.png ([66db598](https://github.com/svchord/Rem-Craft/commit/66db5986d16804d330b9290433cdd6e8325b2942))

## [1.4.0](https://github.com/svchord/Rem-Craft/compare/v1.3.0...v1.4.0) (2022-07-12)


### ✏️ 文档更新 | Documentation

* :memo: 更新readme ([0ac3bdf](https://github.com/svchord/Rem-Craft/commit/0ac3bdfbb06ed73f8ad75174236cbafee96af5ea))


### ✨ 新增功能 | Features

* :sparkles: 更改渲染块操作菜单样式 ([5a6b3b3](https://github.com/svchord/Rem-Craft/commit/5a6b3b34133502d68a305112a711f02f6ca45e26))
* :sparkles: 更改iframe块样式 ([8af8609](https://github.com/svchord/Rem-Craft/commit/8af86099a0b416c67961ebf0f2f1bb4b16ffef88))
* :sparkles: 优化块嵌入样式，提高可读性 ([f8f7ff3](https://github.com/svchord/Rem-Craft/commit/f8f7ff3de44c1aa606718ba69000864fa8ab6ae8))
* :sparkles: 优化行内图片的按钮样式 ([204bcb9](https://github.com/svchord/Rem-Craft/commit/204bcb9582a4f9c3a25117425ad42e504337155d))
* :sparkles: 优化list的竖向滚动条显示 ([cd713c4](https://github.com/svchord/Rem-Craft/commit/cd713c4ab5da096a33b0777828da8c3a0f602574))
* :sparkles: 在无子元素的列表项前增加圆点，增强可读性 ([738208a](https://github.com/svchord/Rem-Craft/commit/738208a0725cd314b19923176e95133546ef607e))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复边窗动画效果不匹配的问题 ([80ebca3](https://github.com/svchord/Rem-Craft/commit/80ebca304d04208a2ba437c4f38ec5e881ba59fe))
* :bug: 修复编辑区域窄宽度显示横向滚动条的问题 ([564e945](https://github.com/svchord/Rem-Craft/commit/564e9453fedf43b66e56584e013e6e1423ac4da6))
* :bug: 修复菜单read-only的样式 ([4614df9](https://github.com/svchord/Rem-Craft/commit/4614df9570ebcdc52f3a049a936e8b78e4251070))
* :bug: 修复代码块菜单透明度的问题 ([210d1f5](https://github.com/svchord/Rem-Craft/commit/210d1f5818e1dafb2e61ba5c142912935bbb0e51))
* :bug: 修复反链展开后图标位置错误的问题 ([a985d27](https://github.com/svchord/Rem-Craft/commit/a985d27d086df9c892b32c2447d6d3c8573b2702))
* :bug: 修复列表块按钮和辅助线的显示问题 ([03a9b37](https://github.com/svchord/Rem-Craft/commit/03a9b3766bfc9e6bc3b84956b2588bdf2ce0af5c))
* :bug: 修复视频菜单资源栏输入框的长度问题 ([570ed75](https://github.com/svchord/Rem-Craft/commit/570ed75759b670d5557e1ebc7c7ca15003c40937))
* :bug: 修改辅助条圆角 ([c5183bc](https://github.com/svchord/Rem-Craft/commit/c5183bc112cbe878948e61e564d56cd4ba6d7390))
* :bug: 修改块嵌入的样式 ([5f3dcba](https://github.com/svchord/Rem-Craft/commit/5f3dcbadf315c122da5ff5d088b206c6c004e13d))
* :bug: 修改mark标记样式 ([1d58ce0](https://github.com/svchord/Rem-Craft/commit/1d58ce02e5f842ee2c6fe8178bfd519d862bb6ac))
* :bug: 修改wnd圆角 ([9ea4339](https://github.com/svchord/Rem-Craft/commit/9ea43397bb5d181a9d36bb515ce2e5d1d4439c3c))
* :bug: 优化渲染块输入界面util的样式 ([69d480d](https://github.com/svchord/Rem-Craft/commit/69d480dc43f3b0e25657b6d62e3817f4c9bd94ca))
* :bug: 优化mark的样式，增加可读性 ([d3d8be9](https://github.com/svchord/Rem-Craft/commit/d3d8be90ff9f38293c386bf2e5666bf07355d8fb))

## [1.3.0](https://github.com/svchord/Rem-Craft/compare/v1.2.0...v1.3.0) (2022-07-10)


### 🐛 修复缺陷 | Bug Fixes

* :bug: 修复设置界面边栏列表的样式 ([680fc29](https://github.com/svchord/Rem-Craft/commit/680fc29285502701ecf0a30be3852bbdb2949bd9))


### ✏️ 文档更新 | Documentation

* :memo: 更新readme和preview.png ([5612bab](https://github.com/svchord/Rem-Craft/commit/5612babd562207ff548f15bbc43a3f7d99d22054))


### ✨ 新增功能 | Features

* :sparkles: 增加新的超链接块图标 ([d5d6f1a](https://github.com/svchord/Rem-Craft/commit/d5d6f1a5c723b06061b427863f1f2f4cc6acb03a))

## [1.2.0](https://github.com/svchord/Rem-Craft/compare/v1.1.0...v1.2.0) (2022-07-10)


### ✏️ 文档更新 | Documentation

* 更新readme ([97bdbe3](https://github.com/svchord/Rem-Craft/commit/97bdbe36bc03ed5cacff905b17192d59fb39bf2f))


### 🎡 持续集成 | Continuous Integration

* **deps:** :ferris_wheel: 更新commit工作流 ([5852556](https://github.com/svchord/Rem-Craft/commit/5852556cec16a226c08034f4a77bf467cf033bb1))


### ⚡ 性能提升 | Performance Improvements

* **components:** :zap: 重新构建list样式的依赖关系，减少编译后的代码量，增加代码可读性 ([908d10d](https://github.com/svchord/Rem-Craft/commit/908d10da64553e5dce1b512c3d7df4676f9bce54))
* **layout:** :zap: 重新构建wnd样式的依赖关系，减少编译后的代码量，增加代码可读性 ([58fe087](https://github.com/svchord/Rem-Craft/commit/58fe087fcae8e32dcc34f3ae04896da9e042a93a))


### ✨ 新增功能 | Features

* **components:** :sparkles: 更新滑条动画，缩小滑块大小 ([8c02a02](https://github.com/svchord/Rem-Craft/commit/8c02a02763183c4fafd37b260af576686f19c202))
* **components:** :sparkles: 修改文档树、书签的一级列表项和大纲标题的样式 ([5e34ccb](https://github.com/svchord/Rem-Craft/commit/5e34ccb117a43065cad146490aa16a392d2b931c))


### 🐛 修复缺陷 | Bug Fixes

* :bug: 兼容部分官方css变量 ([5388fe8](https://github.com/svchord/Rem-Craft/commit/5388fe8a8cc710e9ba75162dac8ca51ba0d1a814))
* :bug: 修改边栏按钮聚焦条的圆角 ([3ca4a85](https://github.com/svchord/Rem-Craft/commit/3ca4a8588093f12f4f54d14ce05117f4996743b6))
* 修复底栏的边栏设置按钮菜单的显示问题 ([a9342b7](https://github.com/svchord/Rem-Craft/commit/a9342b79eb9876bce901a91fdbde7ef1b4dea63f))
* 修复文档右侧滑条位置偏移的问题 ([285252f](https://github.com/svchord/Rem-Craft/commit/285252f911ab7286f1b8aa0153aa9a6a045f4c13))
* **components:** :bug: 修复通知栏警告、危险和成功样式 ([5f18afc](https://github.com/svchord/Rem-Craft/commit/5f18afcef081caae1a428ea04fc8425a00240de1))
* **components:** :bug: 修复文档树定位问题 ([aa3dce5](https://github.com/svchord/Rem-Craft/commit/aa3dce57c60225be4f077c80c522914147ef6aec))
* **components:** :bug: 修复menu的.b3-list-item样式 ([b3b24ab](https://github.com/svchord/Rem-Craft/commit/b3b24ab30241fa7b727831ae673f2c848ef84373))
* **components:** :bug: 修改菜单分割线样式 ([33dc207](https://github.com/svchord/Rem-Craft/commit/33dc20712023a75fdbabec58daa028dc2100b0aa))
* **components:** :bug: 页签阴影重置 ([3b3d38b](https://github.com/svchord/Rem-Craft/commit/3b3d38b3276e81922653da18c225c08db8b0201c))
* **pages:** :bug: 修复历史界面的列表样式 ([634f704](https://github.com/svchord/Rem-Craft/commit/634f7048fe6601a8dd05346bdbeffd2c8af46073))
* **pages:** :bug: 修复小弹窗按钮文本颜色样式 ([ace1d80](https://github.com/svchord/Rem-Craft/commit/ace1d80ff2ea86a61dd879940cd172e54db69b95))
* **pages:** :bug: 修复样式工具窗按钮的样式 ([18c967e](https://github.com/svchord/Rem-Craft/commit/18c967e496c8d9c1b9e08fd338db22cb8693fe2d))

## [1.1.0](https://github.com/svchord/Rem-Craft/compare/v1.0.0...v1.1.0) (2022-06-29)


### 👷 Continuous Integration | CI 配置

* **npm:** 更新standard-version命令 ([f8a2cde](https://github.com/svchord/Rem-Craft/commit/f8a2cde5ee29f13b04005cccf9cf7cca0d4a7aee))


### ⚡ Performance Improvements | 性能优化

* 重新构建menu样式的依赖关系，减少编译后的代码量，增加代码可读性 ([ae49b70](https://github.com/svchord/Rem-Craft/commit/ae49b70217501ec9adf5e1df8798db04976dab16))


### ✏️ Documentation | 文档

* 更新readme ([3abd270](https://github.com/svchord/Rem-Craft/commit/3abd270f8299da58a849d4fc7a729d7a8ad1f2af))


### ✨ Features | 新功能

* 更新底栏各项目颜色 ([6c5718c](https://github.com/svchord/Rem-Craft/commit/6c5718c4eab4b1ab0697cd7370863c983d3f4a3b))
* 更新关系图设置面板样式 ([7d1dda8](https://github.com/svchord/Rem-Craft/commit/7d1dda8a00273243ed80906227e3d73ba6261df0))
* 更新全屏后的顶栏样式 ([4150ffe](https://github.com/svchord/Rem-Craft/commit/4150ffe6cbe8784a68e410b51f15978c15da2b79))
* 兼容最新版本底栏 ([3f26e0b](https://github.com/svchord/Rem-Craft/commit/3f26e0bb6f644b9fa1b5623adf675c510e94053c))
* 兼容最新版本顶栏 ([0f4aadf](https://github.com/svchord/Rem-Craft/commit/0f4aadf661d7adf3806310585394460833e310c2))
* 优化低层阴影样式 ([83dfbd3](https://github.com/svchord/Rem-Craft/commit/83dfbd3c51205582456e0b20287faba91ebc6f26))
* 优化滑条样式 ([1fd2c9a](https://github.com/svchord/Rem-Craft/commit/1fd2c9aa085d5ca5b347743fc5e05dcba999e0a9))


### 🐛 Bug Fixes | Bug 修复

* 完善列表块按钮 ([673f7a0](https://github.com/svchord/Rem-Craft/commit/673f7a097d990da97e836dbfd55062ce2b93f626))
* 修复按钮图标宽高及文字行高问题 ([be1bf69](https://github.com/svchord/Rem-Craft/commit/be1bf694cc06eff6df84d69f3b13d3b2bbd80756))
* 修复超级块下一级列表的样式问题 ([1a5c54e](https://github.com/svchord/Rem-Craft/commit/1a5c54e15456eb3e67c4651411c52aee01c1c4c9))
* 修复页签钉住时的样式问题 ([b4d59c9](https://github.com/svchord/Rem-Craft/commit/b4d59c9fb2c00d919a4bc662d892fb94439b2672))
* 修复wolai链接图标显示问题 ([0e9381a](https://github.com/svchord/Rem-Craft/commit/0e9381a05e63d4d85f9de7fd0f4ec80c7bad2c2a))

## [1.0.0](https://github.com/svchord/Rem-Craft/compare/v0.5.2...v1.0.0) (2022-06-27)


### ⚡ Performance Improvements | 性能优化

* 重新构建文本框样式的依赖关系，减少编译后的代码量，增加代码可读性 ([18fa89e](https://github.com/svchord/Rem-Craft/commit/18fa89e5876c2051883eb7598da3db1acc9bb61e))
* 重新构建button样式的依赖关系，减少编译后的代码量，增加代码可读性 ([eb8beba](https://github.com/svchord/Rem-Craft/commit/eb8beba1ba68c8567233d00555268ae3ab70990f))


### ✏️ Documentation | 文档

* 更新预览图 ([a5f45a9](https://github.com/svchord/Rem-Craft/commit/a5f45a9022ff2edf4e574f4673e888330f09e3ce))


### 🐛 Bug Fixes | Bug 修复

* 兼容最新版本顶栏 ([2937248](https://github.com/svchord/Rem-Craft/commit/29372486b897db73e45f4633b40fedb55749cff5))
* 修复列表块线条的位置问题 ([676a159](https://github.com/svchord/Rem-Craft/commit/676a159200f5191c1c7549bd784990024b8c176b))
* 修复全局提示按钮样式问题 ([3d554a3](https://github.com/svchord/Rem-Craft/commit/3d554a379e876f3e23c774b61b88a1fe223f170d))
* 修复全局提示高度问题 ([52e34f4](https://github.com/svchord/Rem-Craft/commit/52e34f4394cf6894fdbff06819abf206ec30c607))


### ✨ Features | 新功能

* 调整标签搜索界面搜索按钮的样式 ([dc9fd11](https://github.com/svchord/Rem-Craft/commit/dc9fd110923adf2ac54c473b7dec0d878fba76fe))
* 调整数据历史界面样式 ([9b1f951](https://github.com/svchord/Rem-Craft/commit/9b1f951c4f4311f97041cf2f1ce6b6e4a7fde6ad))
* 更新计数块样式 ([a8db2cf](https://github.com/svchord/Rem-Craft/commit/a8db2cfaf16e6a7eb85d4ab3a59921145b764600))
* 更新数据历史界面样式 ([0208658](https://github.com/svchord/Rem-Craft/commit/02086586a6c245ae4ca0b1b2814e7991a01b06c3))
* 添加最新版本底栏样式 ([16aeffd](https://github.com/svchord/Rem-Craft/commit/16aeffd14b9b5c181d10c271af280e1ca22cb136))
* 完善小弹窗的内容样式 ([c698ac3](https://github.com/svchord/Rem-Craft/commit/c698ac39b5bdd147301950b7c2e4264e44ddf420))

### [0.5.2](https://github.com/svchord/Rem-Craft/compare/v0.5.1...v0.5.2) (2022-06-26)


### ✏️ Documentation | 文档

* 修改style目录下的文件说明 ([031b5da](https://github.com/svchord/Rem-Craft/commit/031b5dabb231e7a1e9ae59234866becc23cf3fdb))


### 🐛 Bug Fixes | Bug 修复

* 解决列表块标使用的问题 ([948d035](https://github.com/svchord/Rem-Craft/commit/948d035cf7788139d65214f437eeac2a6349c88e))
* 修复待办列表完成后各子元素的样式问题 ([71b9334](https://github.com/svchord/Rem-Craft/commit/71b9334c91caf9ba31b8e8d5297b39de22f27175))
* 修复待办列表完成时的超链接子块样式 ([d4260f1](https://github.com/svchord/Rem-Craft/commit/d4260f178b9a944f6b5e1dd836703956eb2ffa9f))
* 修复导出预览页的列表线条位置问题 ([458a21a](https://github.com/svchord/Rem-Craft/commit/458a21adc2b5be38ea8cb2f79a5ae1d520e8c5d4))
* 修复全局提示上按钮样式问题 ([112b5b8](https://github.com/svchord/Rem-Craft/commit/112b5b8687d47d4194be88526e9c5ad1419ee213))
* 修复移动弹窗搜索结果列表样式问题 ([32385c8](https://github.com/svchord/Rem-Craft/commit/32385c8fe71b6ec9d2a9192d7c3a1d172c634f65))


### ✨ Features | 新功能

* 修改数据历史界面样式 ([505d94d](https://github.com/svchord/Rem-Craft/commit/505d94d67de249418c53c797e98c9dbc482b0b7e))
* pDF导出弹窗样式更新 ([a7d0a6e](https://github.com/svchord/Rem-Craft/commit/a7d0a6e4ea30d57d5da8b07f070fc41d1e3f1f49))

### [0.5.1](https://github.com/svchord/Rem-Craft/compare/v0.5.0...v0.5.1) (2022-06-24)


### 🐛 Bug Fixes | Bug 修复

* 修复标题为空时的样式 ([b5e88fb](https://github.com/svchord/Rem-Craft/commit/b5e88fbadb2fa815524904cd661bc0af1be5b064))
* 修复代码块行号和代码不对齐的问题 ([cdfcafe](https://github.com/svchord/Rem-Craft/commit/cdfcafea566b248360af50e2d88e8c4d8fb0f552))
* 修复Readme预览图不全屏时的圆角 ([2a70a86](https://github.com/svchord/Rem-Craft/commit/2a70a86be95cddb7fc4bfc21dc8e1e827971fd59))
* 修复Readme预览图展示界面圆角 ([5663fa2](https://github.com/svchord/Rem-Craft/commit/5663fa2e403884fd26a20eac79c64c8574de7fb1))
* 修改代码块字号问题 ([1c546b4](https://github.com/svchord/Rem-Craft/commit/1c546b4db3cf2b62fc98c8b4e8862482a01e0c72))
* 修改代码行号颜色 ([5839b45](https://github.com/svchord/Rem-Craft/commit/5839b453e1f4d07564d14db7ad7fe0b23646a8bf))
* 修改段落块的段间距和行高 ([8155d0b](https://github.com/svchord/Rem-Craft/commit/8155d0beb7ee07b545c873ffbeb46769132fae18))
* 修改段落块的上下内边距 ([c1c6205](https://github.com/svchord/Rem-Craft/commit/c1c6205c0c97b5a6c1cced788f35ba14c9988a74))
* 修改滚动条颜色，增加可见性 ([c814617](https://github.com/svchord/Rem-Craft/commit/c814617fa6345227b9779eacb4244fa25afe64cb))


### ✏️ Documentation | 文档

* 更新Readme ([9fda5b9](https://github.com/svchord/Rem-Craft/commit/9fda5b939d90d9d996c01cfdc4300abb21957597))

## 0.5.0 (2022-06-23)


### ⚠ BREAKING CHANGES

* 参考TDesign的文件目录组织结构，添加色板和全局Token，提高代码的延展性

### ♻️ Code Refactoring | 代码重构

* 代码重构 ([83c0e43](https://github.com/svchord/Rem-Craft/commit/83c0e437cf0330f824ad126c73834cbd7690dd22)), closes [#15](https://github.com/svchord/Rem-Craft/issues/15) [#18](https://github.com/svchord/Rem-Craft/issues/18) [#21](https://github.com/svchord/Rem-Craft/issues/21)


### 📦‍ Build System | 构建/工程依赖/工具

* **npm:** 更新 standard-version 和 sass 的依赖版本 ([be57e10](https://github.com/svchord/Rem-Craft/commit/be57e1074c679dfdf441d92692ae5aef97430f78))


### 🐛 Bug Fixes | Bug 修复

* 调整超级块横排间距 ([505018a](https://github.com/svchord/Rem-Craft/commit/505018aed68282cca9a922dfae8d9945e6bb6cd4))
* 修复顶栏最大化按钮样式问题 ([49982f4](https://github.com/svchord/Rem-Craft/commit/49982f4b2ef78a1d4b1397a6e944cc7e9145094d))
* 修复github链接图标显示问题 ([ae285b5](https://github.com/svchord/Rem-Craft/commit/ae285b5c4d84e0a5d4b3ed976319648a9b5e46c4))
* 修改块标按钮样式 ([2582286](https://github.com/svchord/Rem-Craft/commit/2582286274eb4a2709899a1eda42f6116d622266))


### ✏️ Documentation | 文档

* 更新Readme、preview.png、theme.json、package.json、样式文件目录说明 ([056e9b3](https://github.com/svchord/Rem-Craft/commit/056e9b34a4fd9861fb15be1c5346e2b3540df35c))

## 0.3.3(2022/4/16)

- 修复新UI的不兼容问题
- 修复顶栏VIP显示
- 修复右侧dock样式
- 修改mark样式
- 修改编辑器最小边距

## 0.3.2(2022/3/28)

- 去除导出预览页的超链接样式
- 修复菜单隐藏问题
- 修改滑条点击样式
- 修复顶栏同步按钮显示弹窗问题
- 修改文字颜色序列

## 0.3.1(2022/3/25)

- 修复引述块样式问题
- 修复二级菜单显示问题
- 修复题头图问题
- 修改文档标签样式
- 修改分割线样式

## 0.3.0(2022/3/23)

- 参考了Windows 11的设计，修改了主色、边栏、滑条、开关、输入框

## 0.2.2(2022/1/17)

- 工程化代码
- 参考[semi design](https://semi.design/zh-CN)的设计系统，统一了颜色、线条、圆角等变量
- 间距变量修改为适应屏幕宽度
- 修改通知栏、滑动条、开关等样式
- 搜索结果页面调整

## 0.2.1

- 整体配色方案小幅度修改
- 边窗上按钮位置调整
- 标签页栏样式调整
- 修复列表块问题
- 面包屑右侧按钮位置调整
- 集市Tab调整
- 设置菜单左侧Tab搜索后的样式调整
- 调整新版本的页签样式
- 修改加载页面的底色

## 0.2.0.1(2021/12/13)

- 整体配色方案更换
- 文档树样式调整
- 滚动条样式调整
- 修复大弹窗的下左右圆角
- 将标签面板中的输入栏与下列表对齐
- 将移动文档弹窗中的搜索框与下列表对齐

## 0.1.2-hotfix

 - 修复列表左侧竖线显示问题
 - 调整全屏状态下的<kbd>···</kbd>按钮位置
 - 去除`quote`字体

## 0.1.2

- 添加
  - 强调块、标签块、块引用、超链接及悬浮提示条的样式修改
  - 块标识按钮透明度降低
  - 行内公式块、行内代码块增量两侧边距
  - 集市tab、卡片、查看图片界面的样式修改
  - 将新增icon的代码提取出来
  - 待办列表完成后的样式
  - 增加块引用浮窗的显示动画
  - 调整菜单的高度
- 修复
  - 列表内代码块左侧无线条
  - 图片点击菜单的样式调整
  - 编辑器宽度添加最大值和最小值
  - 大纲页面仍然显示计数块的问题
  - 新版本顶部工具栏的样式修复

## 0.1.1

- 超链接浮窗重新更改为激进操作中的样式
- 横排超级块增加间隔，防止块标识按钮遮挡内容
- 大纲跳转问题修复
- 标题块样式修改
- 设置菜单中，快捷键设置输入框的底色修改
- 代码块上的按钮增加悬浮动画
- 编辑器宽度自适应屏幕，目前为46.9vw
- 代码块字号自适应和行距调整
- 工具条上提示条的位置调整