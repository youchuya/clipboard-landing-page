# Clipboard landing page

Frontend Mentor 挑战（Junior），纯 HTML + CSS，无框架、无 JS。

- [Live site](https://youchuya.github.io/clipboard-landing-page/)
- [Challenge](https://www.frontendmentor.io/challenges)

## 学到什么

- 整页多区块布局：页头 / 左图右文 / 单图 / 三栏 / logo 墙 / CTA / 页脚
- 图片左溢出：容器 `overflow: hidden` + `transform: translateX(-100px)`
- `clamp()` 让区块间距随屏幕平滑缩放，减少媒体查询条数
- `<dl>` / `<dt>` / `<dd>` 做「功能名 + 描述」的语义列表（记得清 `dd` 默认缩进）
- 页脚导航用 `grid-auto-flow: column` + 固定两行，实现「先竖着填满再换列」
- 页脚三栏：外层负责背景满宽，内层 `max-width` + `margin-inline: auto` 让内容居中
- 两个 CTA 按钮用 `min-width` 等宽，手机上 `min-width: 0` + `width: 100%` 撑满
- 600px / 768px 断点：竖排、取消偏移、字号缩小、背景换 mobile 版

## 响应式

- 桌面：容器 1100 / 内容 700，左图右文两栏
- 手机（≤768px）：全部单列、按钮竖排撑满、页脚居中、logo 竖向排列
