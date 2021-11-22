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

<form id="myForm" action="/action_page.php">
  <label for="height">Height:</label>
  <input type="number" id="height" name="height" value="1"><br><br>
</form>

<button onclick="myFunction()"> Try it </button>

<script type="text/tikz">
  function myFunction() {
    var x = document.getElementById("myForm").elements[0].value;
    document.getElementById("demo").innerHTML = x;
  }
  \begin{tikzpicture}
    \draw (0,0) -- (0,x);
    \draw (0,0) -- (6,0);
  \end{tikzpicture}
</script>

