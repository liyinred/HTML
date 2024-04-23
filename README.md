<!-- 居中对齐图片 -->
<p align='center'>
  <img src="https://github.com/Zzaphkiel/Seraphine/assets/60383222/78c14456-8f8e-4137-a6bc-20896c382c1a">
</p>

<!-- 居中对齐文本 -->
<p align='center'>
  基于 LCU API 实现的英雄联盟战绩查询工具
</p>

<!-- 添加徽章链接 -->
<p align='center'>
  <a href="https://github.com/Zzaphkiel/Seraphine/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/Zzaphkiel/Seraphine?style=flat&label=License">
  </a>
  <a href="https://github.com/Zzaphkiel/Seraphine/forks">
    <img src="https://img.shields.io/github/forks/Zzaphkiel/Seraphine?style=flat&label=Forks">
  </a>
  <a href="https://github.com/Zzaphkiel/Seraphine/stargazers">
    <img src="https://img.shields.io/github/stars/Zzaphkiel/Seraphine?style=flat&label=Stars">
  </a>
  <a href="https://github.com/Zzaphkiel/Seraphine/releases">
    <img src="https://img.shields.io/github/downloads/Zzaphkiel/Seraphine/total?style=flat&label=Downloads">
  </a>
</p>



<section style="text-align: center;">
  <figure>
    <img src="https://github.com/Zzaphkiel/Seraphine/assets/60383222/78c14456-8f8e-4137-a6bc-20896c382c1a" alt="Seraphine logo">
  </figure>
  <div>
    <h1>基于 LCU API 实现的英雄联盟战绩查询工具</h1>
    <div class="badges">
      <a href="https://github.com/Zzaphkiel/Seraphine/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/Zzaphkiel/Seraphine?style=flat&label=License">
      </a>
      <a href="https://github.com/Zzaphkiel/Seraphine/forks">
        <img src="https://img.shields.io/github/forks/Zzaphkiel/Seraphine?style=flat&label=Forks">
      </a>
      <a href="https://github.com/Zzaphkiel/Seraphine/stargazers">
        <img src="https://img.shields.io/github/stars/Zzaphkiel/Seraphine?style=flat&label=Stars">
      </a>
      <a href="https://github.com/Zzaphkiel/Seraphine/releases">
        <img src="https://img.shields.io/github/downloads/Zzaphkiel/Seraphine/total?style=flat&label=Downloads">
      </a>
    </div>
  </div>
</section>

```css
.container {
    width: 100%;  /* 设定容器宽度为父元素的100% */
    max-width: 900px; /* 容器的最大宽度为900px，防止在大屏幕上过宽 */
    height: auto; /* 高度根据内容自动调整 */
    border: 2px solid black; /* 边框为2px宽的黑色实线 */
    border-radius: 10px; /* 边框圆角半径为10px */
    box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* 阴影效果，四周微黑 */
    padding: 10px; /* 容器内部与内容之间的空间为10px */
    margin: 20px auto; /* 外边距为上下20px，左右自动居中 */
    display: flex; /* 使用Flexbox布局 */
    flex-direction: column; /* 主轴方向为垂直方向 */
    align-items: center; /* 子项沿交叉轴（此处为水平方向）居中对齐 */
    position: relative; /* 相对定位，便于后续绝对定位的子元素定位 */
}
.container:before {
    content: "Project 1"; /* 伪元素内容为"Project 1" */
    position: absolute; /* 绝对定位，相对于.container定位 */
    top: 1px; /* 距离容器顶部1px */
    left: 50%; /* 左侧位置50%，即居中 */
    transform: translateX(-50%); /* 通过向左平移50%来精确居中 */
    font-weight: bold; /* 字体加粗 */
    color: black; /* 字体颜色为黑色 */
    font-size: 18px; /* 字体大小为18px */
}
.core {
    width: 90%; /* 宽度为父元素的90% */
    min-height: 60px; /* 最小高度为60px */
    display: flex; /* 使用Flexbox布局 */
    flex-direction: row; /* 主轴方向为水平方向 */
    justify-content: space-between; /* 子元素之间的间距平均分布 */
    align-items: center; /* 子元素在交叉轴上居中对齐 */
    padding: 5px; /* 内边距5px */
    margin-top: 20px; /* 顶部外边距为20px */
    background-color: #7f788b; /* 背景色为淡紫灰色 */
    border-radius: 8px; /* 边框圆角为8px */
    position: relative; /* 相对定位，可能用于后续绝对定位的子元素 */
}
.core:before {
    content: attr(data-name); /* 伪元素内容来自data-name属性 */
    position: absolute; /* 绝对定位，相对于.core定位 */
    top: -8px; /* 顶部外超出-8px，显示在.core外部 */
    left: 50%; /* 左侧位置50%，居中 */
    transform: translateX(-50%); /* 通过向左平移50%来精确居中 */
    font-weight: bold; /* 字体加粗 */
    color: rgb(168, 37, 52); /* 字体颜色为深红色 */
}
.epi {
    width: 30%; /* 宽度为父元素的30% */
    height: auto; /* 高度根据内容自动调整 */
    padding: 5px; /* 内边距5px */
    background-color: darkgray; /* 背景色为深灰色 */
    border-radius: 5px; /* 边框圆角为5px */
    box-shadow: 0 2px 4px rgba(0,0,0,0.05); /* 阴影效果，轻微 */
    text-align: center; /* 文本居中对齐 */
    color: black; /* 字体颜色为黑色 */
    display: flex; /* 使用Flexbox布局 */
    flex-direction: column; /* 主轴方向为垂直方向 */
    justify-content: space-between; /* 子元素间隔均匀 */
    align-items: center; /* 子元素在交叉轴上居中对齐 */
}
.epi-name {
    width: 100%; /* 宽度为100%，即占满父元素宽度 */
    font-size: 16px; /* 字体大小为16px */
    font-weight: bold; /* 字体加粗 */
    color: white; /* 字体颜色为白色 */
    padding: 5px 0; /* 上下内边距5px，左右无内边距 */
    background-color: black; /* 背景颜色为黑色 */
    border-radius: 8px; /* 边框圆角为8px */
}
.node {
    width: 48%; /* 宽度为父元素的48% */
    height: 30px; /* 高度固定为30px */
    background-color: #e0e0e0; /* 背景色为浅灰色 */
    color: rgb(79, 165, 207); /* 字体颜色为天蓝色 */
    border-radius: 5px; /* 边框圆角为5px */
    line-height: 30px; /* 行高为30px，使文字垂直居中 */
    text-align: center; /* 文本水平居中对齐 */
    margin-top: 5px; /* 顶部外边距为5px */
}
```
