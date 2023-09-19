---
layout: post
title: The distributions of primes
date: 2023-09-18 07:36:00-0400
description: 
tags: formatting math
categories: sample-posts
# giscus_comments: true
related_posts: false
# related_publications: 
---
<!-- This post shows how to add bibliography to simple blog posts. If you would like something more academic, check the [distill style post]({% post_url 2018-12-22-distill %}). -->

For $$x \in \mathbb N$$,
\begin{equation}
    \pi(n) = \sharp\, \\{p = n \mid p \text{ is prime}\\}. 
\end{equation}
Then 
\begin{equation}
    \pi(x) \sim \int_2^{x} \frac{1}{\ln t}dt = \text{Li}(x),
\end{equation}
    