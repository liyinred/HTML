:not([class*='woo-badge-') 是一个属性选择器，用于选择具有特定属性值的元素。具体来说，选择所有 class 属性值包含 woo-badge- 的元素。这里的 *= 是一个包含运算符，表示属性值中包含给定字符串。
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




/* 设置整个页面的布局 */
body {
    display: flex; /* 使用flex布局，使其子元素可以灵活地排列 */
    justify-content: center; /* 子元素水平居中对齐 */
    margin: 0; /* 去除默认的边距 */
    background-color: #f4f4f4; /* 设置页面的背景颜色为浅灰色 */
}

/* 设置.container类的样式，用于页面主体区域 */
.container {
    background-color: white; /* 设置背景颜色为白色 */
    border-radius: 15px; /* 设置边角为圆角，半径为15px */
    box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* 设置阴影效果 */
    width: 40%; /* 宽度设置为容器宽度的40% */
    padding: 20px; /* 内边距为20px */
    box-sizing: border-box; /* 边框和内边距包含在宽度内 */
    border: 2px solid #ddd; /* 设置边框为浅灰色 */
}

/* 设置.header类的样式，通常用于标题或头部区域 */
.header {
    font-size: 24px; /* 设置字体大小为24px */
    color: #333; /* 设置字体颜色为深灰色 */
    margin-bottom: 20px; /* 设置与下面元素的间距为20px */
    text-align: center; /* 文本居中显示 */
}

/* 设置.project类的样式，用于展示项目或特定内容区块 */
.project {
    display: block; /* 使元素以块级元素显示 */
    background-color: rgb(101, 42, 165); /* 设置背景颜色 */
    color: white; /* 文本颜色为白色 */
    text-align: center; /* 文本居中显示 */
    padding: 10px; /* 内边距为10px */
    text-decoration: none; /* 去除文本的下划线 */
    border-radius: 10px; /* 边角圆滑，半径为10px */
    margin-bottom: 20px; /* 与下面元素的间距为20px */
}

/* 设置.project类在鼠标悬停时的样式变化 */
.project:hover {
    background-color: #a400b3; /* 鼠标悬停时背景颜色变化 */
}

/* 设置.project类内的div元素的样式 */
.project div {
    margin: 0; /* 设置外边距为0 */
}

/* 设置.menu类的样式，用于导航菜单 */
.menu {
    display: flex; /* 使用flex布局 */
    justify-content: space-around; /* 子元素均匀分布 */
    margin-bottom: 50px; /* 底部间距为50px */
    border-bottom: 1px dashed; /* 底部边框为虚线 */
    padding-bottom: 12px; /* 底部内边距为12px */
}

/* 设置.menu类内的div元素的样式 */
.menu div {
    text-align: center; /* 文本居中显示 */
}

/* 设置.submenu类的样式，通常用于下拉菜单 */
.submenu {
    background-color: #EFEFEF; /* 背景颜色为浅灰色 */
    margin-top: 10px; /* 顶部外边距为10px */
    padding: 10px; /* 内边距为10px */
    border-radius: 10px; /* 边角圆滑，半径为10px */
    display: flex; /* 使用flex布局 */
    flex-direction: column; /* 子元素垂直排列 */
}

/* 设置.submenu类内的div元素的样式 */
.submenu div {
    padding: 2px; /* 内边距为2px */
    margin: 15px 0; /* 顶部和底部外边距为15px */
    background-color: white; /* 背景颜色为白色 */
    border-radius: 5px; /* 边角圆滑，半径为5px */
}

/* 设置.button类的样式，用于按钮 */
.button {
    display: inline-block; /* 使元素以行内块显示 */
    padding: 10px 20px; /* 内边距为10px 20px */
    margin: 5px; /* 外边距为5px */
    background-color: #007BFF; /* 背景颜色为蓝色 */
    color: white; /* 文本颜色为白色 */
    text-align: center; /* 文本居中显示 */
    text-decoration: none; /* 去除文本的下划线 */
    border-radius: 5px; /* 边角圆滑，半径为5px */
    transition: background-color 0.3s; /* 背景颜色变化过渡效果 */
}

/* 设置.button类在鼠标悬停时的样式变化 */
.button:hover {
    background-color: #0056b3; /* 鼠标悬停时背景颜色变化 */
}

```
```JavaScript
// 给所有具有类名 'drag-item' 的元素添加拖动开始事件的监听
document.querySelectorAll('.drag-item').forEach(item => {
    // 当拖动开始时，该函数被调用
    item.addEventListener('dragstart', function(event) {
        // 设置拖动数据，将拖动的元素的id作为数据传递，格式为纯文本
        event.dataTransfer.setData('text/plain', event.target.id);
    });
});

// 给所有具有类名 'drag-container' 的元素添加事件监听，以支持拖放操作
document.querySelectorAll('.drag-container').forEach(container => {
    // 拖动元素经过容器时调用此函数
    container.addEventListener('dragover', function(event) {
        // 阻止默认处理，这是必须的，以便允许放置
        event.preventDefault(); 
    });

    // 在元素放置时调用此函数
    container.addEventListener('drop', function(event) {
        // 阻止事件的默认处理，这也是必要的
        event.preventDefault();
        // 从拖动数据中获取元素的id
        const data = event.dataTransfer.getData('text');
        // 根据id获取元素
        const element = document.getElementById(data);
        // 检查元素是否存在，且放置的目标容器不是该元素的当前父容器
        if (element && this !== element.parentNode) {
            // 将元素添加到目标容器中
            this.appendChild(element);
        }
    });
});

```



下面这段代码的问题在于，当通过按钮点击更改日期后，原本绑定在按钮上的事件处理器因为 innerHTML 的更新被移除了。这意味着新生成的“更改”按钮没有再次绑定必要的事件处理器，导致按钮点击后没有任何响应。

在修改后的版本中，我创建了几个函数来更好地组织和管理这些操作：

showCoreInEpicDue(core_id, epic_stage, card): 这个函数负责发起请求获取日期数据，并调用 updateDueDateInCard 来更新卡片上的日期和重新绑定事件。
updateDueDateInCard(card, due_date, core_id, epic_stage): 这个函数更新卡片上显示的日期，并重新设置“更改”按钮的点击事件。这确保每次更新HTML内容后，事件处理器都会正确绑定。
displayModal(core_id, epic_stage, due_div): 这个函数负责显示和设置模态窗口。如果模态窗口不存在，它会创建一个新的，同时设置关闭按钮和提交按钮的事件。
fetchDueDate(core_id, epic_stage, days, due_div): 当用户输入天数并提交时，这个函数会被调用。它负责向服务器发送请求，更新日期，并调用 updateDueDateInCard 来更新显示的日期和重新绑定事件。
通过这种方式，每次更新日期时都会确保相关的事件处理器被正确设置，避免了按钮无响应的问题。
```javascript
// 定义一个函数来显示某个核心任务在特定史诗阶段的截止日期
function showCoreInEpicDue(core_id, epic_stage, card) {
    // 发送一个 POST 请求到服务器端的指定 URL，包含核心任务 ID 和史诗阶段
    fetch("/progress/showCoreInEpicDue", {
        method: 'POST', // 请求方式为 POST
        headers: { // 请求头
            'Content-Type': 'application/json', // 请求内容类型为 JSON
        },
        body: JSON.stringify({ core_id: core_id, epic_stage: epic_stage }) // 请求体，发送 JSON 字符串
    })
    .then(response => { // 处理响应
        if (!response.ok) { // 如果响应状态不是 ok，则抛出错误
            throw new Error('Network response was not ok');
        }
        return response.json(); // 将响应转换为 JSON
    })
    .then(data => { // 处理转换后的数据
        const due_date = data.due_date; // 从响应数据中获取截止日期
        updateDueDateInCard(card, due_date, core_id, epic_stage); // 更新卡片上的截止日期
    })
    .catch(error => { // 捕获并处理错误
        console.error('There was a problem with the fetch operation:', error);
    });
}

// 定义一个函数，用于在卡片上更新截止日期信息
function updateDueDateInCard(card, due_date, core_id, epic_stage) {
    const due_div = card.querySelector('.due_date'); // 从卡片中找到显示截止日期的元素
    // 设置截止日期的 HTML 内容
    due_div.innerHTML = `
        <strong>Due in epic:</strong> ${due_date}
        <div style="padding-left:50px">
            <button class="set_time btn btn-outline-primary">Change</button>
        </div>
    `;

    const changeBtn = due_div.querySelector('.set_time'); // 获取更改按钮
    changeBtn.onclick = function() { // 设置更改按钮的点击事件
        displayModal(core_id, epic_stage, due_div); // 显示一个模态对话框以更改截止日期
    };
}

// 定义一个函数，用于显示修改截止日期的模态对话框
function displayModal(core_id, epic_stage, due_div) {
    let modal = document.getElementById("myModal"); // 尝试获取模态对话框元素
    if (!modal) { // 如果模态对话框不存在，则创建一个
        modal = document.createElement("div");
        modal.id = "myModal";
        modal.style.display = "none";
        modal.style.position = "fixed";
        modal.style.left = "0";
        modal.style.top = "0";
        modal.style.width = "100%";
        modal.style.height = "100%";
        modal.style.backgroundColor = "rgba(0,0,0,0.4)"; // 半透明背景
        modal.innerHTML = `
            <div style="background-color: #fefefe; margin: 15% auto; padding: 20px; border: 1px solid #888; width: 80%;">
                <span class="close" style="color: #aaa; float: right; font-size: 28px; font-weight:bold;">&times;</span>
                <p>📂📂📂</p>
                <label for="due_dateInput">Input due_date:</label>
                <input type="number" id="due_dateInput" placeholder="Enter due_date">
                <button id="submitdue_date" class="btn btn-primary">Submit</button>
            </div>
        `;
        document.body.appendChild(modal); // 将模态对话框添加到文档中

        modal.querySelector(".close").onclick = function() { // 设置关闭按钮的点击事件
            modal.style.display = "none"; // 隐藏模态对话框
        };
    }

    modal.style.display = "block"; // 显示模态对话框

    const submitBtn = modal.querySelector('#submitdue_date'); // 获取提交按钮
    submitBtn.onclick = function() { // 设置提交按钮的点击事件
        const due_date = document.getElementById("due_dateInput").value; // 获取输入的新截止日期
        modal.style.display = "none"; // 隐藏模态对话框
        fetchDueDate(core_id, epic_stage, due_date, due_div); // 发送请求更新截止日期
    };
}

// 定义一个函数，用于发送请求并更新截止日期
function fetchDueDate(core_id, epic_stage, due_date_str, due_div) {
    // 将输入的截止日期字符串转换为整数，表示要增加的天数
    const daysToAdd = parseInt(due_date_str, 10);

    // 获取当前日期并添加指定的天数
    const currentDate = new Date();
    currentDate.setDate(currentDate.getDate() + daysToAdd);
    const futureDate = currentDate.toISOString().split('T')[0];  // 格式化为 YYYY-MM-DD

    // 发送一个 POST 请求到服务器端的指定 URL，更新截止日期
    fetch("/progress/showCoreInEpicDue", {
        method: 'POST', // 请求方式为 POST
        headers: { // 请求头
            'Content-Type': 'application/json', // 请求内容类型为 JSON
        },
        body: JSON.stringify({ core_id: core_id, epic_stage: epic_stage, due_date: futureDate }) // 请求体，发送 JSON 字符串
    })
    .then(response => { // 处理响应
        if (!response.ok) { // 如果响应状态不是 ok，则抛出错误
            throw new Error('Network response was not ok');
        }
        return response.json(); // 将响应转换为 JSON
    })
    .then(data => { // 处理转换后的数据
        const new_due_date = data.due_date; // 从响应数据中获取新的截止日期
        updateDueDateInCard(due_div.parentNode, new_due_date, core_id, epic_stage); // 更新卡片上的截止日期
    })
    .catch(error => { // 捕获并处理错误
        console.error('Error fetching updated due date:', error);
    });
}
```

```python
def showCoreInEpicDue(request):
    if request.method == 'POST':  # 如果请求方式为POST
        # 从请求体中获取数据
        data_from_frontend = json.loads(request.body.decode('utf-8'))  # 将请求体中的内容解码并转换为JSON对象
        print('Data received from frontend:', data_from_frontend)  # 打印从前端接收到的数据
        core_id = data_from_frontend.get('core_id')  # 从数据中获取core_id
        epic_stage = data_from_frontend.get('epic_stage')  # 从数据中获取epic_stage
        
        # 根据core_id从数据库中获取Core对象
        core = work_task_series.Core.objects.get(pk=core_id)
        # 从数据库中查找第一个名称为epic_stage的Epic对象
        epic = work_task_series.Epic.objects.filter(name=epic_stage).first()

        # 根据core和epic查询CoreEpicTime对象，并按主键倒序排序
        queryset = work_task_series.CoreEpicTime.objects.filter(
            core=core,
            epic=epic
        ).order_by('-pk')

        # 初始化due_date变量
        # due_date = 'Not set'
        
        due_date = data_from_frontend.get('due_date')  # 从数据中获取due_date
        if queryset.exists():  # 如果查询集不为空
            due_date = queryset.first().due_date  # 获取最近的due_date
            due_date = due_date.strftime('%Y-%m-%d')  # 将due_date格式化为'YYYY-MM-DD'格式
        return JsonResponse({'due_date': due_date})  # 返回JSON响应，包含due_date

    else:
        # 处理其他HTTP方法
        return JsonResponse({'error': 'Only POST requests are allowed'})  # 如果不是POST请求，返回错误信息

```
