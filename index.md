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

Direct Sums of Cyclic Groups

We will explore the geometric intuition hiding in 

$$ (\mathbb{Z}_m \oplus \mathbb{Z}_n)/ \langle x,y \rangle $$

<script type="text/tikz">
    \begin{tikzpicture}[
      roundnode/.style={circle, draw=green!60, fill=green!5, very thick, minimum size=7mm},
      squarednode/.style={rectangle, draw=red!60, fill=red!5, very thick, minimum size=5mm},
      ]
      %Nodes
      \node[squarednode]      (maintopic)                              {2};
      \node[roundnode]        (uppercircle)       [above=of maintopic] {1};
      \node[squarednode]      (rightsquare)       [right=of maintopic] {3};
      \node[roundnode]        (lowercircle)       [below=of maintopic] {4};

      %Lines
      \draw[->] (uppercircle.south) -- (maintopic.north);
      \draw[->] (maintopic.east) -- (rightsquare.west);
      \draw[->] (rightsquare.south) .. controls +(down:7mm) and +(right:7mm) .. (lowercircle.east);
  \end{tikzpicture}
</script>

