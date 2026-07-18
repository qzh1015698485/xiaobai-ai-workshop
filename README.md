# 小白AI工坊 — 网站素材包

## 📁 文件结构

```
xiaobai_website/
├── images/              ← 所有图片放这里
│   ├── xiaobai_main.png         (Hero主视觉)
│   ├── xiaobai_正面.jpg         (IP画廊·正面)
│   ├── xiaobai_引导.jpg         (IP画廊·引导)
│   ├── xiaobai_侧脸.jpg         (IP画廊·侧脸)
│   ├── xiaobai_回眸.jpg         (IP画廊·回眸)
│   ├── xiaobai_cheer.jpg        (底部装饰)
│   ├── bg_dataflow.jpg          (背景氛围)
│   ├── bg_focus.jpg             (氛围)
│   ├── 小白_CORE核心形态.jpg    (四种形态·可选展示)
│   ├── 小白_ANALYST数据形态.jpg
│   ├── 小白_GUARDIAN防护形态.jpg
│   ├── 小白_ADVISOR企业顾问.jpg
│   ├── 小白_Q版.jpg             (趣味元素)
│   ├── 小白_微信头像.jpg
│   ├── 表情_01_收到.jpg ~ 表情_08_无语.jpg  (互动表情)
│   ├── 数据大屏讲解.jpg         (文章配图用)
│   └── 数据流环绕全景.jpg       (文章配图用)
│
└── index.html           ← 让Codex生成这个文件
```

## ✅ 给Codex的提示词

打开ChatGPT Plus → Codex → 粘贴这段话：

```
帮我做一个个人网站「小白AI工坊」，一个建材人折腾AI的真实记录。

设计要求：
- 暗黑底色 + 青色(#00d4ff) + 金色(#FDD000) 配色
- 赛博科技感，但内容扎实不浮夸
- 全前端单页HTML，不要后端
- 所有图片路径：images/文件名

页面结构：
1. 导航栏 + 暗黑/亮色切换 + 滚动进度条
2. Hero区：左文案右图片（images/xiaobai_main.png）
3. 三大模块卡片：🔧工具箱 / 📝笔记 / 👤关于我
4. 工具区：美缝计用量计算器 + 报价生成器 + 色卡搭配（真交互）
5. 笔记区：8篇文章·分类筛选·弹窗阅读·点赞收藏（localStorage）
6. 四格IP画廊：images/xiaobai_正面/引导/侧脸/回眸.jpg
7. 关于页：基本信息 + 时间线
8. 数据面板：Chart.js 趋势图+排行图
9. 底部联系
10. 回到顶部按钮
```

## 💡 说明

- 图片已全部整理好，无需额外下载
- 如果Codex生成的HTML里图片路径不对，改成 images/文件名
- 上线时整个文件夹上传到服务器或托管到 Vercel/GitHub Pages 就行
- 想换图直接替换 images/ 下的对应文件，不用改代码
