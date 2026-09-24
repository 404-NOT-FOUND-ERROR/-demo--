# 懂了鸭 DEMO Lab

这里收录为「懂了鸭」平台制作的可交互 Demo。每个项目强调一个清晰主题、一条完整体验路径，以及可以直接分享和演示的成品。

## Demo 目录

| Demo | 状态 | 体验方式 |
| --- | --- | --- |
| 窑变陶艺体验 | 可体验 | 下载仓库后双击 `index.html` |

### 窑变陶艺体验

从选择器形、3D 旋转查看、手绘釉色，到选择烧成工艺并观看分阶段烧制，最后生成带有窑变晕染与陶瓷光泽的成品。

- 3D 器物选择与旋转预览
- 多釉色、自定义颜色与三档笔刷
- 可直接在模型表面绘制和叠色
- 分阶段烧制进度与窑变结果
- 器形、釉色与窑火文化科普
- 首次进入的交互引导

## 本地运行

当前 Demo 是单文件网页，直接双击 `index.html` 即可打开。Three.js 从 CDN 加载，体验时需要联网。

## 后续 Demo 规范

新增项目时放入 `demos/<demo-slug>/`，每个目录至少包含：

```text
demos/<demo-slug>/
├─ index.html
├─ README.md
├─ preview.png
└─ assets/        # 仅在存在独立资源时创建
```

根目录 README 维护 Demo 索引；每个 Demo 的 README 说明主题、体验路径、运行方式、依赖和当前状态。详细交付清单见 [DEMO_GUIDE.md](DEMO_GUIDE.md)。

## License

[MIT](LICENSE)
