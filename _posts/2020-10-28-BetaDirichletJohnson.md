---
layout: default
title: "充足性,Beta与Dirichlet分布"
tags: notes
---
<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

## Beta分布
无差别原理的推论之一即均匀的先验概率分布，这也与最大熵原理相关。  
但是均匀的先验概率分布并不适用于所有情况。在19世纪末到20世纪初，Hardy与Whitworth相互独立地提出了利用Beta概率分布描述先验概率分布，即Beta Priors。  
Beta分布表示的是概率的概率，例如在抛硬币结果序列前对"两种随机变量之一的概率为50%"赋予的概率的连续分布。  
Beta分布有两个正值参数: $\alpha$和$\beta$，Beta分布表示为$Beta(a,b)=\frac{x^{\alpha -1}(1-x)^{\beta -1}}{B(\alpha,\beta)}$，其中$B$为Beta函数。  
Beta分布的均值(期望值)为: $E(X)=\frac{\alpha}{\alpha +\beta}$。  
Beta分布的方差为: $\frac{\alpha\beta}{(\alpha +\beta)^2(\alpha +\beta +1)}$。  
Beta分布是Bernoulli/二项分布/负二项分布和几何分布的共轭先验分布。  
当$\alpha$与$\beta$都取值为1时，Beta分布即为均匀分布。由此可见，无差别原理仅为Beta分布的特例。  
<img src="https://pic4.zhimg.com/50/v2-c8a881146a1d2ee3423a38242d971022_hd.webp?source=1940ef5c" width="250" height="" alt=""/>  
  
## Dirichlet分布
Dirichlet分布是将Beta分布由二项分布推广到多项分布后的共轭分布。

## 充足性假设
由W.E.Johnson在1920s提出，其实质即将Hardy与Whitworth的Beta先验分布扩充为多项分布的Dirichlet先验分布。  
值得一提的是，卡尔纳普在1952年提出的归纳方法的连续统(The Continuum of Inductive Methods)也是将其1950年的归纳逻辑系统发展成具有Dirichlet先验分布的系统。  
