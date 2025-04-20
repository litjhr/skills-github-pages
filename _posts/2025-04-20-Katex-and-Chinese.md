---
title: Katex and Chinese
date: 2025-04-20
---

<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Pages 显示数学公式（KaTeX）</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.8/dist/katex.min.css"
        integrity="sha384-GvrOXuhMATgEsSwCs4smul74iXGOixntILdUW9XmUC6+HX0sLNAK3q71HotJqlAn" crossorigin="anonymous">
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.8/dist/katex.min.js"
        integrity="sha384-cpW21h6RZv/phavutF+AuVYrr+dA8xD9zs6FwLpaCct6O9ctzYFfFr4dgmgccOTx"
        crossorigin="anonymous"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.16.8/dist/contrib/auto-render.min.js"
        integrity="sha384-+VBxd3r6XgURycqtZ117nYw44OOcIax56Z4dCRWbxyPt0Koah1uHoK0o4+/RRE05"
        crossorigin="anonymous" onload="renderMathInElement(document.body);"></script>
</head>

<body>
    <!-- 行内公式 -->
    这是一个行内公式：\(E=mc^2\)

    <!-- 块级公式 -->
    <p>这是一个块级公式：</p>
    $$
    \sum_{i=1}^{n} i = \frac{n(n + 1)}{2}
    $$
</body>

</html>
