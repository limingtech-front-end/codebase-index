#limingtech 前端及nodeJs公共代码库索引

##建立目的##
提供前端及nodeJs代码库的索引服务，为代码包及文档提供索引支持

##层级划分基本原则##
###settings###
配置相关，例如全局css reset，全局环境变量配置等
###controllers###
逻辑控制类，多为抽离于具体功能的抽象封装，例如计数方法，数据状态控制方法等
###directives###
dom、bom相关操作封装，例如跨平台touch事件封装，滚动位置检测
###components###
复用性组件，例如搜索框，button控件，多为引用controllers及directives代码和组件相关样式及模板的组合
###utilities###
功能性方法，例如url参数截取，cookie操作等
###threeparties###
基于第三方类库，服务，API进行封装的以上类别及扩展类别相关代码 

##层级组织与命名规则方式##
为方便开发人员对于代码的引用与及自动化构建效率，远程代码库文件使用扁平化索引方式，不建立显示的目录层级（参照npm对依赖的管理方式），本地文件的组织方式依据个人喜好自行安排。
依据上文所述划分原则，命名方式以封装代码所属层级的首字母及其之后未被已有命名占用的第一个字母作为索引，
使用短横线与代码包名进行组合（子层级命名规则以此类推），具体参阅下文所述（*代表代码包名或子层级名称）
###settings###
se-*
###controllers###
co-*
###directives###
di-*
###components###
cm-*
###utilities###
ut-*
###threeparties###
th-*

##代码包（package）构建与引用指南##
###基础开发环境的选择###
为解决传统手动处理各种依赖所产生的代码重复加载、执行、引用混乱、版本不统一等问题，使用[NodeJs](https://nodejs.org/en/) + [npm包管理器](https://www.npmjs.com/)作为代码库的引用与构建基础，
npm提供了git协同支持，可以节省很多处理包管理器与代码仓库间的衔接问题，因此代码仓库基于git进行构建。
###开发环境安装###
* Git [git - 简易指南](http://www.bootcss.com/p/git-guide/)
* NodeJs + npm [官网下载安装很简单](https://nodejs.org/en/) ，速度慢的话可以在[淘宝npm镜像](https://npm.taobao.org/)下载对应安装包

###公共代码包的构建与引用###
构建与引用参阅[代码包构建与引用指南](https://github.com/limingtech-front-end/codebase-index/blob/master/documents/%E4%BB%A3%E7%A0%81%E5%8C%85%E6%9E%84%E5%BB%BA%E4%B8%8E%E5%BC%95%E7%94%A8%E6%8C%87%E5%8D%97.md)
编码规范参阅[编码规范](https://github.com/limingtech-front-end/codebase-index/blob/master/documents/%E7%BC%96%E7%A0%81%E8%A7%84%E8%8C%83.md)

##代码包索引##
###settings###
* [se-cssNormalize](https://github.com/limingtech-front-end/se-cssNormalize) 全局css样式reset

###controllers###
* [co-example](https://github.com/limingtech-front-end/co-example) 一个controller代码包封装示例

###directives###
* [di-example](https://github.com/limingtech-front-end/di-example) 一个directive代码包封装示例

###components###
* [cm-example](https://github.com/limingtech-front-end/cm-example) 一个component代码包封装示例

###utilities###
* [ut-example](https://github.com/limingtech-front-end/ut-example) 一个utility代码包封装示例

###threeparties###









