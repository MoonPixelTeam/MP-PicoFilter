
# 介绍
<div align="center">

![ICON](./Resources/ICON.ico)

## 一款图片筛选工具，当前版本：![GitHub Release](https://img.shields.io/github/v/release/ReGoMark/PicoFilter)

>[!CAUTION]
>本工具复刻自：https://github.com/ReGoMark/PicoFilter/tree/main
>当前分支版本的更新可能稍滞后于原始版本。

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/ReGoMark/PicoFilter.svg?style=for-the-badge" alt="license"></a>
<a href="https://github.com/ReGoMark/PicoFilter/commits/main">
    <img src="https://img.shields.io/github/last-commit/ReGoMark/PicoFilter?style=for-the-badge"></a>
<a href="https://github.com/ReGoMark/PicoFilter/stargazers">
    <img src="https://img.shields.io/github/stars/ReGoMark/PicoFilter.svg?style=for-the-badge" alt="stars"></a>
<a href="https://github.com/ReGoMark/PicoFilter/issues">
    <img src="https://img.shields.io/github/issues/ReGoMark/PicoFilter.svg?style=for-the-badge" alt="issues"></a>
    
</div>

支持常用图片格式如 `JPEG & JPG`，`PNG`，`GIF`，`ICO`，`BMP`，大约可以筛选4000张图像文件，加载时间取决于目录结构复杂程度和单文件的体积。


无论是界面设计还是运行平台均遵循标准的 Win32 设计规范，完全基于 `.net Framework` 的原生开发。除此之外，几乎肉眼可见的所有控件，都添加了工具提示，方便用户查看、使用。

>[!CAUTION]
>修复字体问题：安装 [方正黑体_GBK](./Fonts/方正黑体GBK.ttf)字体提升视觉效果体验。字体文件已经附在 [Fonts 文件夹](./Fonts) 中。
>
>修复缩放问题：右键单击“属性”，切换至“兼容性”选项卡，选择“更改高DPI设置”，启用“程序DPI”和“高DPI缩放替代”两个复选框。如果还是遇到了显示问题，请尝试修改部分设置。

  感谢开源社区的支持，没有开源社区就没有 PicoFilter 的诞生。

</div>

# 功能

1.指定格式筛选（支持`jpg`、`bmp`、`png`、`ico`和`gif`图像，自动加载到列表中）

2.指定分辨率筛选（`宽度`、`高度`，或者是大于设定值、等于设定值、排除设定值、小于设定值，交换宽高，甚至是交叉筛选）

3.一键统计（自动统计分析筛选结果，轻松查看占比等信息）

4.一键跳转（自动加载当前目录的文件夹结构，轻松跳转至上一级/下一级目录）

5.一键导出结果（导出筛选结果为`xlsx`文件，方便统计和比对）

6.一键整理（对筛选结果实现一键隔离、移动和复制、删除）

7.集成鼠标功能（如鼠标中键打开当前扫描文件夹，鼠标拖拽文件夹自动扫描、鼠标中键分配列表宽度、鼠标中键填充分辨率等）

8.标记识别（识别到包含“超时”“存疑”“无效”的文件名时自动标记）

9.右键菜单（支持快速筛选、快速调整工作列等功能）

10.排序和命名（支持字符串长度、序号、分辨率总和、大小、修改日期排序，排序完成后可以批量命名，支持序号、日期、月份命名规则）


更多细节欢迎下载体验！

# 截图

![QQ20250223-213313](https://github.com/user-attachments/assets/63103375-e2cc-413e-ad58-33b61976f7f8)
![](./Assets/398368099-8520cb3d-5ddc-4179-9ae2-a445a2dcc311.png)
![](./Assets/398368110-cbbfe498-ced8-48e8-a21b-b91a3915504d.png)
![](./Assets/398368119-d366e397-2426-42f3-9d34-bf639fe7771a.png)
![](./Assets/398368128-1a386175-ea09-49ae-8ae6-1ad620ec35ca.png)
![](./Assets/398368137-4a76b72a-e837-4c84-bc36-6739c3200c48.png)
![](./Assets/398368160-7b607b31-a668-4996-aad0-64ca21bc0898.png)

# 开发初衷
开发初衷是针对 PAA 像素艺术大赛中的尺寸不合规、格式不合规文件进行筛选，便于后续工作的开展。因为当前社区网站还未完全建立起来，选手的投稿作品都是通过第三方网站上传，我们的收集工作也是手工从网站内下载的。对于分辨率不合规的作品，在放大的时候可能会比较模糊；同样的，PNG和JPG格式的不同，也影响了放大或展示质量。

>[!NOTE]
>+“新增”；-“删去”；~“优化”；=“修正”
## 1.6
### 2025/2/28
=若干问题；
更多更新内容请查看提交记录。

### 2025/2/19-24
+操作提示

+右键菜单

=格式和分辨率叠加筛选修正

~优化加载速度和内存占用，变相提升了可加载文件数量

~UI设计，包括进度条显示等

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
