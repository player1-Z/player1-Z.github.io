---
layout: default
title: "无差别原理,熵与贝叶斯"
tags: blogs
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

## 派别
**客观学派**   
  逻辑学派: Keynes, Jeffreys  
  频率学派: Venn，Reichenbach，von Mises   
  倾向性学派: Peirce，Popper，Hacking，Gillies   
**主观学派**  
  客观贝叶斯: Jeynes，Carnap，Williamson  
  主观贝叶斯: Ramsey，De Finett，Savage  
  
## 无差别原理
无差别原理(Principle of Indifference)，又不充分理由原则(Principle of Insufficient Reason)，最早由拉普拉斯提出，由凯恩斯正式确立术语。  
内容: 当无任何已知信息可以为两种可能性赋予不同概率时，应赋予其相同概率。  
基于该原理，拉普拉斯确立了后继规则(Rule of Succession): 当事件连续发生$m$次，该事件在下一次发生概率为$\frac{m+1}{m+2}$。  
在该原理基础上可以推出均匀分布(Uniform Distribution)的先验概率，从而与最大熵原理(Principle of Maximum Entropy)产生联系。  

## 最大熵原理
由Jeynes提出，其1957的论文还将统计物理学中的熵还原为信息论中的熵。  
从最大熵原理同样可以得出均匀分布的先验概率，另外还可以得到概率更新规则(Updating Rule)，即在获得新信息时将对事件的先验概率更新为后验概率的规则。  
由此最大熵原理推演出的两个结果分别与无差别原理和贝叶斯概率更新规则(Beyasian Updating Rule)产生联系，并分化出许多观点流派。  
Shimony将最大熵原理视为无差别原理的精细版。  
Skyrms将最大熵原理视为贝叶斯定理的特例，而Williams/Seidenfeld/Lukits持相反观点。  
