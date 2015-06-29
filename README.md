##简介

使用 EL(易语言) 编写酷Q应用。

##文件说明

### SDK模块

`CQPAppSdk.ec` - 开发辅助模块，直接引入应用内即可

### 样例应用

`com.coxxs.demo.e` - 样例应用源代码，请编译为 com.coxxs.demo.dll，放置在酷Q的app目录下测试

`com.coxxs.demo.json`  - 样例应用的对应信息文件，包含应用的基础信息、事件列表等，请放置在酷Q的app目录下（用文本编辑器打开，复制到 next.cqp.cc/json 解析校验，无需使用的事件、菜单、权限请务必在此删除）

`com.coxxs.demo.e` - 正则样例应用源代码，使用正则来过滤、解析消息

`com.coxxs.demo.json` - 正则样例应用的对应信息文件，正则表达式在该文件内（同上）

`com.coxxs.status.e` - 酷Q自带的“状态监控”源代码，制作悬浮窗信息显示应用参考

`com.coxxs.status.json` - 状态监控的对应信息文件（同上）

### SDK模块源码
`CQPAppSdk.e` - 开发辅助模块源码，通常无需更改。（如要扩展功能，建议另写模块 或 在应用内扩展，避免Sdk模块更新时造成不便）

## 官方网站

主站：https://cqp.cc

文库：https://d.cqp.cc
