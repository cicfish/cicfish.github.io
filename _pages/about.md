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
    <p id="popup-text">第二周“苦学”作业DDL：2024.11.10</p>
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
  background-color: rgba(0, 0, 0, 0.5); /* 半透明灰色背景 */
  display: none;
  z-index: 9998; /* 确保蒙版位于弹窗下方，优先级仅次于弹窗 */
  display: flex;
  justify-content: center;
  align-items: center;
}

/* 弹窗样式 */
#popup-content {
  background-color: white;
  width: 300px; /* 设置宽度为手掌大小 */
  height: 400px; /* 设置高度为手掌大小 */
  padding: 20px;
  border-radius: 10px;
  z-index: 9999; /* 确保弹窗位于最上层 */
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  text-align: center;
}

#popup-text {
  font-size: 20px; /* 默认字体大小 */
  font-family: Arial, sans-serif; /* 默认字体 */
  color: #333; /* 默认字体颜色 */
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
</style>
