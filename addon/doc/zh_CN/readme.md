# Outlook 扩展 #

* 作者: Cyrille Bougot, Ralf Kefferpuetz
* NVDA兼容版本: 2018.3至2019.3
* 下载 [稳定版][1]
* 下载 [开发板][2]

此插件主要通过发出一些命令并添加额外的命令来改进Microsoft Outlook的使用体验。

## 命令

* Alt+1 到 Alt+9, Alt+0, Alt+-, Alt+=:
  在消息，日历项或任务窗口中朗读标题1到12。按两次，将焦点移动到此字段。按三次，则将其内容复制到剪贴板。
* NVDA+shift+I (台式机方按) / NVDA+control+shift+I (笔记本方按):
  案一次，朗读消息，日历项目或任务窗口中的信息栏。按两次，则将焦点移动到上述项目。按三次，则将其内容复制到剪贴板。
* NVDA+shift+A (台式机方按) / NVDA+control+shift+A (笔记本方案):
  在消息窗口中朗读附件的编号和名称。按两次，则将焦点移动到附件。
* NVDA+shift+M (台式机方案) / NVDA+shift+M (笔记本方案): 将焦点移动到邮件正文
* Control+Alt+左光标 和 Control+Alt+右光标: 分别在地址簿搜索结果列表，和当前所选的编辑框之间进行浏览
* Control+Q: 在消息列表中，将所选消息或消息组标记为已读
* Control+U: 在邮件列表中，将所选邮件或邮件组标记为未读

## 注意

可以在NVDA命令手势对话框中修改所有手势。您可能希望修改它们，尤其是在以下情况下：

* 将邮件标记为已读或未读的默认手势是Outlook英文版的手势。如果它们与Outlook本地版本不同，则必须相应地更改它们。
* 读取标题的默认手势对应于Alt与字母数字键盘第一行的键组合。如果它们与本地键盘布局不匹配，您可能需要重新映射读取标题11和12的手势。

## 更新日志

### 版本1.3

* 修复为较新的Office 365版本读取的邮件头。
* 更新以支持（兼容Python 2和3）
* 新增本地化。
* 现在使用appveyor进行发布

### 版本1.2

* 修复转发会议时标头读取。
* 新增本地化。

### 版本1.1

* 新增本地化。

### 版本1.0

* 发布初始版。

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=outlookextended

[2]: https://addons.nvda-project.org/files/get.php?file=outlookextended-dev
