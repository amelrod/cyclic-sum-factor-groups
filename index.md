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

<!-- <form method="GET">
  <label for="height">Height:</label>
  <input type="number" id="height" name="height"><br><br>
  <input type="submit" value="Submit">
</form> -->

<form>
  <label for="height">Height:</label>
  <input type="number" id="height" name="height"><br><br>
</form>

<!-- <script>
  var name = window.prompt("Enter your name: ");
  alert("Name: " + name);
</script> -->

<script type="text/tikz">
  \begin{tikzpicture}
    \draw (0,0) -- (0,document.getElementById("height").value);
    \draw (0,0) -- (6,0);
  \end{tikzpicture}
</script>

