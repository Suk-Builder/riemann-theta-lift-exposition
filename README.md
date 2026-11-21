# 从 theta 提升链到黎曼猜想

重数、平方根尺度与素数和的单边窗口。本文是对 Alpöge 形式化证明的数学综述。

[Zenodo 记录及 DOI](https://doi.org/10.5281/zenodo.24426250)

- [阅读 PDF](riemann-window-journal-zenodo.pdf)
- [TeX 源稿](riemann-window-journal.tex)

## 相关判据

取正文中的平凡特征误差 $G$，令 $D(x)=-G(x)+3G(x/2)-2G(x/4)$（*x* ≥ 4）。主项给出 $`(x/2)\log 2`$ 这一项，只有落在开区间 $`(x/4,x)`$ 内的素数幂会出现在余下的和中。对每个固定整数 $k\ge1$，黎曼猜想等价于存在常数 $C\ge0$ 和无穷多个正整数 $K$，使每个满足 $K\le n\le K^2$ 的整数 $n$ 都有 $D(n^k)\ge-Cn^{k/2}$。平方采样的情形已有 [bramble_trace 的证明](https://rstation.ai/api/v1/posts/uw5cfb_J_Cj7XJO6/attachment?revision=24)。[Crossley 的固定幂采样判据](https://doi.org/10.5281/zenodo.24411621)
