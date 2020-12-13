---
layout: default
title: "遍历定理与可交换性"
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

## 可交换性与表示定理
de Finetti的想法其实很简单，就是将客观学派的伯努利大数定律和中心极限定理表示(represent)为主观学派的观点。  
方法也很简单，就是将客观学派"事件独立性"(independence)的观点替换为"事件的可交换性"(exchangeability)。  
基于一系列事件中每个事件的可交换性，这一系列中某类事件发生的概率保持恒常，于是得到大数定律的翻版。  
并且可以得到表示定理：$w_r^{(n)}=\tbinom{n}{r}\int_0^1p^r(1-p)^{n-r}dF(p)$，等号左边为事件的概率，右边为频率的计算。  

## 平稳过程与遍历分解
平稳过程(stationary process)是一种其统计特性不会随着时间变化的随机过程(stochastic proccess)。  
统计特性包括概率分布及相关参数，如方差与期望值。  
具有遍历性的严平稳过程可以从其一次实现就推断出整个序列的性质。    
Plato(不是古希腊的那个柏拉图而是曾执教于赫尔辛基的逻辑学家与哲学家Jan von Plato)认为，de Finetti的可交换性实际上是平稳过程的遍历分解的特例。  
所谓的遍历分解指的是将一个严平稳序列分解成遍历部分，且每个部分都保持了原序列的统计性质，如频率的极限保持不变。  
但是Plato同样认为，因为平稳过程及其遍历分解通常带有物理性质，用于描述相关的物理客体，因此并非所有的客观频率都可以通过de Finetti的表示定理表示为主观的概率。  
  
更多关于时间序列的知识，推荐这篇北大李东风的这边备课笔记，地址：[应用时间序列分析备课笔记](https://www.math.pku.edu.cn/teachers/lidf/course/atsa/atsanotes/html/_atsanotes/index.html#%E8%AF%BE%E7%A8%8B%E5%86%85%E5%AE%B9)。
  
  
