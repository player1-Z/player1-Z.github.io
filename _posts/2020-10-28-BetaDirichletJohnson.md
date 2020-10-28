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
Beta分布有两个正值参数: $\alpha$和$\beta$，Beta分布表示为$Beta(a,b)=\frac{x^{\alpha -1}*(1-x)^{\beta -1}}{B(\alpha,\beta)}$，其中$B$为Beta函数。  
Beta分布的均值(期望值)为: $E(X)=\frac{\alpha}{\alpha +\beta}$。  
Beta分布的方差为: $\frac{\alpha *\beta}{(\alpha +\beta)^2*(\alpha +\beta +1)}$。  


## 充足性假设
由W.E.Johnson在1920s提出，
