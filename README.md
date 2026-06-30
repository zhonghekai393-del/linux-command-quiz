# Linux 命令刷题

一个用于期末复习的本地 Linux 命令刷题页面。直接打开 `index.html` 即可使用，不需要安装依赖或启动服务器。

## 功能

- 29 道 Linux 命令练习题
- 按常用命令、账户管理、权限管理、YUM 软件包、磁盘存储分类
- 顺序刷题、随机抽题、错题重刷
- 上一题 / 下一题
- 重点题标记
- 严格判分：输入内容必须和标准答案一致
- 本地保存答题记录、错题和重点题
- 附答案截图参考

## 文件结构

```text
.
├── index.html
├── assets/
│   └── answer-sheets/
│       ├── review-1.png
│       ├── review-2.png
│       ├── review-3.png
│       └── review-4.png
└── source-docs/
    └── 期末复习资料和答案 Word 文档
```

## 使用

双击 `index.html`，或用浏览器打开：

```text
index.html
```

答题数据保存在浏览器 `localStorage` 中，换浏览器或清除浏览器数据后记录会丢失。

## GitHub Pages

上传到 GitHub 后，可以在仓库设置里启用 GitHub Pages：

1. 进入仓库 `Settings`
2. 打开 `Pages`
3. Source 选择 `Deploy from a branch`
4. Branch 选择 `main` 和 `/root`
5. 保存后访问 Pages 给出的地址
