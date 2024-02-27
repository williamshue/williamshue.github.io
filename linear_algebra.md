---
layout: page
math: mathjax
title: Linear Algebra
permalink: /linear_algebra/
---

$$\begin{align*}
\textbf{Method 1: Subtracting Equations} \\
\text{Subtracting Equation 2 from Equation 1:} \\
(2x + y) - (x - 3y) &= 5 - 2 \\
2x + y - x + 3y &= 3 \\
x + 4y &= 3 \\
\text{Now, we have a new equation:} & x + 4y = 3, \text{and we still have Equation 2:} x - 3y = 2. \\
\text{Now, we can solve this new system using methods like substitution or elimination.} \\
\text{From Equation 2: } & x = 3y + 2 \\
\text{Substitute } x \text{ into Equation 1:} \\
3y + 2 + 4y &= 3 \\
7y + 2 &= 3 \\
7y &= 1 \\
y &= \frac{1}{7} \\
\text{Substitute } y \text{ back into Equation 2 to find } x: \\
x &= 3\left(\frac{1}{7}\right) + 2 \\
x &= \frac{3}{7} + 2 \\
x &= \frac{17}{7} \\
\text{So, the solution using the method of subtracting equations is } & x = \frac{17}{7} \text{ and } y = \frac{1}{7}.
\end{align*}$$

$$\begin{align*}
2x + y &= 5 \\
x - 3y &= 2
\end{align*}$$



$$\begin{align*}
(2x + y) - (x - 3y) &= 5 - 2 \\
2x + y - x + 3y &= 3 \\
x + 4y &= 3
\end{align*}$$

So we take a **linear** system (no squared terms etc.) and convert it to a matrix:

$$\begin{bmatrix}
2 & 1 & | & 5 \\
1 & -3 & | & 2 \\
\end{bmatrix}$$

<!-- # A Symmetric Matrix 

$$

A = \begin{bmatrix}
    3 & 2 & 4 & 1 \\
    2 & 4 & 1 & 5 \\
    4 & 1 & 6 & 3 \\
    1 & 5 & 3 & 7
\end{bmatrix}

$$ -->

<!-- <iframe src="/assets/pdfs/CSE_6740__Final_Project_Report.pdf" width="600" height="400"></iframe> -->

<!-- <object data="/assets/pdfs/CSE_6740__Final_Project_Report.pdf" type="application/pdf" width="600" height="400">
    <p>Your browser does not support PDFs. <a href="/assets/pdfs/CSE_6740__Final_Project_Report.pdf">Download the PDF</a>.</p>
</object> -->