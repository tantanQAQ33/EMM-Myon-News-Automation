# EMM-Myon-News-Automation
EMMのMyon 网站のNews自动化工具
# Myon 自动化工具

自动登录 Myon 网站，随机选择 11-13 篇新闻(虽然都是前面的新闻就是了，就是你刚加载页面前面加载的那些新闻而已，后面是去不到的)，每篇自动答题、提交、停留 6-8 分钟。

## 功能特性

- 自动登录 Myon 网站
- 随机选择 11-13 篇新闻
- 自动答题（随机选择选项）
- 自动提交答案
- 每篇停留 6-8 分钟
- 完成后弹出系统通知
- 记住上次输入的账号密码

## 使用方法

### 方式一：直接下载 exe（推荐）

1. 前往 [Releases](https://github.com/你的用户名/你的仓库名/releases) 页面
2. 下载 `Myon自动化.exe`
3. 双击运行，按提示输入账号密码

### 方式二：从源码运行

1. 克隆仓库
2. 安装依赖：
   ```bash
   pip install -r requirements.txt
   playwright install msedge

3.运行脚本：
   python myon_automation.py

注意事项
   需要 Windows 10/11 系统
   需要安装 Edge 浏览器
   运行时请勿操作电脑
   
那个 AUTOMA 是我一开始写这个脚本之前用的那个插件，在那写。如果你知道怎么用的话，你可以自己去看一下，大概怎么做的。流程都差不多，反正流程就在那里，你自己看一眼
自己导入一下，看看就可以了
