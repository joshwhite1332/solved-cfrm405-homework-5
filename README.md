Download Link: https://assignmentchef.com/product/solved-cfrm405-homework-5
<br>
<ol>

 <li>Give an example of a 2 × 2 matrix that has no real eigenvectors. Justify your solution with intuition (without solving completely for the eigenvectors and eigenvalues).</li>

 <li>Consider an <em>n</em>×<em>p </em>matrix <em>A</em>. Show that the number of linear independent rows is the same as the number of linearly independent columns.</li>

</ol>

Hint: Write <em>A </em>= <em>CR </em>where <em>C </em>is a matrix of the linearly independent columns of <em>A</em>. Why can we write <em>A </em>like this? Then consider the <em>CR </em>product in the “row” interpretation of matrix multiplication.

<ol start="3">

 <li>Let <em>A </em>be an <em>m</em>×<em>n </em>matrix (assume <em>m &gt; n</em>). The full singular value factorization <em>A </em>= <em>U</em>Σ<em>V </em><sup>T </sup>contains more information than necessary to reconstruct <em>A</em>.

  <ul>

   <li>What are the smallest matrices <em>U</em><sup>˜</sup>, Σ and<sup>˜ </sup><em>V</em><sup>˜</sup><sup>T </sup>such that <em>U</em><sup>˜</sup>Σ<sup>˜</sup><em>V</em><sup>˜</sup><sup>T </sup>= <em>A</em>?</li>

   <li>Let . That is, think about <em>U </em>from the full singular value factorization as a block matrix consisting of the matrix <em>U</em>˜ found in part (a) and the remaining (unneeded) columns <em>U</em>ˆ.</li>

  </ul></li>

</ol>

Find expressions for <em>U</em><sup>˜</sup><sup>T</sup><em>U</em><sup>˜ </sup>and <em>U</em><sup>˜</sup><em>U</em><sup>˜</sup><sup>T</sup>.

<ul>

 <li>Use the <em>reduced </em>singular value factorization obtained in part (a) to find an expression for the matrix <em>H </em>= <em>A</em>(<em>A</em><sup>T</sup><em>A</em>)<sup>−1</sup><em>A</em><sup>T</sup>. How many matrices must be inverted (diagonal and orthogonal matrices don’t count)?</li>

</ul>

<ol start="4">

 <li>Let <em>x </em>and <em>y </em>be vectors of <em>m </em> The least squares solution for a best-fit line for a plot of <em>y </em>versus <em>x </em>is</li>

</ol>

<em>β</em>ˆ = (<em>X</em>T<em>X</em>)−1<em>X</em>T<em>y</em>

where

<ul>

 <li>Suppose you know the <strong>full </strong>singular value factorization <em>X </em>= <em>U</em>Σ<em>V </em><sup>T</sup>. Find an expression for <em>β</em><sup>ˆ </sup>in terms of <em>U</em>, Σ, and <em>V </em>. Hint: Only square matrices can be invertible.</li>

 <li>Repeat part (a) using the reduced singular value factorization <em>X </em>= <em>U</em><sup>˜</sup>Σ<sup>˜</sup><em>V</em><sup>˜</sup><sup>T</sup>.</li>

</ul>

<ol start="5">

 <li>Let <em>X</em>˜ be an <em>m </em>× <em>n </em>matrix (<em>m &gt; n</em>) whose columns have sample mean zero, and let <em>X</em><sup>˜ </sup>= <em>U</em><sup>˜</sup>Σ<sup>˜</sup><em>V</em><sup>˜</sup><sup>T </sup>be a reduced singular value factorization of <em>X</em><sup>˜</sup>. The squared <em>Mahalanobis </em>distance to the point ˜<em>x<sub>i</sub></em><sup>T </sup>(the <em>i</em><sup>th </sup>row of <em>X</em><sup>˜</sup>) is</li>

</ol>

<em>d</em>2<em>i </em>= <em>x</em>˜<em>i</em>T<em>S</em>ˆ−1<em>x</em>˜<em>i</em>

where        = cov(<em>X</em><sup>˜</sup>). Explain how to compute <em>d</em><sup>2</sup><em><sub>i </sub></em>without inverting a matrix.

<ol start="6">

 <li>(a) Suppose <em>A </em>= <em>LU </em>where <em>L </em>is lower triangular and <em>U </em>is upper triangular. Explain how you would solve the problem <em>Ax </em>= <em>b </em>using <em>L</em>, <em>U</em>, and the concepts of forward and backward substitution.</li>

</ol>

(b) Compute the LU factorization of

<ul>

 <li>2 −1<sup></sup></li>

</ul>

−3      2 <sub></sub>

<ul>

 <li>1 1</li>

</ul>

by hand using elimination matrices.