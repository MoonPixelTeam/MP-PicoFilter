# 介绍
![QQ20241224-163948](https://github.com/user-attachments/assets/90dc8a1c-ee80-4ff8-b503-1d46d53d0a1a)
 一款图片筛选工具，支持常用图片格式如 JPEG & JPG，PNG，GIF，ICO，BMP，对于中等文件数目的文件夹是可用。
 
 当前版本分支为：1.5(fix4) 正式版；1.5 comp 兼容模式版本。
 ## 特性
![QQ20241224-162915](https://github.com/user-attachments/assets/8520cb3d-5ddc-4179-9ae2-a445a2dcc311)
![QQ20241224-162944](https://github.com/user-attachments/assets/cbbfe498-ced8-48e8-a21b-b91a3915504d)
![QQ20241224-163010](https://github.com/user-attachments/assets/d366e397-2426-42f3-9d34-bf639fe7771a)
![QQ20241224-163055](https://github.com/user-attachments/assets/1a386175-ea09-49ae-8ae6-1ad620ec35ca)
![QQ20241224-163215](https://github.com/user-attachments/assets/4a76b72a-e837-4c84-bc36-6739c3200c48)
![QQ20241224-163215](https://github.com/user-attachments/assets/c7a590aa-90a4-499f-af90-b6945ff1430d)
![QQ20241224-163338](https://github.com/user-attachments/assets/7b607b31-a668-4996-aad0-64ca21bc0898)
![QQ20241224-164020](https://github.com/user-attachments/assets/e8d2e040-04c7-4289-8d05-bcbd4e720468)

无论是界面设计还是允许平台，均遵循标准的 Win32 设计规范，完全基于 .net Framework 的原生开发。

除此之外，几乎肉眼可见的所有控件，都添加了工具提示，方便用户查看、使用。

另外集成了一些鼠标功能（例如中键、双击等），提升用户体验。

推荐安装方正黑体GBK、Consola、微软雅黑字体提升视觉效果体验。

感谢开源社区软件的支持。没有开源社区就没有PicoFilter的诞生。

## 备注
 由于开发之初采用了强制125缩放比例，导致其他人在使用时产生了显示错误。所以在今后的Release中我会发布两个版本，带comp后缀(格式为7z)的即为100缩放正常显示版本，默认命名的(.zip)为125缩放版本。
 
 开发者本人是强迫症患者，所以在软件排版布局上也有些考究。对于功能上，在两个列表之间，按下鼠标中键可以平均分配尺寸。
 
 其他的一些细微功能我都放到工具提示里面了，只要鼠标悬停就可以看得到，如在“×”位置鼠标左键双击可以自动输入宽度值。所以使用时要细心观察呐！
# 开发初衷
 开发初衷是针对 PAA 像素艺术大赛中的尺寸不合规、格式不合规文件进行筛选，便于后续工作的开展。因为当前社区网站还未完全建立起来，选手的投稿作品都是通过第三方网站上传，我们的收集工作也是手工从网站内下载的。对于分辨率不合规的作品，在放大的时候可能会比较模糊；同样的，PNG和JPG格式的不同，也影响了放大或展示质量。希望有一天我们的社区网站能够建成，我的软件使命也就结束了~
# 更新日志
说明： +“新增”；-“删去”；~“优化”；=“修正”
## 1.5 
### 2024/12/23
+统计信息显示

~底部标签显示

+标题栏当前文件夹显示

+标题栏当前文件夹大小显示
### 2024/12/21
+忽略方向筛选

=导出表格内容

## 1.4
### 2024/12/18
~导出表格数据内容

~UI设计

+列表简易搜索功能

=按键绑定

### 2024/12/17
~UI设计

=表格导出

~结果显示

=显示错误问题

### 2024/11/26
~UI设计

+累计更新，版本号修正

~结果显示

=修改标题栏文本，

+标题栏项目扫描进度显示

### 2024/11/13
~UI设计

## 1.3
### 2024/9/28
+鼠标中键打开文件夹功能

+排除分辨率筛选

+全选按钮

+复选功能

+文件总数工具提示

+适配最大化窗口

+分隔条，自由调整两侧尺寸

=若干bug

## 1.2
### 2024/9/27
=配色方案

=图标

-对cur、ani的支持

### 2024/9/26
+对ico、bmp格式支持

+导出为xlsx功能

+调整：

+UI微调整

+对部分按钮增加了按键绑定
