## 全局

- [x] 懒加载
- [x] 重构：context，单独放置在 context 文件夹内
- [ ] 添加回收站，所有删除的内容都会放置在回收站内
  - [ ] 回收站作为一个列表，可以撤回
  - [ ] 删除后跳转到父文件夹
- [ ] 添加 origin path，作为删除前的路径
- [ ] 启动应用后，添加 Splashscreen 应用启动动画
- [ ] 做类似于 windows 设置页面的动画
- [ ] 支持一些常见文件的读取工作
- [ ] 获取文件列表，以及文件的详细信息
- [ ] 左侧菜单添加一个在侧边栏打开，（例如可以，左侧显示 todo 右侧显示 markdown）
- [ ] 左侧菜单添加隐藏功能，只显示 icon，并且悬浮展示详情，此时禁止拖拽到子项内，只能最外层拖拽，通过悬浮窗的点击，进入文件内
- [ ] 同时作为 md 以及 jsonc 的文件编辑打开功能，如果符合格式，则展示对应内容
- [ ] 所有功能页面的模板功能
- [ ] 为 less-process 添加生命周期钩子（还没考虑好用途
- [ ] 在某个阶段，执行（menu-mounted，app-close）等？
- [ ] 如何使在 less-process 中进入回收站
- [ ] 添加删除时的询问，添加删除时移动到回收站或者是直接删除，或者是软件回收站
- [ ] 可以在新的窗口打开应用文件
- [ ] 左侧菜单拖拽到新的文件夹内
- [ ] 全局收集所有报错日志
- [ ] 点击工作页面，展开和收起工作区中的内容
- [ ] 工作区内有其它格式的文件时，使用系统对应打开方式打开
- [ ] 展示文件的详细信息
  - [ ] hover 文件夹 400 ms 后
  - [ ] folder 页面，点击 > 展开文件
- [ ] 页面之间切换的动画
- [ ] 检查是否有最新版本
- [ ] 所有颜色变量进行整理、分类
- [ ] 选中左侧菜单，然后 ctrl c + v
- [ ] 文件上次编辑时间信息的保存
- [ ] 配置页面中，添加对 markdown 的介绍
- [ ] 错误捕获
- [ ] 当前文件不存在，显示无法解析文件
- [ ] less-process 全局搜索功能
- [ ] 应用白屏时间有点长
- [ ] 点击左侧操作后，不应该进入文件内
  - [ ] 后端对错误内容进行保存
  - [ ] 管理端对错误内容进行展示

## 桌面图标

- [ ] 全局快捷键，globalShortcut（暂时用不上）
- [ ] 提供顶层输入框
- [ ] 添加桌面图层，查看当前的所有文件，可以对 todo 进行查看，可以win +d 显示桌面时候并且可以初始化桌面？

## Todo

Todo 要和 board 做区分，todo，可以更改布局为：左 list|右详情

- [ ] 添加一个每周，每月，每几个月自动生成的任务
- [ ] 优化 container 的拖拽
- [ ] todo 项中，如果文本为空，再点击删除，会删除当前 todo
- [ ] 单击编辑，移动超过 5px，则改为拖拽
- [ ] todo 排序，配置内容需要保存
- [ ] 可以展开收起子项的
- [ ] todo 解散方法异常
- [ ] 左侧添加一个周期待办事项
- [ ] 添加 todo 的详情视图，每个 todo 对应一个详情
- [ ] 为了减小 todo 文件的大小，属性为可选
- [ ] 为页面添加按住之后，横向滚动功能 <https://norserium.github.io/react-indiana-drag-scroll/>
- [ ] todo，拥有 todo 的专属看板，时间轴
- [ ] 看板，可以转换为 表格，时间轴
- [ ] 输入 # 后可在后面添加标签
- [ ] 可以设置统一模板，把便签的功能，做的更通用
- 框选功能，<https://www.joshuawootonn.com/react-drag-to-select>拖拽选择框进行选择

每月对所做的内容进行总结

## AI Chat

- [ ] 把聊天记录通过 JSON 保存在本地，而不是 localhost
- [x] 连接到 deepseek
- [ ] 连接到远程 ollama
- [ ] 昨天做了什么
- [ ] 笔记分块并嵌入到内部矢量数据库中
- [ ] 相关笔记通过向量相似度自动连接
- [ ] LLM 支持问答对笔记语料库进行RAG
- [ ] 一切都可以进行语义搜索

## Markdown

- [ ] 文件导出为 pdf，word 等
- [ ] 语言的切换功能优化
- [ ] 再次进入页面时恢复到上次元素的滚动位置
- [x] 添加用于测试的文件，用来测试 markdown 中的解析效果：image、代码块、js、css、html、python、表格、list、todo、list、标题 h1-h6、mark 标记、strong，强调
- [ ] 表格
  - [ ] 可以右键删除行，删除列，添加行，添加列
  - [ ] 可以对行列进行移动
- [ ] 图片，右键，选择定位
- [ ] 图片，可以更改图片链接
- [ ] 代码块，可点击复制

## 官网

- [ ] less-process-page 顶部要可以点击

## 看板

- [ ] 不同于 todo，详情属性为表格固定字段
- [ ] 可以转换为表格，时间轴
- [ ] 时间默认使用 number 保存


设置中，less-process 添加一个进阶模式，保存 json 数据时会添加换行以及前面追加两个空格

添加动画，在下一个页面没加载出来之前，暂时使用上一个页面的内容

参考 mozilla 声明，提供隐私声明 <https://www.mozilla.org/zh-CN/privacy/firefox/>

<https://andreaswilli.github.io/react-verification-input/>
验证码输入组件，可以改为 CDKey 输入组件




如果应用启用了离线模式，不会主动同步任何内容，完全作为本地 app 使用

如果有多人远程协作模式，那么任何更新都要以 json 的形式，展示详情（更新的内容，更新人，更新的行）

应用面向浏览器
Browserslist，支持的浏览器
targets: \[ 'chrome >0 and last 2.5 years', 'edge >0 and last 2.5 years', 'safari >0 and last 2.5 years', 'firefox >0 and last 2.5 years', 'and\_chr >0 and last 2.5 years', 'and\_ff >0 and last 2.5 years', 'ios >0 and last 2.5 years', ]

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

<https://uiverse.io/JaydipPrajapati1910/brave-rattlesnake-29>
这个按钮用于切换是否联网功能，默认所有功能都是不联网的

<https://daotin.netlify.app/tgru9q.html>
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

hamburger-react  菜单转换动画 ，未来添加上

imask.js 防止用户输入无效值。

拖拽功能的官方示例
<https://master--5fc05e08a4a65d0021ae0bf2.chromatic.com/?path=/story/presets-sortable-multiple-containers--many-items>

react-wrap-balancer 更好的换行工具

设置的配置是按照全局来的，各个文件的顺序，配置是按照对应文件的配置信息获取的

尝试使用分支来进行版本发布，探索这一步骤的自动化？

向右拉，可以划出 负一屏，里面添加了周期性工作，可以进行周期性工作的管理以及添加

1，提供几套固定模板
2，根据用户选择类型，生成主旨，根据逻辑提供汇报的结构所需文本
3，将文本插入模板内，提供数据
4，表格内容需转译

<https://linkify.js.org/>
将纯文本中的 URL、邮箱等转换为链接

把目录转换为可以添加多个标签，并且可以通过可视化以及标签进行查看

## markdown

turndown，将 html 转换为 markdown
