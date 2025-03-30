# Trisolaris 项目演示网站

这是一个HTML演示网站，用于展示Trisolaris Web3卡牌抽卡游戏项目。该网站功能类似PowerPoint演示文稿，但以网页形式呈现，提供了更加丰富的交互体验。

## 项目结构

```
projects/2025-03/PPT/
├── index.html            # 主入口文件，使用iframe加载各幻灯片
├── images/               # 图片资源文件夹
│   ├── icon.svg          # 项目图标
│   ├── *.png             # 卡片和其他图像
│   └── *.jpg             # 其他图像
├── slides/               # 各个幻灯片HTML文件
│   ├── 1-cover.html      # 封面
│   ├── 2-overview.html   # 项目概述
│   ├── 3-requirements.html # 需求分析
│   ├── 4-architecture.html # 技术架构
│   ├── 5-gameplay.html   # 游戏流程
│   ├── 6-cards.html      # 卡牌展示
│   ├── 7-demo.html       # 项目演示
│   ├── 8-team.html       # 团队介绍
│   ├── 9-conclusion.html # 项目总结
│   ├── 10-thanks.html    # 鸣谢
│   └── slide-template.html # 幻灯片模板
└── README.md             # 项目说明文档
```

## 特性

- **响应式设计**：适配不同屏幕尺寸的设备
- **现代化UI**：使用TailwindCSS实现美观的界面
- **动画效果**：添加CSS动画提升视觉体验
- **交互功能**：
  - 左侧导航菜单（可隐藏/显示）
  - 键盘导航支持（左右方向键切换幻灯片）
  - 全屏显示功能
  - 幻灯片导航指示器

## 如何使用

1. 直接打开`index.html`文件即可启动演示网站
2. 使用左右方向键切换幻灯片
3. 点击右下角的全屏按钮进入全屏模式
4. 点击左上角的菜单按钮展开/收起导航菜单
5. 点击底部的导航指示器可直接跳转到对应幻灯片

## 技术栈

- **HTML5**：结构搭建
- **CSS3/TailwindCSS**：样式和响应式设计
- **JavaScript**：交互功能
- **FontAwesome**：图标

## 开发说明

如需修改或扩展演示内容：

1. 修改`index.html`中的`slides`数组添加新的幻灯片
2. 在`slides`目录中创建对应的HTML文件
3. 可使用`slide-template.html`作为新幻灯片的基础模板

## 关于Trisolaris项目

Trisolaris是一个基于Web3的游戏应用，用户通过Monad Testnet的测试代币支付抽卡，抽取三张无聊猿卡片。如果三张卡片相同，用户赢得测试代币奖励；否则，无奖励。

项目由四人团队在两小时内完成，展示了Web3技术在游戏领域的应用。

## 鸣谢

- HackathonWeekly（周周黑客松）
- OpenBuild
- 所有项目贡献者 