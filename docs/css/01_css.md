# CSS
## CSS 定义

层叠样式表 (Cascading Style Sheets，缩写为 CSS），是一种 样式表 语言，用来描述 HTML 文档的呈现（美化内容）。

## CSS 引入

### 内部样式表 - `style`

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>初识 CSS</title>
  <style>
    p {
      color: red; /* 文字颜色 */
      font-size: 30px;  /* 字号 */
    }
  </style>
</head>
<body>
  <p>体验 CSS</p>
</body>
</html>
```

css 代码写在 style 标签里面,常用与学习使用

### 外部样式表 - `link`

CSS 代码写在单独的 CSS 文件中（.css）， 在 HTML 使用 link 标签引入,开发使用

```html
my.css 文件内容
p {
  color: red;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS 引入方式</title>
  <!-- link 引入外部样式表； rel：关系，样式表 -->
  <link rel="stylesheet" href="./my.css">
</head>
<body>
  <p>这是 p 标签</p>
</body>
</html>
```

### 行内样式表 - `style`

CSS 写在标签的 style 属性值里， 配合 JavaScript 使用

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS 引入方式</title>
</head>
<body>
  <p>这是 p 标签</p>
  <!-- 行内，style=" CSS" -->
  <div style="color: green; font-size: 30px;">这是 div 标签</div>
</body>
</html>
```

## 选择器

### 标签选择器

### 类选择器

### id选择器

### 通配符选择器


