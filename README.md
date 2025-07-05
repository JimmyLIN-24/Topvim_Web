# Topvim 企业官网

> 阳江市益高箱包有限公司官方网站

## 📋 项目介绍

这是阳江市益高箱包有限公司的官方企业网站，展示公司的产品系列、企业文化和联系方式。网站采用现代化的设计风格，具有响应式布局，支持多种设备访问。

## ✨ 主要特性

- 🎨 **现代化设计** - 采用毛玻璃效果和渐变色彩
- 📱 **响应式布局** - 完美适配桌面、平板和手机
- 🚀 **流畅动画** - 使用GSAP实现丰富的动画效果
- 🖼️ **产品展示** - 支持产品图片画廊和详情展示
- 💼 **企业形象** - 完整的公司介绍和实景展示
- 🌟 **用户体验** - 平滑滚动和交互反馈

## 🏢 公司信息

- **公司名称**: 阳江市益高箱包有限公司
- **成立时间**: 2008年（前身2004年成立）
- **行业经验**: 20年专业制造经验
- **主营产品**: 多功能收纳包、旅行包、化妆包、运动健身包、背包、斜挎包、购物袋

## 🛠️ 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **动画库**: GSAP (GreenSock Animation Platform)
- **图标**: Font Awesome 6.0
- **字体**: Google Fonts (Playfair Display, Noto Sans SC, Cinzel)
- **样式**: CSS Grid, Flexbox, 渐变效果, 毛玻璃效果

## 📂 项目结构

```
topvim-web/
├── index.html             # 主页面（GitHub Pages默认加载）
├── index-enhanced.html    # 增强版本（与index.html相同）
├── index-basic.html       # 基础版本（备份）
├── index-inline.html      # 内联样式版本
├── style.css              # 主样式文件
├── style-fallback.css     # 备用样式
├── script.js              # 主脚本文件
├── test.html              # 测试页面
└── product_pics/          # 产品图片目录
    ├── 00公司实景图片/
    ├── 01公司活动/
    ├── 02产品汇总介绍图/
    ├── 03产品手稿图（特色展出区域）/
    ├── 多功能收纳包/
    ├── 旅行包/
    ├── 化妆包/
    ├── 运动健身游泳包/
    ├── 背包/
    ├── 斜挎包/
    └── 购物袋/
```

## 📄 版本说明

本项目提供了多个版本的HTML文件，适用于不同的使用场景：

### 主要版本
- **`index.html`** - 主页面（GitHub Pages默认加载）
  - 包含完整的GSAP动画效果
  - 毛玻璃导航栏
  - 丰富的交互体验
  - 与index-enhanced.html内容相同

### 备用版本
- **`index-enhanced.html`** - 增强版本（原始版本）
  - 完整功能的原始文件
  - 包含所有高级特性
  
- **`index-basic.html`** - 基础版本
  - 简化版本，使用外部CSS文件
  - 加载速度更快
  - 兼容性更好

- **`index-inline.html`** - 内联样式版本
  - 所有样式内联在HTML中
  - 适合单文件部署

## 🚀 快速开始

### 本地预览

1. 克隆项目到本地：
```bash
git clone https://github.com/JimmyLIN-24/Topvim_Web.git
cd Topvim_Web
```

2. 启动本地服务器：
```bash
# 使用Python 3
python -m http.server 8000

# 或使用Python 2
python -m SimpleHTTPServer 8000
```

3. 在浏览器中访问：
```
http://localhost:8000/index.html
```

### GitHub Pages部署

1. 在GitHub仓库的Settings中开启Pages功能
2. 选择source为`main`分支
3. 网站将自动部署到：`https://JimmyLIN-24.github.io/Topvim_Web/`

## 📸 功能展示

### 主要页面板块

- **英雄区域**: 品牌标语和产品预览卡片
- **关于我们**: 公司介绍和实景展示
- **产品总览**: 产品汇总图展示
- **产品展示**: 7大产品系列的详细介绍
- **公司活动**: 企业文化和团队活动
- **设计工艺**: 产品设计手稿展示
- **联系我们**: 完整的联系信息

### 特色功能

- 🎭 **毛玻璃导航栏**: 滚动时自动切换样式
- 🎨 **文字动画**: 分字符动画效果
- 🖼️ **产品画廊**: 点击查看产品大图
- 📱 **响应式设计**: 自适应各种屏幕尺寸
- 🎯 **平滑滚动**: 导航链接平滑跳转

## 🔧 自定义配置

### 修改公司信息

在`index-enhanced.html`中找到相应的HTML标签进行修改：

```html
<!-- 公司名称 -->
<h2>Topvim</h2>
<span>益高箱包</span>

<!-- 公司介绍 -->
<h3>阳江市益高箱包有限公司</h3>
<p class="company-info">成立于2008年（前身2004年成立）</p>
```

### 更新产品图片

1. 将新图片放入`product_pics/`相应目录
2. 在JavaScript中更新图片路径（第1954行开始）

### 修改样式

主要样式文件：`style.css`和`index-enhanced.html`中的`<style>`标签

## 📞 联系信息

- **网站**: www.topvim.cn
- **地址**: 广东省阳江市
- **邮箱**: contact@topvim.cn
- **电话**: +86-xxx-xxxx-xxxx

## 📄 版权声明

© 2024 阳江市益高箱包有限公司. 保留所有权利.

## 🤝 贡献

欢迎提出建议和改进意见！

## 📝 更新日志

### v1.0.0 (2024-01-xx)
- 初始版本发布
- 实现完整的企业官网功能
- 添加产品展示和公司介绍
- 优化移动端适配

---

⭐ 如果这个项目对您有帮助，请给个Star支持！
