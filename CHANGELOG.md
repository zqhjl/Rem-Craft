# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

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