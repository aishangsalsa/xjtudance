# 爱尚salsa
这是西安交大爱尚salsa社交舞团的报名微信小程序。
包括萨友列表，萨友信息，报到和爱尚salsa介绍页。
## 更新日志
### 2017.09.05
* 更新 萨友列表页去除复制微信号到剪切板功能，添加复制手机号到剪切板功能
* 修复 部分报名项目没有写入数据库的问题，修改对应的兵马俑BBS报到帖、萨友信息页，这些项目包括：真实姓名，年级，身高，舞蹈水平，微信号
* 修复 部分页面上拉时卡顿并且屏幕顶部出现空白区域的问题
* 修复 导航栏等处颜色设置无效的问题，所有颜色改用rgb值设置
* 优化 页面布局及组件样式
* 优化 首页换成萨友列表
* 优化 报名页面所有input背景色改为白色
* 新增 后台从文件读取数据到数据库功能
### 2017.09.03
* 更新 首页改为salsainfo
* 更新 报名表去除年级、身高、微信号、舞蹈水平，增加姓名，手机号必填，调整萨友信息页对应内容
* 新增 一台后台服务器，一个域名
* 新增 自动选择可用域名功能，用于更换域名时
* 安全 修改apache服务器配置，禁止外部网络通过url访问Apache目录
* 修复 报到后无法自动跳转到萨友列表的问题。
* 优化 salsa介绍页背景色为white，与图片底色一致
### 2017.09.02
* 新增 十份说明文档。