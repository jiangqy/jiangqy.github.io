---
layout: gridlay
sitemap: false
link: tips
image: tips.jpg
title: "Tips for Usage of Latex Table, Figure and Algorithm"
authors: Qing-Yuan Jiang
type: tool
intro: Latex table, image, algorithm typesetting usage for academic paper.
usemathjax : true
---

# Tips for Usage of Latex Table, Figure and Algorithm

* Author: Qing-Yuan Jiang

<!-- This article provides examples of using [Latex](#latex) and [Python](#python) to create illustrations for academic research papers. -->

## 1. Tables <a name="table"></a>

### 1.1. Specify Table Cell Width

```latex
\documentclass{article}

\usepackage[paperheight=2cm,paperwidth=12cm,left=0cm, right=0cm, top=0cm, bottom=0cm]{geometry}

\usepackage{array}
\newcommand{\PreserveBackslash}[1]{\let\temp=\\#1\let\\=\temp}
\newcolumntype{C}[1]{>{\PreserveBackslash\centering}p{#1}}
\newcolumntype{R}[1]{>{\PreserveBackslash\raggedleft}p{#1}}
\newcolumntype{L}[1]{>{\PreserveBackslash\raggedright}p{#1}}

\begin{document}
\begin{table}\centering
\caption{Example 1: specifying cell width.}
\begin{tabular}{|C{1cm}|C{2cm}|R{3cm}|L{3cm}|}
\hline
A & B & Country & Destination\\\hline
A & B & Country & Destination\\
\hline
\end{tabular}
\end{table}
\end{document}
```

* Illustration:
<object data="{{ site.url }}{{ site.baseurl }}/notes/tips/tab1.pdf#view=FitH" width="100%" height="200" type="application/pdf"></object>

## 2. Figures <a name="figure"></a>

by using: $$\boldsymbol{R}$$

$$\boldsymbol{R}$$

by using: $$\phi(\gamma)$$

$$a^2 + b^2 = c^2$$

by using: $a^2 + b^2 = c^2$

$a^2 + b^2 = c^2$
