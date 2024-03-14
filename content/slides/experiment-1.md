---
marp: true
theme: gaia
paginate: true
math: katex
_class: lead
---

<!-- #REGION -->
<style>
:root {
  font-family: "Fira Sans", "Sans";
}

section {
  font-size: 32px;
}


h1, h2, h3 {
  text-align: center;
}

h1 {
  font-size: 1em;
  font-weight: normal;
  color: blue;
}

h2, h3 {
  font-size: 1em;
  font-weight: normal;
}

b, strong {
   color: blue;
   font-style: normal;
   font-weight: 500;
}

b, em {
   color: red;
   font-style: normal;
}

.columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
}
</style>    
<!-- #ENDREGION -->


# 博弈论: 实验一

## 湖南大学课程

---

# 猜数字博弈

- 每位同学选择一个 0 到 1000 之间的数.
- 具体要求:
  - 不能低于 0, 可以选0.
  - 不能高于 1000, 可以选 1000.
  - 可以选小数, 比如 3.14.
  - 不符合以上要求的, 视为无效策略. 直接出局.

- 收集完所有同学报告的数字后, 计算这些数字的平均数, **和平均数的 2/3 最接近的同学获胜.**

---

https://send2me.cn/CdsZT0n1/RRO_SM-yjEeITA









