# NewEmoji  93个组件演示，支持emoji，支持易语言/火山/C#/Python

> 口径说明：本文档以 Python 为准，易语言/火山/C# 同样可做到一样的效果
>
> 非Webui，非Webui，非Webui，重要的事情说三遍
>
> 视频演示：https://www.bilibili.com/video/BV17XLP67Euu/

- 开源仓库多语言接入矩阵

![开源仓库多语言接入矩阵](https://img.msblog.cc/img/image-20260518153427688.png)

## 目录

- [基础布局](#基础布局)（17 个）
- [表单输入](#表单输入)（15 个）
- [选择媒体](#选择媒体)（14 个）
- [数据展示](#数据展示)（17 个）
- [图表导航](#图表导航)（14 个）
- [反馈流程](#反馈流程)（16 个）

> `new_emoji` 是一个 Windows 原生 UI DLL，已提供易语言、Python ctypes、C# 对象式封装
>
> 开源仓库：https://github.com/mosheng20205/new-emoji
>
> 还提供商业版可视化设计器，一键导出易语言、C#
>
> QQ交流群：464558635

## 基础布局

面板、容器、区域、间距和基础视觉元素，适合快速理解单 HWND + D2D 的布局风格。

Python gallery 原始说明：面板、容器、区域、间距和基础视觉元素，适合快速理解单 HWND + D2D 的布局风格。

### 01. 🧱 面板 (Panel)

**功能简介：**
面板容器

**状态/版本：** 已完成 | **创建导出：** `EU_CreatePanel` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式
![深色模式](https://img.msblog.cc/img/image-20260518155500823.png)

#### 浅色模式

![浅色模式](https://img.msblog.cc/img/image-20260518155545910.png)

</details>

---

### 02. 🚀 按钮 (Button)

**功能简介：**
按钮交互

**状态/版本：** 已完成 | **创建导出：** `EU_CreateButton` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![深色模式](https://img.msblog.cc/img/image-20260518155832275.png)

#### 浅色模式
![浅色模式](https://img.msblog.cc/img/image-20260518155915091.png)

</details>

---

### 03. 💡 信息框 (InfoBox)

**功能简介：**
信息提示

**状态/版本：** 已完成 | **创建导出：** `EU_CreateInfoBox` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式
![深色模式](https://img.msblog.cc/img/image-20260518162706187.png)

#### 浅色模式
![浅色模式](https://img.msblog.cc/img/image-20260518162715012.png)



</details>

---

### 04. 🔤 文本 (Text)

**功能简介：**
文本渲染

**状态/版本：** 已完成 | **创建导出：** `EU_CreateText` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>
<br>

#### 深色模式
![深色模式](https://img.msblog.cc/img/image-20260518162818062.png)

#### 浅色模式
![浅色模式](https://img.msblog.cc/img/image-20260518162828027.png)

</details>

---

### 05. 🔗 链接 (Link)

**功能简介：**
链接状态

**状态/版本：** 已完成 | **创建导出：** `EU_CreateLink` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![深色模式](https://img.msblog.cc/img/image-20260518162944200.png)

#### 浅色模式

![浅色模式](https://img.msblog.cc/img/image-20260518162951592.png)

</details>

---

### 06. ⭐ 图标 (Icon)

**功能简介：**
图标/emoji

**状态/版本：** 已完成 | **创建导出：** `EU_CreateIcon` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![深色模式](https://img.msblog.cc/img/image-20260518163053603.png)

#### 浅色模式

![浅色模式](https://img.msblog.cc/img/image-20260518163101330.png)

</details>

---

### 07. ↔️ 间距 (Space)

**功能简介：**
占位间距

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSpace` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![深色模式](https://img.msblog.cc/img/image-20260518163254269.png)

#### 浅色模式

![浅色模式](https://img.msblog.cc/img/image-20260518163307013.png)

</details>

---

### 08. 📦 容器套件 (Container)

**功能简介：**
内容容器

**状态/版本：** 已完成 | **创建导出：** `EU_CreateContainer` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>
<br>

#### 深色模式

![深色模式](https://img.msblog.cc/img/image-20260518163409219.png)

#### 浅色模式

![浅色模式](https://img.msblog.cc/img/image-20260518163421961.png)

</details>

---

### 09. 📌 顶栏 (Header)

**功能简介：**
顶栏容器

**状态/版本：** 已完成 | **创建导出：** `EU_CreateHeader` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>
<br>

#### 深色模式

![深色模式](https://img.msblog.cc/img/image-20260518163516314.png)

#### 浅色模式

![浅色模式](https://img.msblog.cc/img/image-20260518163523972.png)

</details>

---

### 10. 🧭 侧边栏 (Aside)

**功能简介：**
侧边栏容器

**状态/版本：** 已完成 | **创建导出：** `EU_CreateAside` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![image-20260518163631424](https://img.msblog.cc/img/image-20260518163631424.png)

#### 浅色模式

![image-20260518163639037](https://img.msblog.cc/img/image-20260518163639037.png)

</details>

---

### 11. 📄 主要区域 (Main)

**功能简介：**
主要区域容器

**状态/版本：** 已完成 | **创建导出：** `EU_CreateMain` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>
<br>

#### 深色模式

![image-20260518163726624](https://img.msblog.cc/img/image-20260518163726624.png)

#### 浅色模式

![image-20260518163734670](https://img.msblog.cc/img/image-20260518163734670.png)

</details>

---

### 12. ✅ 底栏 (Footer)

**功能简介：**
底栏容器

**状态/版本：** 已完成 | **创建导出：** `EU_CreateFooter` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>
<br>

#### 深色模式

![image-20260518163833779](https://img.msblog.cc/img/image-20260518163833779.png)

#### 浅色模式

![image-20260518163845196](https://img.msblog.cc/img/image-20260518163845196.png)

</details>

---

### 13. 🧭 布局 (Layout)

**功能简介：**
自动布局

**状态/版本：** 已完成 | **创建导出：** `EU_CreateLayout` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![image-20260518163928572](https://img.msblog.cc/img/image-20260518163928572.png)

#### 浅色模式

![image-20260518163936982](https://img.msblog.cc/img/image-20260518163936982.png)


</details>

---

### 14. ▣ 边框 (Border)

**功能简介：**
边框区域

**状态/版本：** 已完成 | **创建导出：** `EU_CreateBorder` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![image-20260518164026347](https://img.msblog.cc/img/image-20260518164026347.png)

#### 浅色模式

![image-20260518164040110](https://img.msblog.cc/img/image-20260518164040110.png)


</details>

---

### 15. ➖ 分割线 (Divider)

**功能简介：**
分割线

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDivider` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![image-20260518164130333](https://img.msblog.cc/img/image-20260518164130333.png)


#### 浅色模式

![image-20260518164138312](https://img.msblog.cc/img/image-20260518164138312.png)

</details>

---

### 16. 📌 固钉 (Affix)

**功能简介：**
固钉区域

**状态/版本：** 已完成 | **创建导出：** `EU_CreateAffix` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![image-20260518164219760](https://img.msblog.cc/img/image-20260518164219760.png)

#### 浅色模式

![image-20260518164229002](https://img.msblog.cc/img/image-20260518164229002.png)

</details>

---

### 17. 💧 水印 (Watermark)

**功能简介：**
水印背景

**状态/版本：** 已完成 | **创建导出：** `EU_CreateWatermark` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 深色模式

![image-20260518164303584](https://img.msblog.cc/img/image-20260518164303584.png)

#### 浅色模式

![image-20260518164311622](https://img.msblog.cc/img/image-20260518164311622.png)


</details>

---

## 表单输入

输入、选择、评分和候选建议组件，重点展示键鼠交互与状态读回能力。

Python gallery 原始说明：输入、选择、评分和候选建议组件，重点展示键鼠交互与状态读回能力。

### 18. ☑️ 复选框 (Checkbox)

**功能简介：**
复选框

**状态/版本：** 已完成 | **创建导出：** `EU_CreateCheckbox` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 深色模式
![image-20260518164642246](https://img.msblog.cc/img/image-20260518164642246.png)

#### 点击/悬停状态
![image-20260518164659084](https://img.msblog.cc/img/image-20260518164659084.png)

#### 浅色模式
![image-20260518164713567](https://img.msblog.cc/img/image-20260518164713567.png)

</details>

---

### 19. 🔘 单选框 (Radio)

**功能简介：**
单选项

**状态/版本：** 已完成 | **创建导出：** `EU_CreateRadio` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518164754134](https://img.msblog.cc/img/image-20260518164754134.png)

#### 点击/悬停状态
![image-20260518164816097](https://img.msblog.cc/img/image-20260518164816097.png)

#### 浅色模式
![image-20260518164836793](https://img.msblog.cc/img/image-20260518164836793.png)

</details>

---

### 20. 🎚️ 开关 (Switch)

**功能简介：**
开关

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSwitch` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518164848664](https://img.msblog.cc/img/image-20260518164848664.png)

#### 点击/悬停状态
![image-20260518164908825](https://img.msblog.cc/img/image-20260518164908825.png)

#### 浅色模式
![image-20260518164921442](https://img.msblog.cc/img/image-20260518164921442.png)

</details>

---

### 21. 🎛️ 滑块 (Slider)

**功能简介：**
滑块

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSlider` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165008415](https://img.msblog.cc/img/image-20260518165008415.png)

#### 点击/悬停状态
![image-20260518165031508](https://img.msblog.cc/img/image-20260518165031508.png)

#### 浅色模式
![image-20260518165052798](https://img.msblog.cc/img/image-20260518165052798.png)

</details>

---

### 22. 🔢 数字输入框 (InputNumber)

**功能简介：**
数字输入

**状态/版本：** 已完成 | **创建导出：** `EU_CreateInputNumber` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165109970](https://img.msblog.cc/img/image-20260518165109970.png)

#### 点击/悬停状态
![image-20260518165129865](https://img.msblog.cc/img/image-20260518165129865.png)

#### 浅色模式
![image-20260518165143218](https://img.msblog.cc/img/image-20260518165143218.png)

</details>

---

### 23. ⌨️ 输入框 (Input)

**功能简介：**
增强输入

**状态/版本：** 已完成 | **创建导出：** `EU_CreateInput` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165210212](https://img.msblog.cc/img/image-20260518165210212.png)

#### 点击/悬停状态
![image-20260518165225739](https://img.msblog.cc/img/image-20260518165225739.png)

#### 浅色模式
![image-20260518165237275](https://img.msblog.cc/img/image-20260518165237275.png)

</details>

---

### 24. 🏷️ 标签输入 (InputTag)

**功能简介：**
标签输入

**状态/版本：** 已完成 | **创建导出：** `EU_CreateInputTag` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165301585](https://img.msblog.cc/img/image-20260518165301585.png)

#### 点击/悬停状态
![image-20260518165322005](https://img.msblog.cc/img/image-20260518165322005.png)

#### 浅色模式
![image-20260518165348117](https://img.msblog.cc/img/image-20260518165348117.png)

</details>

---

### 25. 📋 选择器 (Select)

**功能简介：**
下拉选择

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSelect` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165425731](https://img.msblog.cc/img/image-20260518165425731.png)

#### 点击/悬停状态
![image-20260518165439633](https://img.msblog.cc/img/image-20260518165439633.png)

#### 浅色模式
![image-20260518165454727](https://img.msblog.cc/img/image-20260518165454727.png)

</details>

---

### 26. 🧾 虚拟选择器 (SelectV2)

**功能简介：**
虚拟选择

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSelectV2` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165542396](https://img.msblog.cc/img/image-20260518165542396.png)

#### 点击/悬停状态
![image-20260518165524546](https://img.msblog.cc/img/image-20260518165524546.png)

#### 浅色模式
![image-20260518165553861](https://img.msblog.cc/img/image-20260518165553861.png)

</details>

---

### 27. ⭐ 评分 (Rate)

**功能简介：**
评分

**状态/版本：** 已完成 | **创建导出：** `EU_CreateRate` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165611947](https://img.msblog.cc/img/image-20260518165611947.png)

#### 点击/悬停状态
![image-20260518165649141](https://img.msblog.cc/img/image-20260518165649141.png)

#### 浅色模式
![image-20260518165708209](https://img.msblog.cc/img/image-20260518165708209.png)

</details>

---

### 28. 🎨 颜色选择器 (ColorPicker)

**功能简介：**
颜色选择

**状态/版本：** 已完成 | **创建导出：** `EU_CreateColorPicker` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165753469](https://img.msblog.cc/img/image-20260518165753469.png)

#### 点击/悬停状态
![image-20260518165727475](https://img.msblog.cc/img/image-20260518165727475.png)

#### 浅色模式
![image-20260518165739677](https://img.msblog.cc/img/image-20260518165739677.png)

</details>

---

### 29. 🔎 自动补全 (Autocomplete)

**功能简介：**
自动完成

**状态/版本：** 已完成 | **创建导出：** `EU_CreateAutocomplete` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518165923082](https://img.msblog.cc/img/image-20260518165923082.png)

#### 点击/悬停状态
![image-20260518165912231](https://img.msblog.cc/img/image-20260518165912231.png)

#### 浅色模式
![image-20260518165933219](https://img.msblog.cc/img/image-20260518165933219.png)

</details>

---

### 30. @ 提及 (Mentions)

**功能简介：**
提及输入

**状态/版本：** 已完成 | **创建导出：** `EU_CreateMentions` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170007635](https://img.msblog.cc/img/image-20260518170007635.png)

#### 点击/悬停状态
![image-20260518165949371](https://img.msblog.cc/img/image-20260518165949371.png)

#### 浅色模式
![image-20260518170021156](https://img.msblog.cc/img/image-20260518170021156.png)

</details>

---

### 31. 🧭 级联选择 (Cascader)

**功能简介：**
级联选择

**状态/版本：** 已完成 | **创建导出：** `EU_CreateCascader` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170042687](https://img.msblog.cc/img/image-20260518170042687.png)

#### 点击/悬停状态
![image-20260518170104447](https://img.msblog.cc/img/image-20260518170104447.png)

#### 浅色模式
![image-20260518170118820](https://img.msblog.cc/img/image-20260518170118820.png)

</details>

---

### 32. 🔗 组合输入 (InputGroup)

**功能简介：**
组合输入

**状态/版本：** 已完成 | **创建导出：** `EU_CreateInputGroup` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170150933](https://img.msblog.cc/img/image-20260518170150933.png)

#### 点击/悬停状态
![image-20260518170220750](https://img.msblog.cc/img/image-20260518170220750.png)

#### 浅色模式
![image-20260518170231341](https://img.msblog.cc/img/image-20260518170231341.png)

</details>

---

## 选择媒体

日期时间、树形选择、穿梭框、上传、图片和轮播等较完整的业务组件。

Python gallery 原始说明：日期时间、树形选择、穿梭框、上传、图片和轮播等较完整的业务组件。

### 33. 📅 日历 (Calendar)

**功能简介：**
日历全样式

**状态/版本：** 已完成 | **创建导出：** `EU_CreateCalendar` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170410514](https://img.msblog.cc/img/image-20260518170410514.png)

#### 点击/悬停状态
![image-20260518170425404](https://img.msblog.cc/img/image-20260518170425404.png)

#### 浅色模式
![image-20260518170436889](https://img.msblog.cc/img/image-20260518170436889.png)

</details>

---

### 34. 🌳 树 (Tree)

**功能简介：**
树组件

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTree` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>
<br>

#### 正常状态
![image-20260518170459190](https://img.msblog.cc/img/image-20260518170459190.png)

#### 点击/悬停状态
![image-20260518170519978](https://img.msblog.cc/img/image-20260518170519978.png)

#### 浅色模式
![image-20260518170531783](https://img.msblog.cc/img/image-20260518170531783.png)

</details>

---

### 35. 🌲 树选择 (TreeSelect)

**功能简介：**
树选择

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTreeSelect` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170610072](https://img.msblog.cc/img/image-20260518170610072.png)

#### 点击/悬停状态
![image-20260518170549711](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20260518170549711.png)

#### 浅色模式
![image-20260518170629255](https://img.msblog.cc/img/image-20260518170629255.png)

</details>

---

### 36. 🔁 穿梭框 (Transfer)

**功能简介：**
穿梭框

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTransfer` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170646534](https://img.msblog.cc/img/image-20260518170646534.png)

#### 点击/悬停状态
![image-20260518170730247](https://img.msblog.cc/img/image-20260518170730247.png)

#### 浅色模式
![image-20260518170743925](https://img.msblog.cc/img/image-20260518170743925.png)

</details>

---

### 37. 📆 日期选择器 (DatePicker)

**功能简介：**
日期选择

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDatePicker` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170802269](https://img.msblog.cc/img/image-20260518170802269.png)

#### 点击/悬停状态
![image-20260518170819464](https://img.msblog.cc/img/image-20260518170819464.png)

#### 浅色模式
![image-20260518170830904](https://img.msblog.cc/img/image-20260518170830904.png)

</details>

---

### 38. 📅 日期范围选择器 (DateRangePicker)

**功能简介：**
日期范围

**状态/版本：** Gallery 演示项 | **创建导出：** `EU_CreateDatePicker + EU_SetDatePickerRangeSelect` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518170917562](https://img.msblog.cc/img/image-20260518170917562.png)

#### 点击/悬停状态
![image-20260518170938144](https://img.msblog.cc/img/image-20260518170938144.png)

#### 浅色模式
![image-20260518171010327](https://img.msblog.cc/img/image-20260518171010327.png)

</details>

---

### 39. 🕐 时间范围 (TimeRange)

**功能简介：**
时间范围

**状态/版本：** Gallery 演示项 | **创建导出：** `EU_CreateTimePicker + EU_SetTimePickerRangeSelect` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171044459](https://img.msblog.cc/img/image-20260518171044459.png)

#### 点击/悬停状态
![image-20260518171101492](https://img.msblog.cc/img/image-20260518171101492.png)

#### 浅色模式
![image-20260518171115240](https://img.msblog.cc/img/image-20260518171115240.png)

</details>

---

### 40. 🗓️ 日期时间范围 (DateTimeRange)

**功能简介：**
日期时间范围

**状态/版本：** Gallery 演示项 | **创建导出：** `EU_CreateDateTimePicker + EU_SetDateTimePickerRangeSelect` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171132608](https://img.msblog.cc/img/image-20260518171132608.png)

#### 点击/悬停状态
![image-20260518171143340](https://img.msblog.cc/img/image-20260518171143340.png)

#### 浅色模式
![image-20260518171200156](https://img.msblog.cc/img/image-20260518171200156.png)

</details>

---

### 41. ⏰ 时间选择器 (TimePicker)

**功能简介：**
时间选择

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTimePicker` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171214063](https://img.msblog.cc/img/image-20260518171214063.png)

#### 点击/悬停状态
![image-20260518171225382](https://img.msblog.cc/img/image-20260518171225382.png)

#### 浅色模式
![image-20260518171239277](https://img.msblog.cc/img/image-20260518171239277.png)

</details>

---

### 42. 🗓️ 日期时间选择器 (DateTimePicker)

**功能简介：**
日期时间

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDateTimePicker` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171253397](https://img.msblog.cc/img/image-20260518171253397.png)

#### 点击/悬停状态
![image-20260518171305137](https://img.msblog.cc/img/image-20260518171305137.png)

#### 浅色模式
![image-20260518171330694](https://img.msblog.cc/img/image-20260518171330694.png)

</details>

---

### 43. 🕘 时间选择 (TimeSelect)

**功能简介：**
时间候选

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTimeSelect` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171343229](https://img.msblog.cc/img/image-20260518171343229.png)

#### 点击/悬停状态
![image-20260518171356736](https://img.msblog.cc/img/image-20260518171356736.png)

#### 浅色模式
![image-20260518171419120](https://img.msblog.cc/img/image-20260518171419120.png)

</details>

---

### 44. 📤 上传 (Upload)

**功能简介：**
上传入口

**状态/版本：** 已完成 | **创建导出：** `EU_CreateUpload` 

<details>
<summary><b>📸 点击查看 UI 截图 (共4张)</b></summary>

<br>

#### 正常状态
![image-20260518171432601](https://img.msblog.cc/img/image-20260518171432601.png)

#### 点击/悬停状态
![image-20260518171510811](https://img.msblog.cc/img/image-20260518171510811.png)

![image-20260518171521368](https://img.msblog.cc/img/image-20260518171521368.png)

#### 
![image-20260518171541189](https://img.msblog.cc/img/image-20260518171541189.png)

</details>

---

### 45. 🖼️ 图片 (Image)

**功能简介：**
纯图片、边框、无边框、占位、懒加载、远程和预览列表

**状态/版本：** 已完成 | **创建导出：** `EU_CreateImage` 

<details>
<summary><b>📸 点击查看 UI 截图 (共7张)</b></summary>

<br>

#### 正常状态
![image-20260518171615716](https://img.msblog.cc/img/image-20260518171615716.png)

![image-20260518171629774](https://img.msblog.cc/img/image-20260518171629774.png)

![image-20260518171636140](https://img.msblog.cc/img/image-20260518171636140.png)

![image-20260518171642769](https://img.msblog.cc/img/image-20260518171642769.png)

![image-20260518171648751](https://img.msblog.cc/img/image-20260518171648751.png)

#### 点击/悬停状态
![image-20260518171700064](https://img.msblog.cc/img/image-20260518171700064.png)

#### 浅色模式
![image-20260518171714733](https://img.msblog.cc/img/image-20260518171714733.png)

</details>

---

### 46. 🎠 轮播 (Carousel)

**功能简介：**
轮播

**状态/版本：** 已完成 | **创建导出：** `EU_CreateCarousel` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171742044](https://img.msblog.cc/img/image-20260518171742044.png)

#### 点击/悬停状态
![image-20260518171756679](https://img.msblog.cc/img/image-20260518171756679.png)

#### 浅色模式
![image-20260518171817656](https://img.msblog.cc/img/image-20260518171817656.png)

</details>

---

## 数据展示

状态、卡片、表格、统计指标和加载占位，适合后台工具与业务系统。

Python gallery 原始说明：状态、卡片、表格、统计指标和加载占位，适合后台工具与业务系统。

### 47. 🏷️ 标签 (Tag)

**功能简介：**
标签

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTag` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171838258](https://img.msblog.cc/img/image-20260518171838258.png)

#### 点击/悬停状态
![image-20260518171910495](https://img.msblog.cc/img/image-20260518171910495.png)

#### 浅色模式
![image-20260518171925924](https://img.msblog.cc/img/image-20260518171925924.png)

</details>

---

### 48. 🔴 徽标 (Badge)

**功能简介：**
徽标

**状态/版本：** 已完成 | **创建导出：** `EU_CreateBadge` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518171939918](https://img.msblog.cc/img/image-20260518171939918.png)

#### 点击/悬停状态
![image-20260518171955782](https://img.msblog.cc/img/image-20260518171955782.png)

#### 浅色模式
![image-20260518172007167](https://img.msblog.cc/img/image-20260518172007167.png)

</details>

---

### 49. 📈 进度条 (Progress)

**功能简介：**
进度条

**状态/版本：** 已完成 | **创建导出：** `EU_CreateProgress` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>
<br>

#### 正常状态
![image-20260518172024250](https://img.msblog.cc/img/image-20260518172024250.png)

#### 点击/悬停状态
![image-20260518172044457](https://img.msblog.cc/img/image-20260518172044457.png)

#### 浅色模式
![image-20260518172053358](https://img.msblog.cc/img/image-20260518172053358.png)

</details>

---

### 50. 😀 头像 (Avatar)

**功能简介：**
头像

**状态/版本：** 已完成 | **创建导出：** `EU_CreateAvatar` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 正常状态
![image-20260518172108658](https://img.msblog.cc/img/image-20260518172108658.png)


#### 浅色模式
![image-20260518172129329](https://img.msblog.cc/img/image-20260518172129329.png)

</details>

---

### 51. 📭 空状态 (Empty)

**功能简介：**
空状态

**状态/版本：** 已完成 | **创建导出：** `EU_CreateEmpty` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518172150726](https://img.msblog.cc/img/image-20260518172150726.png)

#### 点击/悬停状态
![image-20260518172217363](https://img.msblog.cc/img/image-20260518172217363.png)

#### 浅色模式
![image-20260518172230459](https://img.msblog.cc/img/image-20260518172230459.png)

</details>

---

### 52. 💀 骨架屏 (Skeleton)

**功能简介：**
骨架屏

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSkeleton` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518172242698](https://img.msblog.cc/img/image-20260518172242698.png)

#### 点击/悬停状态
![image-20260518172256496](https://img.msblog.cc/img/image-20260518172256496.png)

#### 浅色模式
![image-20260518172308775](https://img.msblog.cc/img/image-20260518172308775.png)

</details>

---

### 53. 📋 描述列表 (Descriptions)

**功能简介：**
描述列表

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDescriptions` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518172324112](https://img.msblog.cc/img/image-20260518172324112.png)

#### 点击/悬停状态
![image-20260518172344803](https://img.msblog.cc/img/image-20260518172344803.png)

#### 浅色模式
![image-20260518172355124](https://img.msblog.cc/img/image-20260518172355124.png)

</details>

---

### 54. 📊 表格 (Table)

**功能简介：**
表格

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTable` 

<details>
<summary><b>📸 点击查看 UI 截图 (共9张)</b></summary>

<br>

#### 正常状态
![image-20260518172410031](https://img.msblog.cc/img/image-20260518172410031.png)

![image-20260518172417811](https://img.msblog.cc/img/image-20260518172417811.png)

![image-20260518172430992](https://img.msblog.cc/img/image-20260518172430992.png)

![image-20260518172445972](https://img.msblog.cc/img/image-20260518172445972.png)

![image-20260518172506279](https://img.msblog.cc/img/image-20260518172506279.png)

![image-20260518172522360](https://img.msblog.cc/img/image-20260518172522360.png)

![image-20260518172536521](https://img.msblog.cc/img/image-20260518172536521.png)

#### 点击/悬停状态
![image-20260518172558453](https://img.msblog.cc/img/image-20260518172558453.png)

#### 浅色模式
![image-20260518172615761](https://img.msblog.cc/img/image-20260518172615761.png)

</details>

---

### 55. 📋 列表框 (ListBox)

**功能简介：**
列表框

**状态/版本：** 已完成 | **创建导出：** `EU_CreateListBox` 

<details>
<summary><b>📸 点击查看 UI 截图 (共7张)</b></summary>

<br>

#### 正常状态
![image-20260518172651846](https://img.msblog.cc/img/image-20260518172651846.png)

![image-20260518172658004](https://img.msblog.cc/img/image-20260518172658004.png)

![image-20260518172703637](https://img.msblog.cc/img/image-20260518172703637.png)

![image-20260518172711590](https://img.msblog.cc/img/image-20260518172711590.png)

![image-20260518172717619](https://img.msblog.cc/img/image-20260518172717619.png)

#### 点击/悬停状态
![image-20260518172744751](https://img.msblog.cc/img/image-20260518172744751.png)

#### 浅色模式
![image-20260518172755816](https://img.msblog.cc/img/image-20260518172755816.png)

</details>

---

### 56. ♾️ 无限滚动 (InfiniteScroll)

**功能简介：**
无限滚动

**状态/版本：** 已完成 | **创建导出：** `EU_CreateInfiniteScroll` 

<details>
<summary><b>📸 点击查看 UI 截图 (共6张)</b></summary>

<br>

#### 正常状态
![image-20260518172823157](https://img.msblog.cc/img/image-20260518172823157.png)

![image-20260518172830370](https://img.msblog.cc/img/image-20260518172830370.png)

![image-20260518172836158](https://img.msblog.cc/img/image-20260518172836158.png)

![image-20260518172842088](https://img.msblog.cc/img/image-20260518172842088.png)

#### 点击/悬停状态
![image-20260518172905389](https://img.msblog.cc/img/image-20260518172905389.png)

#### 浅色模式
![image-20260518172914051](https://img.msblog.cc/img/image-20260518172914051.png)

</details>

---

### 57. 💳 卡片 (Card)

**功能简介：**
基础、列表、图片和插槽卡片

**状态/版本：** 已完成 | **创建导出：** `EU_CreateCard` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518172937387](https://img.msblog.cc/img/image-20260518172937387.png)

#### 点击图片放大
![image-20260518172957094](https://img.msblog.cc/img/image-20260518172957094.png)

#### 浅色模式
![image-20260518173016640](https://img.msblog.cc/img/image-20260518173016640.png)

</details>

---

### 58. 📂 折叠面板 (Collapse)

**功能简介：**
折叠面板

**状态/版本：** 已完成 | **创建导出：** `EU_CreateCollapse` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518173412474](https://img.msblog.cc/img/image-20260518173412474.png)

#### 点击/悬停状态
![image-20260518173442414](https://img.msblog.cc/img/image-20260518173442414.png)

#### 浅色模式
![image-20260518173452205](https://img.msblog.cc/img/image-20260518173452205.png)

</details>

---

### 59. 🕒 时间线 (Timeline)

**功能简介：**
时间线

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTimeline` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>
<br>

#### 正常状态
![image-20260518173656965](https://img.msblog.cc/img/image-20260518173656965.png)

![image-20260518173645115](https://img.msblog.cc/img/image-20260518173645115.png)

![image-20260518173622548](https://img.msblog.cc/img/image-20260518173622548.png)

![image-20260518173628873](https://img.msblog.cc/img/image-20260518173628873.png)

#### 点击/悬停状态
![image-20260518173715160](https://img.msblog.cc/img/image-20260518173715160.png)

#### 浅色模式
![image-20260518173725869](https://img.msblog.cc/img/image-20260518173725869.png)

</details>

---

### 60. 📌 统计数值 (Statistic)

**功能简介：**
统计数值

**状态/版本：** 已完成 | **创建导出：** `EU_CreateStatistic` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518173803463](https://img.msblog.cc/img/image-20260518173803463.png)

#### 点击/悬停状态
![image-20260518173819679](https://img.msblog.cc/img/image-20260518173819679.png)

#### 浅色模式
![image-20260518173828329](https://img.msblog.cc/img/image-20260518173828329.png)

</details>

---

### 61. 🎯 指标卡 (KPI Card)

**功能简介：**
指标卡

**状态/版本：** Gallery 演示项 | **创建导出：** `EU_CreateKpiCard` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518173841861](https://img.msblog.cc/img/image-20260518173841861.png)

#### 点击/悬停状态
![image-20260518173858511](https://img.msblog.cc/img/image-20260518173858511.png)

#### 浅色模式
![image-20260518173907964](https://img.msblog.cc/img/image-20260518173907964.png)

</details>

---

### 62. 📈 趋势 (Trend)

**功能简介：**
趋势

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTrend` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518173927541](https://img.msblog.cc/img/image-20260518173927541.png)

#### 点击/悬停状态
![image-20260518173947235](https://img.msblog.cc/img/image-20260518173947235.png)

#### 浅色模式
![image-20260518173959494](https://img.msblog.cc/img/image-20260518173959494.png)

</details>

---

### 63. 🟢 状态点 (StatusDot)

**功能简介：**
状态点

**状态/版本：** 已完成 | **创建导出：** `EU_CreateStatusDot` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518174016284](https://img.msblog.cc/img/image-20260518174016284.png)

#### 点击/悬停状态
![image-20260518174050681](https://img.msblog.cc/img/image-20260518174050681.png)

#### 浅色模式
![image-20260518174101762](https://img.msblog.cc/img/image-20260518174101762.png)

</details>

---

## 图表导航

图表、菜单、锚点、页头和标签页，展示复杂信息组织能力。

Python gallery 原始说明：图表、菜单、锚点、页头和标签页，展示复杂信息组织能力。

### 64. 🎯 仪表盘 (Gauge)

**功能简介：**
仪表盘

**状态/版本：** 已完成 | **创建导出：** `EU_CreateGauge` 

<details>
<summary><b>📸 点击查看 UI 截图 (共2张)</b></summary>

<br>

#### 正常状态
![image-20260518174207094](https://img.msblog.cc/img/image-20260518174207094.png)

#### 浅色模式
![image-20260518174219945](https://img.msblog.cc/img/image-20260518174219945.png)

</details>

---

### 65. ⭕ 环形进度 (RingProgress)

**功能简介：**
环形进度

**状态/版本：** 已完成 | **创建导出：** `EU_CreateRingProgress` 

<details>
<summary><b>📸 点击查看 UI 截图 (共5张)</b></summary>

<br>

#### 正常状态
![image-20260518174400930](https://img.msblog.cc/img/image-20260518174400930.png)

#### 点击/悬停状态
![image-20260518174424692](https://img.msblog.cc/img/image-20260518174424692.png)

![image-20260518174431760](https://img.msblog.cc/img/image-20260518174431760.png)

![image-20260518174442176](https://img.msblog.cc/img/image-20260518174442176.png)

#### 浅色模式
![image-20260518174513740](https://img.msblog.cc/img/image-20260518174513740.png)

</details>

---

### 66. 🧭 子弹进度 (BulletProgress)

**功能简介：**
子弹进度

**状态/版本：** 已完成 | **创建导出：** `EU_CreateBulletProgress` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518174539234](https://img.msblog.cc/img/image-20260518174539234.png)

#### 点击/悬停状态
![image-20260518174553193](https://img.msblog.cc/img/image-20260518174553193.png)

#### 浅色模式
![image-20260518174602924](https://img.msblog.cc/img/image-20260518174602924.png)

</details>

---

### 67. 📈 折线图 (LineChart)

**功能简介：**
折线图

**状态/版本：** 已完成 | **创建导出：** `EU_CreateLineChart` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518174634836](https://img.msblog.cc/img/image-20260518174634836.png)

#### 点击/悬停状态
![image-20260518174646616](https://img.msblog.cc/img/image-20260518174646616.png)

#### 浅色模式
![image-20260518174658143](https://img.msblog.cc/img/image-20260518174658143.png)

</details>

---

### 68. 📊 柱状图 (BarChart)

**功能简介：**
柱状图

**状态/版本：** 已完成 | **创建导出：** `EU_CreateBarChart` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518174854417](https://img.msblog.cc/img/image-20260518174854417.png)

#### 点击/悬停状态
![image-20260518175000754](https://img.msblog.cc/img/image-20260518175000754.png)

#### 浅色模式
![image-20260518175014774](https://img.msblog.cc/img/image-20260518175014774.png)

</details>

---

### 69. 🍩 环形图 (DonutChart)

**功能简介：**
环形图

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDonutChart` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518175028540](https://img.msblog.cc/img/image-20260518175028540.png)

#### 点击/悬停状态
![image-20260518175048314](https://img.msblog.cc/img/image-20260518175048314.png)

#### 浅色模式
![image-20260518175057641](https://img.msblog.cc/img/image-20260518175057641.png)

</details>

---

### 70. 📂 下拉菜单 (Dropdown)

**功能简介：**
下拉菜单

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDropdown` 

<details>
<summary><b>📸 点击查看 UI 截图 (共7张)</b></summary>

<br>

#### 正常状态
![image-20260518175113920](https://img.msblog.cc/img/image-20260518175113920.png)

![image-20260518175120533](https://img.msblog.cc/img/image-20260518175120533.png)

![image-20260518175126520](https://img.msblog.cc/img/image-20260518175126520.png)

![image-20260518175132015](https://img.msblog.cc/img/image-20260518175132015.png)

![image-20260518175138712](https://img.msblog.cc/img/image-20260518175138712.png)

#### 点击/悬停状态
![image-20260518175159631](https://img.msblog.cc/img/image-20260518175159631.png)

#### 浅色模式
![image-20260518175213234](https://img.msblog.cc/img/image-20260518175213234.png)

</details>

---

### 71. 🧭 菜单 (Menu)

**功能简介：**
菜单

**状态/版本：** 已完成 | **创建导出：** `EU_CreateMenu` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518175242982](https://img.msblog.cc/img/image-20260518175242982.png)

![image-20260518175249637](https://img.msblog.cc/img/image-20260518175249637.png)

![image-20260518175256065](https://img.msblog.cc/img/image-20260518175256065.png)

#### 点击/悬停状态
![image-20260518175328870](https://img.msblog.cc/img/image-20260518175328870.png)

#### 浅色模式
![image-20260518175339402](https://img.msblog.cc/img/image-20260518175339402.png)

</details>

---

### 72. ⚓ 锚点 (Anchor)

**功能简介：**
锚点

**状态/版本：** 已完成 | **创建导出：** `EU_CreateAnchor` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518175358829](https://img.msblog.cc/img/image-20260518175358829.png)

#### 点击/悬停状态
![image-20260518175425827](https://img.msblog.cc/img/image-20260518175425827.png)

#### 浅色模式
![image-20260518175440545](https://img.msblog.cc/img/image-20260518175440545.png)

</details>

---

### 73. ⬆️ 回到顶部 (Backtop)

**功能简介：**
返回顶部

**状态/版本：** 已完成 | **创建导出：** `EU_CreateBacktop` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>
<br>

#### 正常状态
![image-20260518175514579](https://img.msblog.cc/img/image-20260518175514579.png)

#### 点击/悬停状态
![image-20260518175539163](https://img.msblog.cc/img/image-20260518175539163.png)

#### 浅色模式
![image-20260518175548272](https://img.msblog.cc/img/image-20260518175548272.png)

</details>

---

### 74. 🔀 分段控制器 (Segmented)

**功能简介：**
分段控制

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSegmented` 

<details>
<summary><b>📸 点击查看 UI 截图 (共5张)</b></summary>

<br>

#### 正常状态
![image-20260518175602040](https://img.msblog.cc/img/image-20260518175602040.png)

![image-20260518175608765](https://img.msblog.cc/img/image-20260518175608765.png)

![image-20260518175614602](https://img.msblog.cc/img/image-20260518175614602.png)

#### 点击/悬停状态
![image-20260518175634523](https://img.msblog.cc/img/image-20260518175634523.png)

#### 浅色模式
![image-20260518175643082](https://img.msblog.cc/img/image-20260518175643082.png)

</details>

---

### 75. 📄 页头 (PageHeader)

**功能简介：**
页头

**状态/版本：** 已完成 | **创建导出：** `EU_CreatePageHeader` 

<details>
<summary><b>📸 点击查看 UI 截图 (共5张)</b></summary>

<br>

#### 正常状态
![image-20260518175707552](https://img.msblog.cc/img/image-20260518175707552.png)

![image-20260518175713503](https://img.msblog.cc/img/image-20260518175713503.png)

![image-20260518175719318](https://img.msblog.cc/img/image-20260518175719318.png)

#### 点击/悬停状态
![image-20260518175748701](https://img.msblog.cc/img/image-20260518175748701.png)

#### 浅色模式
![image-20260518175759615](https://img.msblog.cc/img/image-20260518175759615.png)

</details>

---

### 76. 🍞 面包屑 (Breadcrumb)

**功能简介：**
面包屑

**状态/版本：** 已完成 | **创建导出：** `EU_CreateBreadcrumb` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518175814501](https://img.msblog.cc/img/image-20260518175814501.png)

#### 点击/悬停状态
![image-20260518175841280](https://img.msblog.cc/img/image-20260518175841280.png)

#### 浅色模式
![image-20260518175850495](https://img.msblog.cc/img/image-20260518175850495.png)

</details>

---

### 77. 📑 标签页 (Tabs)

**功能简介：**
标签页

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTabs` 

<details>
<summary><b>📸 点击查看 UI 截图 (共6张)</b></summary>

<br>

#### 正常状态
![image-20260518175906884](https://img.msblog.cc/img/image-20260518175906884.png)

![image-20260518175913193](https://img.msblog.cc/img/image-20260518175913193.png)

![image-20260518175918957](https://img.msblog.cc/img/image-20260518175918957.png)

![image-20260518175945943](https://img.msblog.cc/img/image-20260518175945943.png)

#### 点击/悬停状态
![image-20260518175959992](https://img.msblog.cc/img/image-20260518175959992.png)

#### 浅色模式
![image-20260518180012377](https://img.msblog.cc/img/image-20260518180012377.png)

</details>

---

## 反馈流程

提示、弹层、确认、引导、分页和步骤条，覆盖常见业务反馈流程。

Python gallery 原始说明：提示、弹层、确认、引导、分页和步骤条，覆盖常见业务反馈流程。

### 78. 📚 分页 (Pagination)

**功能简介：**
分页

**状态/版本：** 已完成 | **创建导出：** `EU_CreatePagination` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180045403](https://img.msblog.cc/img/image-20260518180045403.png)

#### 点击/悬停状态

![image-20260518180108439](https://img.msblog.cc/img/image-20260518180108439.png)

#### 浅色模式
![image-20260518180118801](https://img.msblog.cc/img/image-20260518180118801.png)

</details>

---

### 79. 👣 步骤条 (Steps)

**功能简介：**
步骤条全样式

**状态/版本：** 已完成 | **创建导出：** `EU_CreateSteps` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180130856](https://img.msblog.cc/img/image-20260518180130856.png)

#### 点击/悬停状态
![image-20260518180157244](https://img.msblog.cc/img/image-20260518180157244.png)

#### 浅色模式
![image-20260518180207948](https://img.msblog.cc/img/image-20260518180207948.png)

</details>

---

### 80. 🚨 警告提示 (Alert)

**功能简介：**
警告提示

**状态/版本：** 已完成 | **创建导出：** `EU_CreateAlert / EU_CreateAlertEx` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180225168](https://img.msblog.cc/img/image-20260518180225168.png)

#### 点击/悬停状态
![image-20260518180241586](https://img.msblog.cc/img/image-20260518180241586.png)

#### 浅色模式
![image-20260518180251469](https://img.msblog.cc/img/image-20260518180251469.png)

</details>

---

### 81. ✅ 结果页 (Result)

**功能简介：**
结果页

**状态/版本：** 已完成 | **创建导出：** `EU_CreateResult` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180309064](https://img.msblog.cc/img/image-20260518180309064.png)

#### 点击/悬停状态
![image-20260518180329709](https://img.msblog.cc/img/image-20260518180329709.png)

#### 浅色模式
![image-20260518180338647](https://img.msblog.cc/img/image-20260518180338647.png)

</details>

---

### 82. 💬 消息提示 (Message)

**功能简介：**
消息提示

**状态/版本：** 已完成 | **创建导出：** `EU_ShowMessage` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180414704](https://img.msblog.cc/img/image-20260518180414704.png)

#### 点击/悬停状态
![image-20260518180404170](https://img.msblog.cc/img/image-20260518180404170.png)

#### 浅色模式
![image-20260518180426771](https://img.msblog.cc/img/image-20260518180426771.png)

</details>

---

### 83. 📬 消息框 (MessageBox)

**功能简介：**
消息框

**状态/版本：** 已完成 | **创建导出：** `EU_ShowMessageBoxEx` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180443480](https://img.msblog.cc/img/image-20260518180443480.png)

#### 点击/悬停状态
![image-20260518180453888](https://img.msblog.cc/img/image-20260518180453888.png)

#### 浅色模式
![image-20260518180504828](https://img.msblog.cc/img/image-20260518180504828.png)

</details>

---

### 84. 🔔 通知 (Notification)

**功能简介：**
通知

**状态/版本：** 已完成 | **创建导出：** `EU_CreateNotification` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180521525](https://img.msblog.cc/img/image-20260518180521525.png)

#### 点击/悬停状态
![image-20260518180531260](https://img.msblog.cc/img/image-20260518180531260.png)

#### 浅色模式
![image-20260518180541133](https://img.msblog.cc/img/image-20260518180541133.png)

</details>

---

### 85. ⏳ 加载 (Loading)

**功能简介：**
加载

**状态/版本：** 已完成 | **创建导出：** `EU_CreateLoading` 

<details>
<summary><b>📸 点击查看 UI 截图 (共4张)</b></summary>

<br>

#### 正常状态
![image-20260518180557823](https://img.msblog.cc/img/image-20260518180557823.png)

#### 点击/悬停状态
![image-20260518180610025](https://img.msblog.cc/img/image-20260518180610025.png)

![image-20260518180625027](https://img.msblog.cc/img/image-20260518180625027.png)

#### 浅色模式
![image-20260518180654569](https://img.msblog.cc/img/image-20260518180654569.png)

</details>

---

### 86. 💬 对话框 (Dialog)

**功能简介：**
对话框

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDialog` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518180714874](https://img.msblog.cc/img/image-20260518180714874.png)

#### 点击/悬停状态
![image-20260518180726964](https://img.msblog.cc/img/image-20260518180726964.png)

#### 浅色模式
![image-20260518180740197](https://img.msblog.cc/img/image-20260518180740197.png)

</details>

---

### 87. 📚 抽屉 (Drawer)

**功能简介：**
抽屉

**状态/版本：** 已完成 | **创建导出：** `EU_CreateDrawer` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518181022435](https://img.msblog.cc/img/image-20260518181022435.png)

#### 点击/悬停状态
![image-20260518181032904](https://img.msblog.cc/img/image-20260518181032904.png)

![image-20260518181040431](https://img.msblog.cc/img/image-20260518181040431.png)

![image-20260518181048610](https://img.msblog.cc/img/image-20260518181048610.png)

![image-20260518181056920](https://img.msblog.cc/img/image-20260518181056920.png)

![image-20260518181104855](https://img.msblog.cc/img/image-20260518181104855.png)

![image-20260518181118288](https://img.msblog.cc/img/image-20260518181118288.png)

![image-20260518181243173](https://img.msblog.cc/img/image-20260518181243173.png)

![image-20260518181130293](https://img.msblog.cc/img/image-20260518181130293.png)

![image-20260518181140456](https://img.msblog.cc/img/image-20260518181140456.png)

![image-20260518181218389](https://img.msblog.cc/img/image-20260518181218389.png)



#### 浅色模式
![image-20260518181310422](https://img.msblog.cc/img/image-20260518181310422.png)

</details>

---

### 88. 💭 文字提示 (Tooltip)

**功能简介：**
文字提示

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTooltip` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![正常状态](./images/component-gallery/tooltip-normal.png)

#### 点击/悬停状态
![交互状态](./images/component-gallery/tooltip-hover.png)

#### 
![异常状态](./images/component-gallery/tooltip-error.png)

</details>

---

### 89. 🗯️ 弹出框 (Popover)

**功能简介：**
气泡卡片

**状态/版本：** 已完成 | **创建导出：** `EU_CreatePopover` 

<details>
<summary><b>📸 点击查看 UI 截图 (共4张)</b></summary>

<br>

#### 正常状态
![image-20260518181329415](https://img.msblog.cc/img/image-20260518181329415.png)

#### 点击/悬停状态
![image-20260518181354881](https://img.msblog.cc/img/image-20260518181354881.png)

![image-20260518181405467](https://img.msblog.cc/img/image-20260518181405467.png)

#### 浅色模式
![image-20260518181424828](https://img.msblog.cc/img/image-20260518181424828.png)

</details>

---

### 90. 💭 气泡卡片 (ElementPopover)

**功能简介：**
反馈流程.气泡卡片

**状态/版本：** Gallery 演示项 | **创建导出：** `ElementPopover` 

<details>
<summary><b>📸 点击查看 UI 截图 (共8张)</b></summary>

<br>

#### 正常状态
![image-20260518181442702](https://img.msblog.cc/img/image-20260518181442702.png)

#### 点击/悬停状态
![image-20260518181505699](https://img.msblog.cc/img/image-20260518181505699.png)

![image-20260518181511338](https://img.msblog.cc/img/image-20260518181511338.png)

![image-20260518181517262](https://img.msblog.cc/img/image-20260518181517262.png)

![image-20260518181526038](https://img.msblog.cc/img/image-20260518181526038.png)

![image-20260518181532189](https://img.msblog.cc/img/image-20260518181532189.png)

![image-20260518181540339](https://img.msblog.cc/img/image-20260518181540339.png)

#### 浅色模式
![image-20260518181552695](https://img.msblog.cc/img/image-20260518181552695.png)

</details>
---
### 91.💬元素弹层 (Popup)
**功能简介：**
右键弹层绑定
**状态/版本：** 已完成 | **创建导出：** `EU_SetElementPopup` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>
<br>

#### 正常状态

![image-20260518182347146](https://img.msblog.cc/img/image-20260518182347146.png)

#### 点击/悬停状态

![image-20260518182355233](https://img.msblog.cc/img/image-20260518182355233.png)

![image-20260518182403019](https://img.msblog.cc/img/image-20260518182403019.png)

![image-20260518182408800](https://img.msblog.cc/img/image-20260518182408800.png)

#### 浅色模式

![image-20260518182420556](https://img.msblog.cc/img/image-20260518182420556.png)


</details>
---


### 92. ❓ 气泡确认框 (Popconfirm)

**功能简介：**
确认气泡

**状态/版本：** 已完成 | **创建导出：** `EU_CreatePopconfirm` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态

![image-20260518181653018](https://img.msblog.cc/img/image-20260518181653018.png)

#### 点击/悬停状态
![image-20260518181706063](https://img.msblog.cc/img/image-20260518181706063.png)

![image-20260518181713755](https://img.msblog.cc/img/image-20260518181713755.png)

![image-20260518182443128](https://img.msblog.cc/img/image-20260518182443128.png)

![image-20260518182449324](https://img.msblog.cc/img/image-20260518182449324.png)

#### 浅色模式
![image-20260518182508935](https://img.msblog.cc/img/image-20260518182508935.png)

</details>

---

### 93. 🧭 漫游引导 (Tour)

**功能简介：**
引导

**状态/版本：** 已完成 | **创建导出：** `EU_CreateTour` 

<details>
<summary><b>📸 点击查看 UI 截图 (共3张)</b></summary>

<br>

#### 正常状态
![image-20260518182544733](https://img.msblog.cc/img/image-20260518182544733.png)

#### 点击/悬停状态
![image-20260518182613070](https://img.msblog.cc/img/image-20260518182613070.png)

#### 浅色模式
![image-20260518182554233](https://img.msblog.cc/img/image-20260518182554233.png)

</details>

Python打包程序UI演示exe下载：https://mscloak.lanzouv.com/iJIGT3ps4t7c