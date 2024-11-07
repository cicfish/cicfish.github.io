---
permalink: /
title: " This is Fish :)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


A  personal website
======
具体内容见Blog Posts部分

会有人打卡的， <img src="/images/对吗.jpg" alt="对吗" width="200"/>
======

---
layout: default
---

<!-- 弹窗 HTML 结构 -->
<div id="popup-overlay" style="display: none;">
  <div id="popup-content">
    <p id="popup-text">
      <strong>第二周“苦学”作业DDL：</strong>2024.11.10
    </p>
    <button onclick="closePopup()">关闭</button>
  </div>
</div>

<script>
// 弹窗显示函数
function openPopup() {
  document.getElementById('popup-overlay').style.display = 'block';
}

// 弹窗关闭函数
function closePopup() {
  document.getElementById('popup-overlay').style.display = 'none';
}

// 页面加载时显示弹窗
window.onload = function() {
  setTimeout(openPopup, 1000); // 1秒后显示弹窗
};
</script>

<style>
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
  height: 200px;
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

/* 按钮样式 */
button {
  padding: 10px 20px;
  background-color: #007BFF;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background-color: #0056b3;
}

/* 使 Gitalk 评论区的 z-index 更低，确保蒙版遮住它 */
#gitalk-container {
  z-index: 999; /* 比蒙版低，确保被蒙版遮挡 */
}
</style>
