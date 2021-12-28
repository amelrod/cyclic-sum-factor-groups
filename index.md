#Direct Sums of Cyclic Groups

We will investigate sums of cyclic groups, their subgroups, and their quotients. We will attempt to gain intuition for these various structures via a geometric interpretation.

First we will explore the general structure of cyclic sums via graphing an integer lattice. We will then intuit the reasoning why
$$ \mathbb{Z}_m \oplus \mathbb{Z}_n \cong \mathbb{Z}_{mn}. $$
when $n$ and $m$ are coprime. Following this, we will explore the general structure of cyclic subgroups and attempt to develop a geometric heuristic for determining the order of an element. That is, we will explain how
$$ \abs{(x,y)} = \lcm(\abs{x},\abs{y}). $$
Then we will examine groups of the form
$$ (\mathbb{Z}_m \oplus \mathbb{Z}_n)/ \langle x,y \rangle $$











<head>
  <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      tex2jax: {
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
        inlineMath: [['$','$']]
      }
    });
  </script>
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
  <link rel="stylesheet" type="text/css" href="https://tikzjax.com/v1/fonts.css">
  <script src="https://tikzjax.com/v1/tikzjax.js"></script>
</head>
