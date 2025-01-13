---
permalink: /
title: "This is a guide from CGQ :)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="width: 80%; max-width: 1000px;">
  <img src="/images/冰红茶.jpg" alt="破防" style="width: 100%; height: auto;">
</div>

<div style="position: relative;">
  <div class="toc" style="position: fixed; right: 100px; top: 20px; width: 240px; max-height: 400px; overflow-y: auto;">
    <h2>目录</h2>
    <ul>
      <li><a href="#大一">大一</a></li>
      <li><a href="#大二">大二</a></li>
      <li><a href="#工作经历">工作经历</a></li>
      <li><a href="#项目">项目</a></li>
    </ul>
  </div>
</div>

<style>
/* 添加偏移量以确保跳转后标题不会被遮挡 */
:target::before {
  content: "";
  display: block;
  height: 80px; /* 调整这个值以适应你的页面布局，确保标题不会被遮挡 */
  margin-top: -80px; /* 与height值相同 */
  visibility: hidden;
}

/* 自定义目录链接样式 */
.toc a {
  color: black; /* 更改为黑色 */
  font-weight: bold; /* 设置为粗体 */
  text-decoration: none; /* 移除下划线 */
  font-family: 'LXGWWENKAI', sans-serif; /* 设置字体为 LXGWWENKAI */
}

.toc a:hover {
  text-decoration: underline; /* 悬停时显示下划线 */
}

/* 为各个标题添加适当的 padding-top 防止遮挡 */
h2, h3, h4 {
  padding-top: 70px; /* 确保标题不会被遮挡，与你的 :target::before 高度相同 */
}

/* 设置默认字体颜色为黑色 */
body, h1, h2, h3, h4, h5, h6, p, a, span, div {
  color: black !important;
}

/* 覆盖全局样式，调整标题的上边距 */
h1, h2, h3, h4, h5, h6 {
  margin-top: 0.5em !important;
  font-family: 'LXGWWENKAI', sans-serif !important;
}
</style>

<script>
// 实现平滑滚动
document.addEventListener('DOMContentLoaded', function() {
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) {
        target.scrollIntoView({
          behavior: 'smooth',
          block: 'start' // 确保滚动的目标元素对齐页面顶部
        });
      }
    });
  });
});
</script>



味精通关指南
======
<div class="toc">
  <h2>目录</h2>
  <ul>
    <li><a href="#大一">大一</a></li>
    <li><a href="#大二">大二</a></li>
    <li><a href="#工作经历">工作经历</a></li>
    <li><a href="#项目">项目</a></li>
  </ul>
</div>

## 大一
这是大一部分。

## 大二
这是教育部分。

## 工作经历
这是工作经历部分。

## 项目
这是项目部分。

会有人看的， <img src="/images/对吗.jpg" alt="对吗" width="200"/>
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
