---
title: Welcome to my blog!
layout: default
---

<style>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem 1rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  line-height: 1.6;
  color: #333;
}
.hero {
  text-align: center;
  padding: 4rem 0;
  border-bottom: 1px solid #eee;
}
.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
  color: #2c3e50;
}
.hero p {
  font-size: 1.2rem;
  color: #666;
}
.section {
  margin: 3rem 0;
}
.section h2 {
  color: #2c3e50;
  border-left: 4px solid #3498db;
  padding-left: 1rem;
}
.project-card {
  padding: 1rem;
  border: 1px solid #eee;
  border-radius: 8px;
  margin-bottom: 1rem;
  transition: box-shadow 0.2s;
}
.project-card:hover {
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}
.project-card h3 {
  margin-top: 0;
  color: #3498db;
}
.contact-links {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 2rem;
}
.contact-links a {
  padding: 0.5rem 1rem;
  border-radius: 4px;
  background: #f5f5f5;
  color: #333;
  text-decoration: none;
  transition: all 0.2s;
}
.contact-links a:hover {
  background: #3498db;
  color: white;
}
</style>

<div class="container">
  <div class="hero">
    <h1>你好，我是XXX 👋</h1>
    <p>欢迎来到我的个人主页 | 开发者 | 技术爱好者</p>
  </div>

  <div class="section">
    <h2>关于我</h2>
    <p>这里可以写你的自我介绍，比如你的技术栈、兴趣爱好、学习方向等等。</p>
    <p>示例：我专注于前端开发，熟悉 React、Vue 等框架，同时也对后端、云计算有浓厚的兴趣。</p>
  </div>

  <div class="section">
    <h2>我的项目</h2>
    <div class="project-card">
      <h3>项目名称1</h3>
      <p>项目的详细介绍，比如用了什么技术栈，解决了什么问题。</p>
      <a href="https://github.com/你的用户名/项目1" target="_blank">查看源码</a>
    </div>
    <div class="project-card">
      <h3>项目名称2</h3>
      <p>项目的详细介绍，比如用了什么技术栈，解决了什么问题。</p>
      <a href="https://github.com/你的用户名/项目2" target="_blank">查看源码</a>
    </div>
  </div>

  <div class="section">
    <h2>博客与笔记</h2>
    <p>这里会记录我的学习笔记、技术踩坑记录、生活日常，欢迎交流。</p>
    <ul>
      <li><a href="./posts/first-post.html">我的第一篇博客</a></li>
      <li><a href="./notes/frontend.html">前端学习笔记汇总</a></li>
    </ul>
  </div>

  <div class="section">
    <h2>联系我</h2>
    <div class="contact-links">
      <a href="https://github.com/你的用户名" target="_blank">GitHub</a>
      <a href="mailto:你的邮箱@example.com">邮箱</a>
      <a href="https://juejin.cn/user/你的ID" target="_blank">掘金</a>
      <a href="https://www.zhihu.com/people/你的ID" target="_blank">知乎</a>
    </div>
  </div>
</div>
