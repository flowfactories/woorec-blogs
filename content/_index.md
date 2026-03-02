---
title: "Home"
sidebar:
  open: false 
---

<!-- 
  标题区域优化：
  1. 使用 style="..." 强制定义字体，不再依赖不稳定的 Tailwind 类名。
  2. 标题加大到 42px，加粗 (800)，字间距微调。
  3. 副标题加大到 18px-20px，颜色加深，提升可读性。
  4. 增加上下间距 (padding)，让页面更有呼吸感。
-->
<div style="text-align: center; padding: 80px 20px 50px 20px; max-width: 900px; margin: 0 auto;">
  
  <!-- 主标题 -->
  <h2 style="
    font-size: 42px; 
    font-weight: 800; 
    color: #111827; 
    margin: 0 0 20px 0; 
    letter-spacing: -0.02em;
    line-height: 1.2;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  ">
    Latest Success Stories
  </h2>

  <!-- 副标题 -->
  <p style="
    font-size: 20px; 
    color: #4b5563; 
    line-height: 1.6; 
    margin: 0 auto;
    font-weight: 400;
    max-width: 600px;
  ">
    Explore how we help businesses grow with intelligent recommendations.
  </p>

</div>

<!-- 
  注意：
  这里依然不需要写列表代码。
  layouts/index.html 会自动把漂亮的卡片网格接在这个标题下面。
-->
