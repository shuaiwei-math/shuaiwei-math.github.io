---
layout: post
title: The distributions of primes
date: 2023-09-18 07:36:00-0400
description: 
tags: math bib
categories: sample-posts
giscus_comments: true
related_posts: false
related_publications: 
---
<!-- This post shows how to add bibliography to simple blog posts. If you would like something more academic, check the [distill style post]({% post_url 2018-12-22-distill %}). -->

    For $$x \in \mathbb N$$,
    \begin{equation}
        \pi(n) = \sharp\, \\{p \leq n \mid p \text{ is prime}\\}. 
    \end{equation}
    Then 
    \begin{equation}
    \pi(x) \sim \int_2^{x} \frac{1}{\ln t}dt,
    \end{equation}
    which is the prime number theory. The concept map and proof process can be seen from: <a href="../../../assets/pdf/conceptMap.pdf">Concept Map</a> A little bit work shows then
    \begin{equation}
    \pi(x) \sim \frac{x}{\ln x}.
    \end{equation}
    But $$\int_2^{x} \frac{1}{\ln t}dt$$ is a better approximation to $\pi(x)$$ than $$\frac{x}{\log x}$$ is. \par
    RH = Riemann Hypothesis (approximately): For any $\epsilon > 0$, 
    \begin{equation}
    \abs{\pi(x) - \operatorname{Li}(x)} = O\bigl(x^{\frac{1}{2} + \epsilon}\bigr).
    \end{equation}
    More careful analysis shows that $$\operatorname{Li}(x) = \frac{x}{\log x} + \frac{x}{(\log x)^{2}} + O\bigl(\frac{x}{(\log x)^{3}}\bigr)$$. So if RH is true, 
    \begin{equation}
    \abs{\pi(x)-\frac{x}{\log x}} \sim \frac{x}{(\log x)^{2}}.
    \end{equation}
\end{fact}
