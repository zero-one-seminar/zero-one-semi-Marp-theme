--- 
marp: true
math: katex
header: "header"
footer: "footer"
theme: 01semi
paginate: true
---
<!--
class: title
_paginate: false
-->
# タイトル
日付と発表者名

---
<!-- class: slides  -->
# 見出し1
## 見出し2
### 見出し3
- 箇条書き
- 箇条書き
  - hoge
  - piyo
---
# 数式も書ける
1. 順序付き箇条書き
2. 順序付き箇条書き

*斜体*
**太字**
立体

$$
  \sum^{\infty}_{n=1} \frac{1}{n^2} 
  = \frac{1}{1^2}+\frac{1}{2^2}+\frac{1}{3^2}+\frac{1}{4^2}+\cdots
  = \frac{\pi}{6}
$$

---
# コードブロック
インライン要素
`int a = 1234567890;`

ブロック要素
```python
def collatz(n):
  if n%2 == 0:
    return n/2
  else:
    return 3*n+1
```
---
# 表
|a|b|c|
|-|-|-|
|1|2|3|
|1|2|3|

---

<!-- 
_header: "" 
_footer: ""
-->
# スライドタイトル
ヘッダー・フッターなし

---
スライドタイトルなし

---
<!-- 
_header: "" 
_footer: ""
-->
ヘッダー・フッターなし
スライドタイトルなし
