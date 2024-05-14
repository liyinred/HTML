```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap 5 实例</title>
  <meta charset="utf-8">
  <!-- 设置视口，使页面在移动设备上响应良好 -->
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- 引入Bootstrap的CSS文件 -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- 引入Bootstrap的JavaScript文件 -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<!-- 创建一个流体容器，内边距为5，背景为蓝色，文字为白色，居中对齐 -->
<div class="container-fluid p-5 bg-primary text-white text-center">
  <h1>我的第一张 Bootstrap 页面</h1>
  <p>请调整这张响应式页面的大小以查看效果！</p> 
</div>

<!-- 创建一个标准容器，顶部外边距为5 -->
<div class="container mt-5">
  <div class="row">
    <!-- 创建第一列，宽度为中等及以上设备的1/3 -->
    <div class="col-sm-4">
      <h3>列 1</h3>
      <p>胜日寻芳泗水滨，无边光景一时新。</p>
      <p>等闲识得东风面，万紫千红总是春。</p>
    </div>
    <!-- 创建第二列，宽度为中等及以上设备的1/3 -->
    <div class="col-sm-4">
      <!-- 列标题 -->
      <h3>列 2</h3>
      <p>纷纷红紫已成尘，布谷声中夏令新。</p>
      <p>夹路桑麻行不尽，始知身是太平人。</p>
    </div>
    <!-- 创建第三列，宽度为中等及以上设备的1/3 -->
    <div class="col-sm-4">
      <!-- 列标题 -->
      <h3>列 3</h3>        
      <p>远上寒山石径斜，白云生处有人家。</p>
      <p>停车坐爱枫林晚，霜叶红于二月花。</p>
    </div>
  </div>
</div>

</body>
</html>

```
