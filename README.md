# gait-junior-online

GAIT-Junior 初中标准筛查版，基于 jsPsych 7.3.4 的静态实验页面。

## 在线访问

[打开实验](https://wendiyang781-coder.github.io/gait-junior-online/)

## GitHub Pages 部署

在仓库的 **Settings → Pages → Build and deployment** 中使用：

- Source：**Deploy from a branch**
- Branch：**main**
- Folder：**/ (root)**

根目录中的 `index.html` 是默认入口。提交修改后，在 **Actions → pages build and deployment** 查看发布结果。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `index.html` | 正式入口，由 `index.html.html` 原样重命名，实验代码未改动。 |
| `初中2.html` | 暂时保留的原版页面，兼容已分发的旧链接；确认不再使用旧链接后可删除。 |
| `README.md` | 访问地址和部署说明。 |

不要再次上传成 `index.html.html`。后续修改以 `index.html` 为准；如继续使用 `初中2.html` 旧链接，应同步更新其内容，避免两个版本不一致。

页面启动需要联网访问 unpkg.com，以加载 jsPsych 及其插件。
