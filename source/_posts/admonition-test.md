---
title: Admonition Style Test
date: 2016-03-02
updated: 2016-03-02
---
## Admonition

Python markdown实现中扩展了markdown的语法，让其支持了[admonition][]。标准markdown语法是不支持的，但我们可以直接在markdown中写html来*粗暴的*实现admonition。

[admonition]: https://pythonhosted.org/Markdown/extensions/admonition.html

### note / info /tips

<div class="admonition note"><p class="admonition-title">Note</p><p>Admonition is not supported in markdown natively.</p>So we need to write some htmls manually.<p></p></div>


### warning / important

<div class="admonition warning"><p class="admonition-title">Warning</p><p>Don't walk on the street alone, after 12:00 pm.</p></div>

### danger / critical

<div class="admonition danger"><p class="admonition-title">Danger</p><p>Boooooom!!!</p></div>

### 中文 

<div class="admonition note"><p class="admonition-title">Note</p><p>原生markdown并不支持admonition。</p><p>所以我们必须要自己手写一些html。</p></div>

