# Mobamas复现&汉化流程

#### 复现

下载并解压Mobamas数据包, 点击文件夹内的`start_server.exe`.

将打开一个可以进行偶像数据浏览及翻译工作的网页.

#### 台词翻译

点击网页首页的"**翻译工作台**"

在"译文"表格, 输入翻译后的文本. 翻译完成后, 点击"**保存到本地**".

使用右上角的"**导出**", 可以把译文和原文导出为json和markdown对照表. 也可以把导出的对照表通过"**导入**"更新到网页.

**原文**是从`idols/[idol_name]/[idol_name]_data.json`读取的;
**译文**是从`idols/[idol_name]/[idol_name]_data_translated.json`读取/保存的.

译文拥有**自动保存功能**, 如果忘记保存, 可以从`unsaved/[idol_name]_unsaved.json`找回, 通过"导入"功能将其更新到网页.