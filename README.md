# 二十四节气网站项目说明文档
# 二十四节气网站项目

这是一个展示中国传统二十四节气的静态网站项目，旨在帮助用户了解和学习二十四节气的相关知识。

## 项目特点

1. **响应式设计**：适配不同设备的屏幕尺寸。
2. **丰富的节气内容**：
   - 节气简介
   - 节气渊源
   - 二十四节气列表
   - 节气详情页
3. **用户交互功能**：
   - 用户登录/注册
   - 鼠标悬停效果
   - 图片切换动画
4. **简洁美观的UI**：采用现代设计风格，布局清晰。

## 技术栈

- **前端**：
  - HTML5
  - CSS3
  - JavaScript
- **部署**：
  - GitHub Pages


## 项目结构
├── css
│   └── gonggong.css           # 公共样式
├── images                     # 图片资源
├── js
│   └── index.js               # JavaScript交互代码
├── index.html                 # 首页
├── jieqi.html                 # 二十四节气列表页
├── jianjie.html               # 节气简介页
├── yuanyuan.html              # 节气渊源页
├── login.html                 # 登录页
├── zhuce.html                 # 注册页
└── jieqi_detail.html          # 节气详情页

## 团队分工
  · Person 1：首页与公共资源开发（css/gonggong.css、js/index.js、index.html）
  · Person 2：节气列表与详情页开发（jieqi.html、jieqi_detail.html）
  · Person 3：用户系统与简介页开发（zhuce.html、jianjie.html、login.html）
  · Person 4：渊源页开发与搜集图片（images、yuanyuan.html）

## 功能说明

1. **首页 (index.html)**：
   - 展示"三立一春"（立春、立夏、立秋、立冬）节气卡片
   - 鼠标悬停显示节气详细信息
   - 二十四节气记忆口诀展示
   - 图片悬停切换效果（口诀图片和标题）

2. **二十四节气列表 (jieqi.html)**：
   - 展示所有24个节气的图片和名称
   - 点击任意节气可跳转到详情页（通过URL传递节气名称）

3. **节气简介 (jianjie.html)**：
   - 二十四节气概述
   - 按季节展示各节气交节时间

4. **节气渊源 (yuanyuan.html)**：
   - 介绍二十四节气的历史渊源
   - 节气规律科学解释

5. **登录/注册 (login.html, zhuce.html)**：
   - 用户账号注册功能（表单验证）
   - 用户登录功能（表单验证）
   - 注册成功跳转登录页，登录成功跳转首页

6. **节气详情 (jieqi_detail.html)**：
   - 展示单个节气的详细信息
   - 包含节气图片和详细描述
   - 通过URL参数动态加载内容（根据jieqi.html传递的节气名称）

## 如何运行
1. 克隆或下载项目代码到本地。
2. 打开 index.html 文件即可在浏览器中查看网站。

## 许可证
项目采用MIT许可证。
