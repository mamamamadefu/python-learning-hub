# 🐍 Python 学习宝库

> 一个把 **Python 入门教程** 和 **爬虫实战** 放在一起的合并仓库，取自两套经典开源资源，整理成统一的学习路径。

[![Python](https://img.shields.io/badge/Python-3.6+-3776AB?style=flat-square&logo=python&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-整理中-4b9cf2?style=flat-square)]()

---

## 📁 仓库结构

```
python-learning-hub/
├── README.md            ← 本文件（总览 + 学习路线）
├── python-tutorial/     ← 📘 Python 入门教程（草根学 Python）
│   ├── Article/         ┊   系统化基础 + 进阶 + Django
│   ├── Res/             ┊   学习资源与工具集
│   ├── SUMMARY.md       ┊   章节导航
│   └── book.json        ┊   GitBook 配置
└── spider/              ← 🕷 爬虫实战（零基础学爬虫）
    ├── examples/        ┊   26 个由浅入深的爬虫示例
    ├── dangdang/        ┊   当当网商品爬虫（Scrapy）
    ├── baidunews/       ┊   百度新闻爬虫（Scrapy）
    ├── douban/          ┊   豆瓣登录 + 验证码识别
    └── jdgoods/         ┊   京东图书爬虫（Scrapy+urllib）
```

---

## 🗺️ 建议学习路线

按「**先打好基础，再做实战**」的顺序推进，避免「从入门到放弃」：

```
📘 入门篇（python-tutorial/Article）
   └── 基础语法 → 数据类型 → 控制流 → 函数 → 面向对象
       → 模块与包 → 正则 → 闭包/装饰器 → 进阶

         ↓ 基础扎实后

🕷 实战篇（spider/）
   ├── examples/ 1~12  掌握 Python 语法 + 编写第一个爬虫
   ├── examples/ 13~18 urllib 请求模拟、伪装、异常处理、实战
   ├── examples/ 19~26 代理池、XPath、BeautifulSoup、PhantomJS
   └── Scrapy 项目    当当 / 百度新闻 / 豆瓣 / 京东
```

---

## 📘 python-tutorial · 入门教程

基于 **Python 3.6** 的系统化入门教程，覆盖从零到进阶的完整内容：

- **基础语法**：数据类型、变量、条件、循环、函数
- **进阶特性**：迭代器、生成器、面向对象、Magic Method、元类
- **常用模块**：正则表达式、线程与进程、闭包/装饰器
- **Web 开发**：Django 框架入门（从搭建到部署）
- 📚 资源：`Res/` 目录内含优质博客网站清单与联网工具集

各章节详见 [`python-tutorial/SUMMARY.md`](python-tutorial/SUMMARY.md)。

---

## 🕷 spider · 爬虫实战

零基础学爬虫，`examples/` 提供 **26 个循序渐进的可运行示例**：

| 阶段 | 示例 | 内容 |
|------|------|------|
| 基础 | 1–12 | Python 语法、控制流、函数、模块、文件、正则、第一个爬虫 |
| HTTP | 13–18 | 超时设置、请求模拟、POST、异常处理、浏览器伪装、CSDN 爬虫 |
| 进阶 | 19–26 | 用户代理池、IP 代理池、淘宝图片、XPath、BeautifulSoup、PhantomJS |
| Scrapy | 独立目录 | 当当、百度新闻、豆瓣（含验证码识别）、京东图书 |

> ⚠️ 示例基于 Python 3.5，部分库（如 PhantomJS）已较旧，建议根据现网环境调整。

---

## 🚀 快速开始

```bash
# 克隆本仓库
git clone https://github.com/mamamamadefu/python-learning-hub.git

# 进入目录
cd python-learning-hub

# 从入门教程开始看
cd python-tutorial/Article

# 或直接跑爬虫示例（需先安装依赖）
cd spider/examples
python example-12.py   # 第一个简单爬虫
```

---

## 📜 版权说明

本仓库为**学习资源的整理与合并**，内容分别来自：

- `python-tutorial` ← fork 自 [`walter201230/Python`](https://github.com/walter201230/Python)
- `spider` ← fork 自 [`gl2378/python-spider`](https://github.com/gl2378/python-spider)

仅用于个人学习与交流，版权归原作者所有。

---

## ✨ 维护

- [ ] 更新爬虫示例至 Python 3 新写法
- [ ] 补充环境安装与依赖说明
- [ ] 添加目录分级导航