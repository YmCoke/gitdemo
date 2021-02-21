# gitdemo

用于熟悉git指令

查阅资料时在前端瓶子君处找到一张git流程图, 非常详细, 可以说是看懂后git直接入门

![](./assets/git-process.jpg)

## 常用术语

Remote: 远程仓库
Repository: 本地仓库
stage/index: 暂存区/Git追踪树
workspace: 工作区(即平时修改文件后文件就都会被放到工作区上)

## 常用指令

### 常用操作篇

```git clone 地址```: 克隆master上最新的项目代码

```git add 文件名```: 将workspace中的文件提交到stage处

```git commit -m "提交信息"```: 将stage处的文件提交到repository（提交信息是可以不写的， 但**不推荐不写!**，提交信息可以在代码需要回退时提供信息说明）

```git push```: 将repository的文件提交到remote上

以上四条指令对应上图中的四个操作，也是平时开发中最常用到的四条指令
