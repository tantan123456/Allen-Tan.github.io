---
# ===== 论文条目模板 =====
# 用法：把本文件复制成 _publications/YYYY-MM-DD-简短英文标题.md，改掉下面各项。
# 本文件带 published: false，不会出现在网站上，可以长期留着当备忘录。

title: "论文标题"
collection: publications
category: manuscripts        # 可选值：books（专著）/ manuscripts（期刊论文）/ conferences（会议论文）
permalink: /publication/2026-01-01-short-name
excerpt: '一句话摘要，会显示在论文列表里。'
date: 2026-01-01              # 发表年月，决定列表排序
venue: '期刊或会议全称'
paperurl: '/files/xxx.pdf'    # PDF 放在 files/ 目录下；没有公开版就整行删掉
slidesurl: ''                 # 可选：报告幻灯片，同样放在 files/
codeurl: ''                   # 可选：代码仓库链接
citation: 'Tan, Z., et al. (2026). "论文标题." <i>期刊名</i>. 1(1), 1-10.'
published: false
---

这里写论文的详细介绍，会出现在该论文的独立页面上。支持 Markdown、公式（用 $$...$$）和图片。

<!-- 需要 BibTeX 引用块时，把下面这段的注释去掉并替换内容：
<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight">
<code>@article{key,
  title   = {论文标题},
  author  = {Tan, Zhen and others},
  journal = {期刊名},
  year    = {2026}
}
</code></pre></div></div>
-->
