# 📊 数据可视化平台

一个功能强大的交互式数据可视化Web应用，支持多种图表类型和数据分析功能。

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ 功能特性

### 📈 丰富的图表类型
- **基础图表**: 折线图、柱状图、饼图、散点图
- **高级图表**: 堆积图、箱线图、直方图、误差棒图
- **交互式图表**: 支持缩放、拖拽、悬停提示

### 🔧 强大的交互功能
- **实时数据筛选**: 支持前N名、高于平均值等筛选条件
- **动态参数调节**: 滑块控制数据范围和比例
- **主题切换**: 多种配色方案可选
- **数据导出**: 支持PNG图片和CSV数据导出

### 📊 数据管理
- **多种数据格式**: 支持CSV、Excel数据导入
- **示例数据集**: 内置多个真实数据集
- **数据统计**: 实时显示数据统计信息

## 🚀 快速开始

### 在线访问
项目已部署到GitHub Pages，可直接访问：
[**点击访问数据可视化平台**](https://[您的用户名].github.io/data-visualization-platform)

### 本地运行
```bash
# 克隆项目
git clone https://github.com/[您的用户名]/data-visualization-platform.git

# 进入项目目录
cd data-visualization-platform

# 使用HTTP服务器启动（任选其一）
# 使用Python
python -m http.server 8000

# 使用Node.js (需要安装http-server)
npx http-server -p 8000

# 使用PHP
php -S localhost:8000

# 访问 http://localhost:8000
```

## 📁 项目结构

```
data-visualization-platform/
├── index.html                    # 主页面导航
├── complete_interactive_visualization.html  # 完整交互可视化
├── interactive_visualization.html           # 交互式图表
├── enhanced_interactive_visualization.html  # 增强可视化
├── simple_interactive_visualization.html    # 简单图表
├── csv_chart_generator.html                 # CSV图表生成器
├── README.md                   # 项目说明文档
├── LICENSE                     # 许可证文件
├── .gitignore                  # Git忽略文件
├── .github/workflows/deploy.yml # GitHub Actions部署配置
└── static/                     # 静态资源
    ├── css/
    │   └── style.css          # 样式文件
    └── js/
        └── script.js          # JavaScript文件
```

## 🎯 主要页面

### 🏠 [主页面](index.html)
- 美观的导航界面
- 项目功能概览
- 快速访问所有可视化页面

### 📊 [完整交互可视化](complete_interactive_visualization.html)
- **功能最全面的可视化平台**
- 支持所有图表类型切换
- 实时数据筛选和参数调节
- 主题切换和数据导出功能

### 🔍 [交互式图表](interactive_visualization.html)
- 专注于核心图表展示
- 简洁的界面设计
- 快速加载和响应

### ⚡ [增强可视化](enhanced_interactive_visualization.html)
- 高级交互功能
- 复杂数据分析
- 专业级可视化效果

### 🎨 [简单图表](simple_interactive_visualization.html)
- 基础图表展示
- 适合快速预览
- 轻量级设计

### 📈 [CSV图表生成器](csv_chart_generator.html)
- 自定义数据上传
- 自动图表生成
- 数据格式转换

## 🛠 技术栈

| 技术 | 用途 | 版本 |
|------|------|------|
| **HTML5** | 页面结构 | 最新 |
| **CSS3** | 样式设计 | 最新 |
| **JavaScript** | 交互逻辑 | ES6+ |
| **Chart.js** | 图表渲染 | 4.x |
| **Bootstrap** | UI框架 | 5.x |
| **Font Awesome** | 图标库 | 6.x |

## 📊 示例数据集

项目包含多个真实数据集：

| 数据集 | 描述 | 用途 |
|--------|------|------|
| `complete_visualization_data.csv` | 完整可视化示例数据 | 综合演示 |
| `city_expenditure_data.csv` | 城市支出统计数据 | 柱状图演示 |
| `quality_distribution_data.csv` | 产品质量分布数据 | 箱线图演示 |
| `wanmeiling_data.csv` | 万美灵实验数据 | 误差棒图演示 |
| `temperature_data.csv` | 气温统计数据 | 折线图演示 |

## 🔧 开发指南

### 环境要求
- 现代浏览器（Chrome、Firefox、Safari、Edge）
- 支持ES6+的JavaScript环境
- 本地开发需要HTTP服务器

### 自定义开发
1. 修改HTML文件调整页面结构
2. 编辑CSS文件自定义样式
3. 修改JavaScript文件添加新功能
4. 添加新的数据文件扩展功能

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

## 🤝 贡献

欢迎提交Issue和Pull Request来改进项目！

### 贡献指南
1. Fork 本项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启Pull Request

## 📞 联系方式

如有问题或建议，请通过以下方式联系：
- 提交 [GitHub Issue](https://github.com/[您的用户名]/data-visualization-platform/issues)
- 发送邮件至 [您的邮箱]

---

⭐ 如果这个项目对您有帮助，请给个Star支持一下！