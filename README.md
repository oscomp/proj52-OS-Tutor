# proj52-OS-Tutor
### 项目名称
应用助手

### 项目描述
openEuler的基本管理单位是rpm包。openEuler含有很多包（以及很多可额外安装的包），每个包又含有很多命令、配置文件等，每个命令的功能各异、用法也不相同，这成为学习使用openEuler的较大障碍。
用户在具备最基本的OS知识后，需要一个从所需功能到所用具体命令的一个桥梁。

项目的目标是开发一个新的工具，在接收到用户给出的几个关键字后，返回可能相关的命令及其它进一步的相关帮助信息。
【相当于在一个主机范围内的搜索引擎】

### 所属赛道

2025全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

张旭舟

* email zhangxuzhou4@huawei.com



### 难度

中等



### 特征
* 收集已知的rpm包，收集其中的命令、配置文件等，建立知识库；

* 基于用户给出的关键字进行搜索，返回匹配的命令、配置文件及其简要描述，结果可按匹配度排序；

* 知识库可与工具包集成，也可分离，以便于支持随时升级；

* (plus) 建立rpm包的一种规范扩展，在各rpm包制作时就提供相关的索引信息，以自动配合此工具提供从“所需功能”到“所用命令”的搜索。【类似于论文中的key words】

* (plus) 建立一种机制，以让用户参与知识库的构建和维护；



### 文档
无

### License

Mulan PSL v1



## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

* 基本目标：返回用户所给关键字所对应的相关命令、配置文件及其简介；

* 扩展目标：实现用户评价、用户提供内容的功能，从而让用户参与知识库的维护。 

