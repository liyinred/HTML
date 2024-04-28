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





这段代码的问题在于，当通过按钮点击更改日期后，原本绑定在按钮上的事件处理器因为 innerHTML 的更新被移除了。这意味着新生成的“更改”按钮没有再次绑定必要的事件处理器，导致按钮点击后没有任何响应。

在修改后的版本中，我创建了几个函数来更好地组织和管理这些操作：

showCoreInEpicDue(core_id, epic_stage, card): 这个函数负责发起请求获取日期数据，并调用 updateDueDateInCard 来更新卡片上的日期和重新绑定事件。
updateDueDateInCard(card, due_date, core_id, epic_stage): 这个函数更新卡片上显示的日期，并重新设置“更改”按钮的点击事件。这确保每次更新HTML内容后，事件处理器都会正确绑定。
displayModal(core_id, epic_stage, due_div): 这个函数负责显示和设置模态窗口。如果模态窗口不存在，它会创建一个新的，同时设置关闭按钮和提交按钮的事件。
fetchDueDate(core_id, epic_stage, days, due_div): 当用户输入天数并提交时，这个函数会被调用。它负责向服务器发送请求，更新日期，并调用 updateDueDateInCard 来更新显示的日期和重新绑定事件。
通过这种方式，每次更新日期时都会确保相关的事件处理器被正确设置，避免了按钮无响应的问题。



```javascript
function showCoreInEpicDue(core_id, epic_stage, card) {
    fetch("/progress/showCoreInEpicDue", {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json',
        },
        body: JSON.stringify({ core_id: core_id, epic_stage: epic_stage })
    })
    .then(response => {
        if (!response.ok) {
            throw new Error('Network response was not ok');
        }
        return response.json();
    })
    .then(data => {
        const due_date = data.due_date;
        updateDueDateInCard(card, due_date, core_id, epic_stage);
    })
    .catch(error => {
        console.error('There was a problem with the fetch operation:', error);
    });
}

function updateDueDateInCard(card, due_date, core_id, epic_stage) {
    const due_div = card.querySelector('.due_date');
    due_div.innerHTML = `
        <strong>Due in epic:</strong> ${due_date}
        <div style="padding-left:50px">
            <button class="set_time btn btn-outline-primary">Change</button>
        </div>
    `;

    const changeBtn = due_div.querySelector('.set_time');
    changeBtn.onclick = function() {
        displayModal(core_id, epic_stage, due_div);
    };
}

function displayModal(core_id, epic_stage, due_div) {
    let modal = document.getElementById("myModal");
    if (!modal) {
        modal = document.createElement("div");
        modal.id = "myModal";
        modal.style.display = "none";
        modal.style.position = "fixed";
        modal.style.left = "0";
        modal.style.top = "0";
        modal.style.width = "100%";
        modal.style.height = "100%";
        modal.style.backgroundColor = "rgba(0,0,0,0.4)";
        modal.innerHTML = `
            <div style="background-color: #fefefe; margin: 15% auto; padding: 20px; border: 1px solid #888; width: 80%;">
                <span class="close" style="color: #aaa; float: right; font-size: 28px; font-weight: bold;">&times;</span>
                <p>📂📂📂</p>
                <label for="due_dateInput">Input due_date:</label>
                <input type="number" id="due_dateInput" placeholder="Enter due_date">
                <button id="submitdue_date" class="btn btn-primary">Submit</button>
            </div>
        `;
        document.body.appendChild(modal);

        modal.querySelector(".close").onclick = function() {
            modal.style.display = "none";
        };
    }

    modal.style.display = "block";

    const submitBtn = modal.querySelector('#submitdue_date');
    submitBtn.onclick = function() {
        const due_date = document.getElementById("due_dateInput").value;
        modal.style.display = "none";
        fetchDueDate(core_id, epic_stage, due_date, due_div);
    };
}

function fetchDueDate(core_id, epic_stage, due_date_str, due_div) {
    // 将 due_date_str 转换为整数，表示要增加的天数
    const daysToAdd = parseInt(due_date_str, 10);

    // 获取当前日期并添加指定的天数
    const currentDate = new Date();
    currentDate.setDate(currentDate.getDate() + daysToAdd);
    const futureDate = currentDate.toISOString().split('T')[0];  // 格式化为 YYYY-MM-DD

    fetch("/progress/showCoreInEpicDue", {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json',
        },
        body: JSON.stringify({ core_id: core_id, epic_stage: epic_stage, due_date: futureDate })
    })
    .then(response => {
        if (!response.ok) {
            throw new Error('Network response was not ok');
        }
        return response.json();
    })
    .then(data => {
        const new_due_date = data.due_date;
        updateDueDateInCard(due_div.parentNode, new_due_date, core_id, epic_stage);
    })
    .catch(error => {
        console.error('Error fetching updated due date:', error);
    });
}
```
