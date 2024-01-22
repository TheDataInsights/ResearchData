<div class="center">

<div class="large">

**Applied Linear Algebra in Data Analysis**  

</div>

**Vectors Assignment**

</div>

------------------------------------------------------------------------

<div class="large">

**Marks: 30**

</div>

Please upload the solutions to the programming questions on this link:
[<u>Assignment 1</u>](https://forms.gle/bZWAFWjm9yRcwkEa9)

1.  Is this set of vectors
    $\\left\\{\\begin{bmatrix}2 \\\\ 1 \\\\ 1\\end{bmatrix}, \\begin{bmatrix}0 \\\\ 0\\\\ 0\\end{bmatrix}, \\begin{bmatrix}0 \\\\ 1 \\\\ 0\\end{bmatrix}\\right\\}$
    independent?

    Explain your answer. **\[Marks: 2\]**

2.  Consider a set of finite duration discrete-time real signals
    **\[Marks: 2\]**
    $$X_N = \\ensuremath\\left\\{x\\ensuremath\\left\[n\\ensuremath\\right\] \\big\\vert x\\ensuremath\\left\[n\\ensuremath\\right\] \\in \\ensuremath\\mathbb{R}, \\,\\forall 0 \\leq n \\leq N-1\\ensuremath\\right\\}$$

    Does this set form a vector space? Explain your answer. Would
    *X*<sub>*N*</sub> still be a vector space if the signals were binary
    signals? i.e.
    $x\\ensuremath\\left\[n\\ensuremath\\right\] \\in \\ensuremath\\mathbb{B}$,
    where
    $\\ensuremath\\mathbb{B} = \\ensuremath\\left\\{0, 1\\ensuremath\\right\\}$
    with the binary addition and multiplication operations defined as
    the following,

    <div class="center">

    | *a* | *b* | *a* + *b* | *a* × *b* |
    |:---:|:---:|:---------:|:---------:|
    |  0  |  0  |     0     |     0     |
    |  0  |  1  |     1     |     0     |
    |  1  |  0  |     1     |     0     |
    |  1  |  1  |     0     |     1     |

      

    </div>

3.  Prove the following for
    $\\ensuremath\\mathbf{x}, \\ensuremath\\mathbf{y} \\in \\mathbb{R}^n$,

    1.  **Triangle Inequality**: **\[Marks: 1\]**
        $$\\left\\lVert \\ensuremath\\mathbf{x} + \\ensuremath\\mathbf{y}\\right\\rVert \\leq \\left\\lVert \\ensuremath\\mathbf{x}\\right\\rVert + \\left\\lVert \\ensuremath\\mathbf{y}\\right\\rVert$$

    2.  **Backward Triangle Inequality**: **\[Marks: 1\]**
        $$\\left\\lVert \\ensuremath\\mathbf{x} - \\ensuremath\\mathbf{y}\\right\\rVert  \\geq \\left\\lvert \\left\\lVert \\ensuremath\\mathbf{x}\\right\\rVert - \\left\\lVert \\ensuremath\\mathbf{y}\\right\\rVert \\right\\rvert$$

    3.  **Parallelogram Identity**: **\[Marks: 1\]**
        $$\\frac{1}{2} \\left(\\left\\lVert \\ensuremath\\mathbf{x} + \\ensuremath\\mathbf{y}\\right\\rVert^2 + \\left\\lVert \\ensuremath\\mathbf{x} - \\ensuremath\\mathbf{y}\\right\\rVert^2 \\right) = \\left\\lVert \\ensuremath\\mathbf{x}\\right\\rVert^2 + \\left\\lVert \\ensuremath\\mathbf{y}\\right\\rVert^2$$

4.  Consider a set of vectors
    $\\ensuremath\\mathbf{x}, \\ensuremath\\mathbf{y} \\in \\mathbb{R}^n$.
    When is
    $\\left\\lVert \\ensuremath\\mathbf{x} - \\ensuremath\\mathbf{y} \\right\\rVert = \\left\\lVert \\ensuremath\\mathbf{x} + \\ensuremath\\mathbf{y}\\right\\rVert$?
    What can you say about the geometry of the vectors
    $\\ensuremath\\mathbf{x},\\,\\ensuremath\\mathbf{y},\\,\\ensuremath\\mathbf{x} - \\ensuremath\\mathbf{y}$
    and $\\ensuremath\\mathbf{x} + \\ensuremath\\mathbf{y}$? **\[Marks:
    2\]**

5.  If *S*<sub>1</sub>, *S*<sub>2</sub> ⊆ *V* are subspaces of *V* then,
    is *S*<sub>1</sub> ∩ *S*<sub>2</sub> a subspace? Demonstrate your
    answer. **\[Marks: 2\]**

6.  Prove that the sum of two subspaces
    *S*<sub>1</sub>, *S*<sub>2</sub> ⊆ *V* is a subspace. **\[Marks:
    1\]**

7.  Consider a vector
    $\\ensuremath\\mathbf{v} = \\begin{bmatrix\*}v_1 & v_2 & \\cdots & v_n\\end{bmatrix\*}^\\top$.
    Express the following in-terms of inner product between a constant
    vector $\\ensuremath\\mathbf{u}$ and the given vector
    $\\ensuremath\\mathbf{v}$, and in each case specify the vector
    $\\ensuremath\\mathbf{u}$. **\[Marks: 3\]**

    1.  $\\sum\_{i=1}^n v_i$

    2.  $\\frac{1}{n}\\sum\_{i=1}^n v_i$

    3.  $\\frac{1}{5}\\sum\_{i=3}^5 v_i$

8.  Which of the following are linear functions of
    {*x*<sub>1</sub>,*x*<sub>2</sub>,…,*x*<sub>*n*</sub>}? **\[Marks:
    3\]**

    1.  min<sub>*i*</sub>{*x*<sub>*i*</sub>}<sub>*i* = 1</sub><sup>*n*</sup>

    2.  $\\left(\\sum\_{i=1}^n x_i^2\\right)^{1/2}$

    3.  *x*<sub>6</sub>

9.  Consider a linear function *f* : ℝ<sup>*n*</sup> → ℝ. Prove that
    every linear function of this form can be represented in the
    following form. **\[Marks: 2\]**
    $$y = f\\left(\\ensuremath\\mathbf{x}\\right) = \\ensuremath\\mathbf{w}^\\top\\ensuremath\\mathbf{x} = \\sum\_{i=1}^{n}w_ix_i, \\,\\,\\,\\,\\, \\ensuremath\\mathbf{x}, \\ensuremath\\mathbf{w} \\in \\mathbb{R}^n$$

10. An *affine* function *f* is defined as the sum of a linear function
    and a constant. It can in general be represented in the form,
    $$y = f\\left(\\ensuremath\\mathbf{x}\\right) = \\ensuremath\\mathbf{w}^\\top\\ensuremath\\mathbf{x} + \\beta, \\,\\,\\,\\,\\, \\ensuremath\\mathbf{x}, \\ensuremath\\mathbf{w} \\in \\mathbb{R}^n, \\, \\beta \\in \\mathbb{R}$$
    Prove that affine functions are not linear. Prove that any affine
    function can be represented in the form
    $\\ensuremath\\mathbf{w}^\\top\\ensuremath\\mathbf{x} + \\beta$.
    **\[Marks: 2\]**

11. Consider a basis
    $B = \\left\\{\\ensuremath\\mathbf{b}\_i\\right\\}\_{i=1}^{n}$ of
    $\\ensuremath\\mathbb{R}^n$. Let the vectors
    $\\ensuremath\\mathbf{x}$ and $\\ensuremath\\mathbf{x}\_b$ be the
    representations in the standard and *B* basis respectively.
    $$\\ensuremath\\mathbf{x} = \\begin{bmatrix\*}x_1\\\\x_2\\\\\\vdots\\\\x_n\\end{bmatrix\*} = \\sum\_{i=1}^{n}x_i\\ensuremath\\mathbf{e}\_i \\,\\,\\,\\,\\, \\text{and} \\,\\,\\,\\,\\, \\ensuremath\\mathbf{x}\_b =  \\begin{bmatrix\*}x\_{b1}\\\\x\_{b2}\\\\\\vdots\\\\x\_{bn}\\end{bmatrix\*} = \\sum\_{i=1}^{n}x\_{bi}\\ensuremath\\mathbf{b}\_i$$

    Evaluate the
    $\\left\\lVert \\ensuremath\\mathbf{x}\\right\\rVert_2^2$ and
    $\\left\\lVert \\ensuremath\\mathbf{x}\_b\\right\\rVert_2^2$.
    Determine what happens to
    $\\left\\lVert \\ensuremath\\mathbf{x}\_b\\right\\rVert_2^2$ under
    the following conditions on the basis vectors: **\[Marks: 2\]**

    1.  $\\left\\lVert \\ensuremath\\mathbf{b}\_i\\right\\rVert = 1, \\forall i$

    2.  $\\left\\lVert \\ensuremath\\mathbf{b}\_i^\\top\\ensuremath\\mathbf{b}\_j\\right\\rVert = \\begin{cases}
                1 & i = j\\\\
                0 & i \\neq j
                \\end{cases}$

12. <span style="color: blue">**\[Programming\]**</span> Consider a set
    of measurements made from adult male subjects, where their height,
    weight and BMI (body mass index) were recorded and stored as vectors
    of length three; the first element is the height in *c**m*, second
    is the weight in *K**g*, and the last is the BMI. Consider the
    following four subjects,
    $$\\ensuremath\\mathbf{s}\_1 =  \\begin{bmatrix\*}\[r\]167\\\\102\\\\36.6\\end{bmatrix\*}; \\,\\,
        \\ensuremath\\mathbf{s}\_2 =  \\begin{bmatrix\*}\[r\]180\\\\87\\\\26.9\\end{bmatrix\*}$$
    $$\\ensuremath\\mathbf{s}\_3 =  \\begin{bmatrix\*}\[r\]177\\\\78\\\\24.9\\end{bmatrix\*}; \\,\\,
        \\ensuremath\\mathbf{s}\_4 =  \\begin{bmatrix\*}\[r\]152\\\\76\\\\32.9\\end{bmatrix\*}$$

    You can use the distance between these vectors
    $\\left\\lVert \\ensuremath\\mathbf{s}\_i - \\ensuremath\\mathbf{s}\_j\\right\\rVert_2$
    as a measure of the similiarity between the four subjects. Generate
    a 4 × 4 table comparing the distance of each subject with respect to
    another subject; the diagonal elements of this table will be zero,
    and it will be symmetric about the main diagonal.

    \(a\) Based on this table, how do the different subjects compare to
    each other? **\[Marks: 1\]**

    \(b\) How do the similarities change if the height had been measured
    in *m* instead of *c**m*? Can you explain this difference?
    **\[Marks: 1\]**

    \(c\) Consider the weighted norm presented in one of the earlier
    problems.
    $$\\left\\lVert x \\right\\rVert\_\\ensuremath\\mathbf{w} = \\left(w_1 x_1^2 + w_2 x_2^2 + \\cdots + w_n x_n^2\\right)^{\\frac{1}{2}}$$
    Will this fix the problem? What would be a good choice for
    $\\ensuremath\\mathbf{w}$ to address the problems with comparing
    distance between vectors due to unit change?**\[Marks: 2\]**

    \(d\) Can the angle between two vectors be used as a measure of
    similarity between vectors? Does this suffer from the problem of
    $\\left\\lVert \\ensuremath\\mathbf{x} \\right\\rVert_2$? **\[Marks:
    2\]**
