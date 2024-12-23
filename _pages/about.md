---
permalink: /
title: "This is Fish :)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 添加偏移量以确保跳转后标题不会被遮挡 */
:target::before {
  content: "";
  display: block;
  height: 100px; /* 根据需要调整偏移量 */
  margin-top: -100px; /* 与height值相同 */
  visibility: hidden;
}

/* 自定义目录链接样式 */
.toc a {
  color: black; /* 更改为黑色 */
  font-weight: bold; /* 设置为粗体 */
  text-decoration: none; /* 移除下划线 */
}

.toc a:hover {
  text-decoration: underline; /* 悬停时显示下划线 */
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
          behavior: 'smooth'
        });
      }
    });
  });
});
</script>

A personal website
======

<div class="toc">
# 目录
- [简介](#简介)
- [教育](#教育)
- [工作经历](#工作经历)
- [项目](#项目)
</div>

## 简介
这是简介部分。

## 教育
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
