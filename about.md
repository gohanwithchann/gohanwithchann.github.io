---
layout: page
title: About
permalink: /about/
---

# Hi~ 👋
This blog is my original work, archived in the `_posts` folder, and all rights are reserved. 
Please contact me for authorization before reusing or reposting.

If you find this blog is useful, a simple star (<a class="github-button" 
  href="https://github.com/gohan/gohan.github.io" 
  data-icon="octicon-star" 
  data-size="large"
  data-show-count="true" 
  aria-label="Star it on GitHub">Star on Github</a>) should be the best affirmation. 😊

<!-- * [My Homepage](https://gohanwithchann.github.io/)  -->

[comment]: <> (  <h2 align="center">PAPER</h2>)
  <h3 align="center">
  <a href="/about/">English Version</a> 
  | <a href="/about-cn/">中文版</a> 
  </h3>

<style>
/* 内联样式隔离 */
#iframe-wrapper {
  width: 100%;
  overflow: hidden;
  border: none;
  display: block;
  margin: 0;
  padding: 0;
}

#iframe-content {
  width: 100%;
  border: none;
  display: block; /* 消除 iframe 默认的 inline 空隙 */
}
</style>

<div id="iframe-wrapper">
  <iframe 
    id="iframe-content"
    src="https://gohanwithchann.github.io/index.html" 
    onload="this.style.height = this.contentWindow.document.documentElement.scrollHeight + 'px'"
  ></iframe>
</div>

<script>
// 纯当前页面运行的脚本
document.getElementById('iframe-content').addEventListener('load', function() {
  try {
    const contentHeight = this.contentWindow.document.documentElement.scrollHeight;
    this.style.height = contentHeight +100+ 'px';//增加了高度
    // 添加窗口变化监听
    window.addEventListener('resize', () => {
      this.style.height = this.contentWindow.document.documentElement.scrollHeight + 'px';
    });
  } catch (error) {
    console.log('跨域保护机制触发，请确保被嵌入页面与本站同源');
  }
});
</script>


<!-- # Hi~ 👋
only for template

## 版权声明

博客文章是我原创文章，存档于_posts 文件夹下，版权归我所有，转载请与我联系获得授权许可。

This blog is my original work, archived in the _posts folder, and all rights are reserved. 
Please contact me for authorization before reusing or reposting. -->
