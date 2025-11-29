<!-- 修复后的毛玻璃效果区域 -->
<div align="center">
  <!-- 父容器：负责承载背景图和文字层，设置相对定位 -->
  <div style="
    position: relative;
    width: 100%;
    max-width: 800px;
    height: 300px;
    border-radius: 15px;
    overflow: hidden;
    margin: 30px auto;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
  ">
    <!-- 背景图：绝对定位，作为底层 -->
    <img src="https://raw.githubusercontent.com/Mythalis-w/Mythalis-w/main/image/1.png" 
         alt="背景图片"
         style="
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: blur(10px) brightness(0.8);
            transform: scale(1.1);
         ">
    
    <!-- 毛玻璃文字层：绝对定位，叠加在背景图上方 -->
    <div style="
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: rgba(255, 255, 255, 0.15);
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 15px;
      padding: 30px;
      text-align: center;
      color: white;
      width: 80%;
      max-width: 500px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
      /* 模拟毛玻璃（适配GitHub） */
      background-image: url('https://raw.githubusercontent.com/Mythalis-w/Mythalis-w/main/image/1.png');
      background-size: cover;
      background-position: center;
      background-blend-mode: overlay;
      opacity: 0.95;
    ">
      <h2 style="margin: 0 0 15px 0; font-size: 2rem; text-shadow: 0 2px 10px rgba(0,0,0,0.3);">
        🚀 创新开发者
      </h2>
      <p style="margin: 0; font-size: 1.1rem; opacity: 0.9; text-shadow: 0 2px 5px rgba(0,0,0,0.3); line-height: 1.5;">
        将想法变为代码，用技术创造价值
      </p>
    </div>
  </div>
</div>

# Mythalis
## Mythalis-w

**人工智能专业本科生**

📍 Tianlin, China  
🕒 UTC +08:00  
🌐 https://space.bilibili.com/393456067

---

## 📚 项目展示

## 🛠️ 技术栈

- **编程语言**: Python, JavaScript, Java, C++
- **人工智能**: 机器学习, 深度学习, 计算机视觉
- **开发工具**: Git, Docker, VS Code, PyCharm

## 📊 GitHub 统计

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mythalis-w&show_icons=true&theme=radical)
