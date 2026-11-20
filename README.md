# SCAU Smart Orchard Lab 402

实验室公开网站：<https://scau-smart-orchard-lab-402.github.io/>

## 页面内容

- 智慧果园 VLA 项目介绍
- TRON2 荔枝采摘实验视频
- 遥操作、数据、训练、部署与评测技术路线
- 实验室研究方向与代码仓库入口

## 本地预览

网站为无构建依赖的静态页面。在仓库目录执行：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 文件结构

```text
.
├── index.html
├── styles.css
├── script.js
└── assets/
    ├── favicon.svg
    ├── tron2-lychee-demo-1.5x.mp4
    └── tron2-lychee-poster.jpg
```

视频已经编码为 H.264/AAC，并在文件层面加速至原始素材的 1.5 倍。