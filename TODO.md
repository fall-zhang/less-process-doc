## 全局

添加回收站，所有删除的内容都会放置在回收站内，
添加 origin path，作为删除前的路径

启动应用后，添加 Splashscreen 应用启动动画

做类似于 windows 设置页面的动画

支持一些常见文件的读取工作
获取文件列表，以及文件的详细信息

左侧菜单添加一个在侧边栏打开，（例如可以，左侧显示 todo 右侧显示 markdown）

左侧菜单添加隐藏功能，只显示 icon，并且悬浮展示详情，此时禁止拖拽到子项内，只能最外层拖拽，通过悬浮窗的点击，进入文件内

同时作为 md 以及 jsonc 的文件编辑打开功能，如果符合格式，则展示对应内容

懒加载：试试 setTimeout 之后，引入 JS 文件

所有功能页面的模板功能

为 less-process 添加生命周期钩子（还没考虑好用途
在某个阶段，执行（menu-mounted，app-close）等？

如何使在 less-process 中进入回收站
添加删除时的询问，添加删除时移动到回收站或者是直接删除，或者是软件回收站

## 桌面图层

全局快捷键，globalShortcut（暂时用不上）

提供顶层输入框

添加桌面图层，查看当前的所有文件，可以对 todo 进行查看，可以win +d 显示桌面时候并且可以初始化桌面？


## Todo

添加一个每周，每月，每几个月自动生成的任务

https://norserium.github.io/react-indiana-drag-scroll/
为页面添加按住之后，横向滚动功能

todo，拥有 todo 的专属看板，时间轴
看板，可以转换为 表格，时间轴

## AI Chat 

把聊天记录通过 JSON 保存在本地

无法连接到远程 ollama，起码要连接到 deepseek

- 笔记分块并嵌入到内部矢量数据库中
- 相关笔记通过向量相似度自动连接
- LLM 支持问答对笔记语料库进行RAG
- 一切都可以进行语义搜索

## Markdown

- 语言的切换功能

添加用于测试的文件，用来测试 markdown 中的解析效果

- 包括 image
- 代码块
  - js、css、html、python
- 表格
- list
- todo list
- 标题 h1-h6
- mark 标记
- strong，强调

## 官网

less-process-page 顶部要可以点击

可以在官网下载应用

## 后端

track backend，用户认证，错误追踪，用户反馈，这些内容是通用的，可以开源

配置、部署，运维、监控，事务控制，服务发现，弹性伸缩，灰度发布，高并发

restful API 好处，监视很容易，做各种统计分析，控制系统可以很容易做流量编排和调度
服务调用链追踪

软件的升级

对应用的下载量进行查看

















文件无法导入到对应的文件夹内，新建文件

context，单独放置在 context 文件夹内

设置中，less-process 添加一个进阶模式，保存 json 数据时会添加换行以及前面追加两个空格


添加动画，在下一个页面没加载出来之前，暂时使用上一个页面的内容

参考 mozilla 声明，提供隐私声明 https://www.mozilla.org/zh-CN/privacy/firefox/

https://andreaswilli.github.io/react-verification-input/
验证码输入组件，可以改为 CDKey 输入组件

应用白屏时间有点长

框选功能？
https://www.joshuawootonn.com/react-drag-to-select
拖拽选择框进行选择

可以设置统一模板，把便签的功能，做的更通用


如果应用启用了离线模式，不会主动同步任何内容，完全作为本地 app 使用

如果有多人远程协作模式，那么任何更新都要以 json 的形式，展示详情（更新的内容，更新人，更新的行）



应用面向浏览器
Browserslist，支持的浏览器
targets: [ 'chrome >0 and last 2.5 years', 'edge >0 and last 2.5 years', 'safari >0 and last 2.5 years', 'firefox >0 and last 2.5 years', 'and_chr >0 and last 2.5 years', 'and_ff >0 and last 2.5 years', 'ios >0 and last 2.5 years', ]

less-process 全局搜索功能
搜索的时候，按照 json 格式的语义搜索，还是按照文本格式搜索内容

scroll-behavior:smooth
顺滑地进行滚动

左侧除了编辑之外，给出一个详情，列出当前名称，icon 文件类型等内容，可以修改文件名称，文件的图标，文件的其它内容


进程中，A tauri app 是怎么回事，打包后如果还存在，如何删除或者修改

"explorer.fileNesting.enabled": true,
将相似的文件嵌套在一起

100 元内，转换为双倍时长，且当前的所有功能免费，基本存储空间（5G）
100-500，转换为双倍时长，且未来推出的新功能也全免费，超大存储空间（30G）
500-5k，独家群，内部新功能测试，领先一个 minor 版本，50G 存储空间
5k，以上所有，并且保留线上会员权利终身，可以提出自己的需求，并且添加特别鸣谢名单
多余 5k 的部分，全部转换为兑换码，还给用户，用户可以发送任何人解锁本地功能，让用户免费解锁体验

不同工作区默认不同的系列，icon，根据动物，蔬菜水果，进行分类，自动从中获取一个
左侧侧边栏可以只剩 icon ，悬浮展示详情，点击直接进入该文件内

点击 icon 选择 icon，点击文件夹展开并且进入，如何收起？再次点击文件夹？更改 icon？在外部更改

给用户一个打算多久后购买的弹窗，收集这类信息

https://uiverse.io/JaydipPrajapati1910/brave-rattlesnake-29
这个按钮用于切换是否联网功能，默认所有功能都是不联网的

https://daotin.netlify.app/tgru9q.html
Clipborad 相关可以复制粘贴语法

需要在 less-process 中使用 clipboard 粘贴板

dialog 用于打开原生文件夹

event 和应用后台、所有 tauri 的 windows 进行交互

http，用于请求，需要在scope中指定可以请求的地址
读取剪切板，并告知用户注意隐私泄露


存在线上资源，提醒用户开启网络功能



历史功能，可能配合上微软的 jsonc-parsor 更好用

@codaworks/react-glow
追踪高亮功能，添加到 less-process 官网中

sharedb，如果需要实时协作，那可能就需要sharedb


再次进入页面时恢复元素的滚动位置

hamburger-react  菜单转换动画 ，未来添加上

imask.js 防止用户输入无效值。

拖拽功能的官方示例
https://master--5fc05e08a4a65d0021ae0bf2.chromatic.com/?path=/story/presets-sortable-multiple-containers--many-items

react-wrap-balancer 更好的换行工具

设置的配置是按照全局来的，各个文件的顺序，配置是按照对应文件的配置信息获取的

尝试使用分支来进行版本发布，探索这一步骤的自动化？


向右拉，可以划出 负一屏，里面添加了周期性工作，可以进行周期性工作的管理以及添加


1，提供几套固定模板
2，根据用户选择类型，生成主旨，根据逻辑提供汇报的结构所需文本
3，将文本插入模板内，提供数据
4，表格内容需转译


https://linkify.js.org/
将纯文本中的 URL、邮箱等转换为链接

把目录转换为可以添加多个标签，并且可以通过可视化以及标签进行查看

## markdown

turndown，将 html 转换为 markdown
