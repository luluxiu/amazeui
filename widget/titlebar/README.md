# Titlebar 标题栏
---

标题栏组件，常用作页头、标题等。

## 使用方法

### 直接使用

- 拷贝演示中的代码，粘贴到 Amaze UI HTML 模板（[点此下载](/getting-started)） `<body>` 区域；
- 将示例代码中的内容替换为自己的内容。

### 使用 Handlebars

本组件 Handlebars partial 名称为 `titlebar`，使用细节参照[折叠面板组件](/widgets/accordion)。

### 云适配 WebIDE

- 将组件拖入编辑界面；
- 点击右侧面板里的【数据采集】按钮，按以下格式采集数据。

```javascript
var data = {
  // 以下三项，可任意组合
  "left": "",				// Titlebar 左侧，可写 html 标签（可选）
  "title": "",			// Titlebar 中部，可写 html 标签（可选）
  "right": ""				// Titlebar 右侧，可写 html 标签（可选）
};

return data;
```

## 数据接口

```javascript
{
  "id": "",

  "className": "",

  "theme": "",

  "options": {
  },

  "content": {
    "left": "",
    "title": "",
    "right": ""
  }
}
```
