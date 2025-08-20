# SmartMem 官方网站

这是一个美观、现代化的HTML静态网站，用于介绍SmartMem智能记忆助手APP。

## 功能特点

- 🎨 **现代化设计**: 采用渐变色彩和现代UI设计
- 📱 **响应式布局**: 完美适配桌面、平板和手机设备
- 🌍 **中英文切换**: 支持中文和英文两种语言
- ⚡ **性能优化**: 轻量级代码，快速加载
- 🎯 **用户体验**: 流畅的动画和交互效果

## 页面结构

```
html/
├── index.html          # 主页
├── privacy.html        # 隐私政策
├── terms.html          # 服务条款
├── subscription.html   # 订阅协议
├── support.html        # 技术支持
├── css/
│   ├── style.css       # 主样式文件
│   └── legal.css       # 法律页面样式
├── js/
│   ├── script.js       # 主JavaScript文件
│   └── legal.js        # 法律页面JavaScript
├── images/
│   ├── logo.png        # 网站Logo
│   ├── app-preview.png # APP预览图
│   ├── favicon.ico     # 网站图标
│   ├── app-store.svg   # App Store下载按钮
│   └── google-play.svg # Google Play下载按钮
└── README.md           # 说明文档
```

## 主要功能

### 1. 主页 (index.html)
- Hero区域：展示APP核心价值
- 功能介绍：四个核心功能卡片
- 下载区域：App Store和Google Play下载链接
- 响应式导航栏

### 2. 法律页面
- **隐私政策** (privacy.html): 详细的隐私保护说明
- **服务条款** (terms.html): 完整的服务使用条款
- **订阅协议** (subscription.html): 付费服务相关条款

### 3. 技术支持 (support.html)
- 常见问题FAQ（可展开/收起）
- 联系表单（带验证功能）
- 多种联系方式
- 实时客服支持

### 4. 多语言支持
- 中文（默认）
- 英文
- 语言切换按钮
- 本地存储语言偏好

## 技术栈

- **HTML5**: 语义化标签
- **CSS3**: Flexbox、Grid、动画
- **JavaScript**: ES6+、DOM操作
- **字体**: Inter字体系列
- **图标**: Font Awesome 6.0
- **响应式**: Mobile-first设计

## 使用方法

### 1. 直接访问
将整个`html`文件夹部署到Web服务器即可访问。

### 2. 本地预览
```bash
# 使用Python简单服务器
cd html
python -m http.server 8000

# 或使用Node.js
npx serve .

# 然后访问 http://localhost:8000
```

### 3. 自定义配置

#### 修改APP信息
编辑`js/script.js`中的翻译数据：
```javascript
const translations = {
    zh: {
        title: "您的APP名称",
        hero_title: "您的标语",
        // ... 其他翻译
    }
}
```

#### 更换图片
- 替换`images/logo.png`为您的Logo
- 替换`images/app-preview.png`为您的APP截图
- 更新下载链接的href属性

#### 修改样式
- 主要样式在`css/style.css`
- 法律页面样式在`css/legal.css`
- 可以修改CSS变量来快速更换主题色

## 浏览器支持

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- 移动端浏览器

## 性能优化

- 使用CDN加载字体和图标
- 图片懒加载
- CSS和JS文件压缩
- 响应式图片
- 缓存策略

## SEO优化

- 语义化HTML结构
- Meta标签优化
- 结构化数据
- 移动端友好
- 快速加载速度

## 联系方式

如需技术支持或定制开发，请联系：
- 邮箱: support@smartmem.app
- 网站: https://smartmem.app

## 许可证

本项目仅供SmartMem APP使用，请勿用于其他商业用途。

---

© 2024 SmartMem. 保留所有权利。
