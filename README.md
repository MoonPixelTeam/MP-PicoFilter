>[!CAUTION]
>注意本项目已从原有组织迁移到该公共仓库，原有版本不再提供，只提供当前版本.

# 介绍
<div align="center">

![ICON](./Resources/ICON.ico)

## 一款图片筛选工具，当前版本：![GitHub Release](https://img.shields.io/github/v/release/ReGoMark/PicoFilter)

</div>

支持常用图片格式如 `JPEG & JPG`，`PNG`，`GIF`，`ICO`，`BMP`，对于中等文件数目的文件夹可用(大约3000张2.5MB的图像)。

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/ReGoMark/PicoFilter.svg?style=for-the-badge" alt="license"></a>
<a href="https://github.com/ReGoMark/PicoFilter/commits/main">
    <img src="https://img.shields.io/github/last-commit/ReGoMark/PicoFilter?style=for-the-badge"></a>
<a href="https://github.com/ReGoMark/PicoFilter/stargazers">
    <img src="https://img.shields.io/github/stars/ReGoMark/PicoFilter.svg?style=for-the-badge" alt="stars"></a>
<a href="https://github.com/ReGoMark/PicoFilter/issues">
    <img src="https://img.shields.io/github/issues/ReGoMark/PicoFilter.svg?style=for-the-badge" alt="issues"></a>

</div>

# 功能(1.6特性未展示，见更新日志)

无论是界面设计还是运行平台均遵循标准的 Win32 设计规范，完全基于 `.net Framework` 的原生开发。

除此之外，几乎肉眼可见的所有控件，都添加了工具提示，方便用户查看、使用。

集成了一些鼠标功能（例如`中键`、`双击`等），提升用户体验。

>[!CAUTION]
>推荐安装 [方正黑体_GBK](./Fonts/方正黑体GBK.ttf)、[Consola](./Fonts/Consola.ttf)、[等线](./Fonts/灯线.ttf)、`微软雅黑`字体提升视觉效果体验。字体文件已经附在 [Fonts 文件夹](./Fonts) 中。

感谢开源社区的支持，没有开源社区就没有 PicoFilter 的诞生。

## 截图

![总览图](./Assets/410770485-23cd403a-5f84-451b-bc5c-34a73283ede7.png "总览图")
![](./Assets/398368099-8520cb3d-5ddc-4179-9ae2-a445a2dcc311.png)
![](./Assets/398368110-cbbfe498-ced8-48e8-a21b-b91a3915504d.png)
![](./Assets/398368119-d366e397-2426-42f3-9d34-bf639fe7771a.png)
![](./Assets/398368128-1a386175-ea09-49ae-8ae6-1ad620ec35ca.png)
![](./Assets/398368137-4a76b72a-e837-4c84-bc36-6739c3200c48.png)
![](./Assets/398368160-7b607b31-a668-4996-aad0-64ca21bc0898.png)

### 备注

 
>本人是强迫症患者，所以在软件排版布局上也有些考究。在两个列表之间，按下鼠标中键可以平均分配尺寸。其他的一些细微功能我都放到工具提示里面了，只要鼠标悬停就可以看得到，如在“×”位置鼠标左键双击可以自动输入宽度值。所以使用时要细心观察呐！   

>由于水平一般、能力有限，软件可能会存在内存泄漏、回收不充分的问题，不过不影响使用。
 
# 开发初衷
开发初衷是针对 PAA 像素艺术大赛中的尺寸不合规、格式不合规文件进行筛选，便于后续工作的开展。因为当前社区网站还未完全建立起来，选手的投稿作品都是通过第三方网站上传，我们的收集工作也是手工从网站内下载的。对于分辨率不合规的作品，在放大的时候可能会比较模糊；同样的，PNG和JPG格式的不同，也影响了放大或展示质量。

# 更新日志
>[!WARNING]
>由于转移仓库，Git Commit 记录已经丢失，更新日志仅供参考

>[!NOTE]
>+“新增”；-“删去”；~“优化”；=“修正”
## 1.6
### 2025/2/7
+目录结构预览

=修正若干错误

~统计结果显示

-按键绑定支持

~关于窗口

~代码运行效率

+重载功能

~UI排版设计

+叠层菜单

## 1.5 
### 2024/12/23
+统计信息显示

~底部标签显示

+标题栏当前文件夹显示

+标题栏当前文件夹大小显示

=UI设计

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
