# yjx五子棋黑先必胜教学

> 无禁手规则下，黑方先手必胜的系统化教学网站——从第一步开局定式到中盘杀法，每门课程配套实战练习。

## 在线访问

**[https://yjx123-a.github.io/yjx-gomoku-tutorial/](https://yjx123-a.github.io/yjx-gomoku-tutorial/)**

## 功能特性

- **7 门系统课程**：从开局必修到综合实战闯关，循序渐进
  1. 开局必修 · 先手必胜的起点
  2. 花月开局 · 直指第一必胜
  3. 浦月开局 · 斜指第一必胜
  4. 直指开局全览
  5. 斜指开局全览
  6. 进攻杀法 · 活三、冲四与组合攻击
  7. 综合实战 · 执黑闯关
- **交互式棋盘**：15×15 标准棋盘，行号 1-15 从上到下，列号 A-O 从左到右，支持逐步演示、自动播放、手数编号
- **实战练习**：执黑落子，系统校验走法，提供提示与讲解，22 个实战关卡
- **对弈模式**：支持双人对弈与人机对战（简单 AI）
- **赞助页面**：支持作者持续更新

## 项目结构

```
├── index.html          # 主页面（自托管，引用 ./assets/ 下的本地资源）
├── 404.html            # SPA 路由回退（与 index.html 相同）
├── .nojekyll           # 禁用 GitHub Pages 的 Jekyll 处理
├── README.md
└── assets/             # 全部静态资源（自托管，不依赖外部 CDN）
    ├── index-CHtyTasP.js      # 应用主逻辑
    ├── index-DNZdFWmS.css     # 样式
    ├── polyfills.js            # 浏览器兼容 polyfill
    ├── rolldown-runtime-CNC7AqOf.js
    ├── radix-Bk9z4NRR.js      # UI 组件库
    └── toolkit-B0huN0bo.js     # 工具库
```

## 技术栈

- 前端：React + TypeScript
- 构建：Vite / Rolldown
- 部署：GitHub Pages（完全自托管，无外部 CDN 依赖）

## 本地部署（GitHub Pages）

1. Fork 或 clone 本仓库
2. 进入仓库 **Settings → Pages**
3. Source 选择 **Deploy from a branch**
4. Branch 选择 **main**，目录选择 **/(root)**，点击 Save
5. 等待 1-2 分钟，站点即部署在 `https://<你的用户名>.github.io/yjx-gomoku-tutorial/`

> 注意：`index.html` 中的 `window.__BASENAME__` 需与仓库名一致。若修改了仓库名，请同步修改该值。

## 课程内容来源

开局定式与必胜点数据参考公开五子棋开局资料（花月、浦月等 26 种开局体系），杀法练习基于标准四三杀、活四杀等棋理设计。

## 许可证

MIT