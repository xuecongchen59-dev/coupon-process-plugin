# coupon-process-plugin

飞书多维表格自定义插件展示用的静态组件：券策智能审核流程。

## 文件结构

```text
coupon-process-plugin/
├── index.html
├── style.css
└── README.md
```

## 本地预览

可以直接双击打开 `index.html`，也可以在项目目录启动一个静态服务：

```bash
python -m http.server 8080
```

然后访问：

```text
http://localhost:8080
```

## GitHub Pages 部署

1. 将本目录上传到 GitHub 仓库。
2. 进入仓库 `Settings` → `Pages`。
3. Source 选择 `Deploy from a branch`。
4. Branch 选择 `main`，目录选择 `/root`。
5. 保存后等待 GitHub Pages 生成访问地址。

## 飞书多维表格嵌入建议

- 作为自定义插件或网页嵌入使用。
- 推荐容器高度：`160–180px`。
- 页面不依赖后端、不依赖框架、不加载外部 CDN。
- 背景为白色，适合放入飞书多维表格应用首页。
