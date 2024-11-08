---
permalink: /
title: " This is Fish :)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- 弹窗 HTML 结构 -->
<div id="popup-overlay" style="display: none;">
  <div id="popup-content">
    <p id="popup-text">
      <strong>第二周“苦学”作业DDL：</strong>2024.11.10
    </p>
    <!-- 按钮容器，使用 Flexbox 排列按钮 -->
    <div id="button-container">
      <button class="popup-button" onclick="closePopup()">关闭</button>
      <button class="popup-button" onclick="redirectToUrl()">跳转</button>
    </div>
  </div>
</div>

<script>
// 弹窗显示函数
function openPopup() {
  document.getElementById('popup-overlay').style.display = 'block';
  document.body.classList.add('no-scroll');  // 禁用滚动
}

// 弹窗关闭函数
function closePopup() {
  document.getElementById('popup-overlay').style.display = 'none';
  document.body.classList.remove('no-scroll');  // 启用滚动
}

// 跳转到指定网址的函数
function redirectToUrl() {
  window.location.href = "https://cicfish.github.io//posts/2024/announcements/week/";  // 将此处的 URL 替换为需要跳转的地址
}

// 页面加载时显示弹窗
window.onload = function() {
  setTimeout(openPopup, 100); // 0.1秒后显示弹窗
};
</script>

<style>

 .no-scroll {
  overflow: hidden;
}
  
/* 蒙版样式 */
#popup-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.7); /* 半透明背景 */
  z-index: 1001; /* 确保蒙版在最上层 */
  display: none; /* 初始不显示 */
}

/* 弹窗样式 */
#popup-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); /* 居中 */
  width: 300px;
  height: 220px; /* 增加高度以适应两个按钮 */
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
  z-index: 1002; /* 确保弹窗在蒙版之上 */
}

/* 文字样式 */
#popup-text {
  font-size: 18px;
  font-family: Arial, sans-serif;
  color: #333;
  line-height: 1.5;
}

/* 按钮容器样式，使用 Flexbox 布局 */
#button-container {
  display: flex;
  justify-content: space-between;  /* 按钮之间留出空间 */
  margin-top: 20px;  /* 增加按钮和文字之间的间距 */
}

/* 弹窗按钮样式，使用 .popup-button 进行限定 */
.popup-button {
  padding: 10px 20px;
  background-color: #007BFF;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
  width: 45%; /* 确保按钮宽度一致 */
}

/* 鼠标悬停时按钮样式 */
.popup-button:hover {
  background-color: #0056b3;
}
</style>


A  personal website
======
具体内容见Blog Posts部分

会有人打卡的， <img src="/images/对吗.jpg" alt="对吗" width="200"/>
======

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

