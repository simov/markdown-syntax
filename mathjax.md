
# MathJax

## Delimiters

| Delimiter                         | Delimiters  | Example                     | Result                    | Support
| :---                              | :---:       | :---                        | :---:                     | :---:
| No delimiters                     | `str`       | `\sqrt{3x-1}+(1+x)^2`       | \sqrt{3x-1}+(1+x)^2       | no
| Bracket without backslash         | `[str]`     | `[\sqrt{3x-1}+(1+x)^2]`     | [\sqrt{3x-1}+(1+x)^2]     | no
| Single backslash with bracket     | `\[str\]`   | `\[\sqrt{3x-1}+(1+x)^2\]`   | \[\sqrt{3x-1}+(1+x)^2\]   | **yes**
| Double backslash with bracket     | `\\[str\\]` | `\\[\sqrt{3x-1}+(1+x)^2\\]` | \\[\sqrt{3x-1}+(1+x)^2\\] | no
| Parentheses without backslash     | `(str)`     | `(\sqrt{3x-1}+(1+x)^2)`     | (\sqrt{3x-1}+(1+x)^2)     | no
| Single backslash with parentheses | `\(str\)`   | `\(\sqrt{3x-1}+(1+x)^2\)`   | \(\sqrt{3x-1}+(1+x)^2\)   | **yes**
| Double backslash with parentheses | `\\(str\\)` | `\\(\sqrt{3x-1}+(1+x)^2\\)` | \\(\sqrt{3x-1}+(1+x)^2\\) | no
| Single dollar sign                | `$str$`     | `$\sqrt{3x-1}+(1+x)^2$`     | $\sqrt{3x-1}+(1+x)^2$     | **yes**
| Double dollar sign                | `$$str$$`   | `$$\sqrt{3x-1}+(1+x)^2$$`   | $$\sqrt{3x-1}+(1+x)^2$$   | **yes**

## Empty

- `\(\)` \(\)
- `$$` $$
- `\[\]` \[\]
- `$$$$` $$$$

## Single Character

- `\(a\)` \(a\)
- `$a$` $a$
- `\[a\]` \[a\]
- `$$a$$` $$a$$

## Multiple on single line

- `\(a\)` \(a\) `\(b\)` \(b\)
- `$a$` $a$ `$b$` $b$
- `\[a\]` \[a\] `\[b\]` \[b\]
- `$$a$$` $$a$$ `$$b$$` $$b$$

## Underscore `_`

## `\(` single line `\)`

`\(x_i = x_\gamma\)` \(x_i = x_\gamma\)

## `\(` multiline `\)`

```
\(
x_i = x_\gamma
\)
```

\(
x_i = x_\gamma
\)

---

## `\[` single line `\]`

`\[x_i = x_\gamma\]` \[x_i = x_\gamma\]

## `\[` multiline `\]`

```
\[
x_i = x_\gamma
\]
```

\[
x_i = x_\gamma
\]

---

## `$` single line `$`

`$x_i = x_\gamma$` $x_i = x_\gamma$

## `$` multiline `$`

```
$
x_i = x_\gamma
$
```

$
x_i = x_\gamma
$

---

## `$$` single line `$$`

`$$x_i = x_\gamma$$` $$x_i = x_\gamma$$

## `$$` multiline `$$`

```
$$
x_i = x_\gamma
$$
```

$$
x_i = x_\gamma
$$

---

## `\begin{}` multiline `\end{}`

```
\begin{align}
x_i = x_\gamma
\end{align}
```

\begin{align}
x_i = x_\gamma
\end{align}

---

## Escapes

### Dollar Sign

- `\$6.20` and `\$0.5` - \$6.20 and \$0.5

- `$4.40` - $4.40

- `\\$1 \\$2` - \\$1 \\$2

---

# Examples

# Using TeX notation

When $a \ne 0$, there are two solutions to \(ax^2 + bx + c = 0\) and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

---

# Several examples of TeX equations

## The Lorenz Equations

\begin{align}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{align}

## The Cauchy-Schwarz Inequality

\[
\left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
 \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
\]

## A Cross Product Formula

\[
  \mathbf{V}_1 \times \mathbf{V}_2 =
   \begin{vmatrix}
    \mathbf{i} & \mathbf{j} & \mathbf{k} \\
    \frac{\partial X}{\partial u} & \frac{\partial Y}{\partial u} & 0 \\
    \frac{\partial X}{\partial v} & \frac{\partial Y}{\partial v} & 0 \\
   \end{vmatrix}
\]

## The probability of getting \(k\) heads when flipping \(n\) coins is:

\[P(E) = {n \choose k} p^k (1-p)^{ n-k} \]

## An Identity of Ramanujan

\[
   \frac{1}{(\sqrt{\phi \sqrt{5}}-\phi) e^{\frac25 \pi}} =
     1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
      {1+\frac{e^{-8\pi}} {1+\ldots} } } }
\]

## A Rogers-Ramanujan Identity

\[
  1 +  \frac{q^2}{(1-q)}+\frac{q^6}{(1-q)(1-q^2)}+\cdots =
    \prod_{j=0}^{\infty}\frac{1}{(1-q^{5j+2})(1-q^{5j+3})},
     \quad\quad \text{for $|q|<1$}.
\]

## Maxwell's Equations

\begin{align}
  \nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} & = \frac{4\pi}{c}\vec{\mathbf{j}} \\
  \nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\
  \nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\
  \nabla \cdot \vec{\mathbf{B}} & = 0
\end{align}

## Stochastic Simulation

Input: $\mathbf{X}_i = (X_{1i}, \ldots, X_{ki})$

Output: $\mathbf{Y}_i = h(\mathbf{X}_i)$

Analysis:

$$Pr(h(\mathbf{X}) \le b) \approx \frac{1}{N} \sum_{i=1}^N I(h(\mathbf{X}_i) \le b)$$
$$E(h(\mathbf{X})) \approx \frac{1}{N} \sum_{i=1}^N h(\mathbf{X}_i)$$

## In-line Mathematics

Finally, while display equations look good for a page of samples, the
ability to mix math and text in a paragraph is also important.  This
expression \(\sqrt{3x-1}+(1+x)^2\) is an example of an inline equation.  As
you see, MathJax equations can be used this way as well, without unduly
disturbing the spacing between lines.

---

# Misc

- $E = mc^2$

- \( A_i = B_i + C_i \sum_{k=0}^{i} D_k E^k \)

- \begin{eqnarray}
  A_i &=& B_i + C_i \sum_{k=0}^{i} D_k E^k \\
  F_i &=& \int_{-\infty}^{x_i} f(x) dx
\end{eqnarray}

- $\frac{w_x}{\sum_z x_z}$
- $\frac{w}{\sum_{z} x_z}$
- $x_\gamma = x_i$
- $x_i = x_\gamma$

Cost function of logistic regression (revision):

$$J(\theta) = - \frac{1}{m} \sum_{i=1}^m [ y^{(i)}\ \log (h_\theta (x^{(i)})) + (1 - y^{(i)})\ \log (1 - h_\theta(x^{(i)}))] + \frac{\lambda}{2m}\sum_{j=1}^n \theta_j^2$$

For Neural Networks, it is:

$$
J(\Theta) = - \frac{1}{m} \sum_{i=1}^m \sum_{k=1}^K \left[y^{(i)}_k \log ((h_\Theta (x^{(i)}))_k) + (1 - y^{(i)}_k)\log (1 - (h_\Theta(x^{(i)}))_k)\right] + \frac{\lambda}{2m}\sum_{l=1}^{L-1} \sum_{p=1}^{s_l} \sum_{n=1}^{s_{l+1}} ( \Theta_{n,p}^{(l)})^2
$$

Commutative diagrams using `\array` or `\newcommand`:

$$
\newcommand{\ra}[1]{\!\!\!\!\!\!\!\!\!\!\!\!\xrightarrow{\quad#1\quad}\!\!\!\!\!\!\!\!}
\newcommand{\da}[1]{\left\downarrow{\scriptstyle#1}\vphantom{\displaystyle\int_0^1}\right.}
%
\begin{array}{llllllllllll} 0 & \ra{f_1} & A & \ra{f_2} & B & \ra{f_3} & C & \ra{f_4} & D & \ra{f_5} & 0 \\
\da{g_1} & & \da{g_2} & & \da{g_3} & & \da{g_4} & & \da{g_5} & & \da{g_6} \\
0 & \ra{h_1} & 0 & \ra{h_2} & E & \ra{h_3} & F & \ra{h_4} & 0 & \ra{h_5} & 0 \\
\end{array}
$$

$$
\begin{array}{ccccccccc}
0 & \xrightarrow{i} & A & \xrightarrow{f} & B & \xrightarrow{q} & C & \xrightarrow{d} & 0 \\
\downarrow & \searrow & \downarrow & \nearrow & \downarrow & \searrow & \downarrow & \nearrow & \downarrow \\
0 & \xrightarrow{j} & D & \xrightarrow{g} & E & \xrightarrow{r} & F & \xrightarrow{e} & 0
\end{array}
$$

---

# Formatting

- $\textbf{bold}$

- $\textit{italic}$

- $\mathtt{Typewriter}$

- $\mathscr{script}$

- $\mathcal{CALLIGRAPHIC}$

- $\mathfrak{Fraktur}$

---

# TeX/LaTeX Extensions

- $\mathtip{math}{tip}$

- $\toggle{math1}{math2}\endtoggle$

- $\circeq \lesseqqgtr$

- $
\bbox[red]{x+y}
\bbox[2pt]{x+1}
\bbox[red,2pt]{x+1}
\bbox[5px, border: 2px solid red]{x+1}
$

- $\boldsymbol{A}$

- $\bra{1}$

- $$
\begin{prooftree}
\AxiomC{}
\RightLabel{Hyp$^{1}$}
\UnaryInfC{$P$}
\AXC{$P\to Q$}
\RL{$\to_E$}
\BIC{$Q^2$}
\AXC{$Q\to R$}
\RL{$\to_E$}
\BIC{$R$}
\AXC{$Q$}
\RL{Rit$^2$}
\UIC{$Q$}
\RL{$\wedge_I$}
\BIC{$Q\wedge R$}
\RL{$\to_I$$^1$}
\UIC{$P\to Q\wedge R$}
\end{prooftree}
$$

- $\cancel{math}$

- $
\require{centernot}
\begin{array}{c}
  A \not\longrightarrow B\\
  A \centernot\longrightarrow B
\end{array}
$

- $\color{red}{x} \color{black}+ \color{blue}{y}$

- $
\require{colortbl}
\begin{array}{|l|c|}
  \rowcolor[gray]{.5}\columncolor{red} one & two\\
  \rowcolor{lightblue} three & four\\\hline
  five & six \\
  \rowcolor{magenta}seven & \cellcolor{green}eight
\end{array}
$

- $
\require{empheq}
\empheqbiglbrack
$

- $
\enclose{circle}[mathcolor="red"]{x}
\enclose{circle}[mathcolor="red"]{\color{black}{x}}
\enclose{circle,box}{x}
\enclose{circle}{\enclose{box}{x}}
$

- $
\require{gensymb}
\celsius
\degree
\micro
\ohm
\perthousand
$

- $
\ce{C6H5-CHO}
\ce{$A$ ->[\ce{+H2O}] $B$}
\ce{SO4^2- + Ba^2+ -> BaSO4 v}
$

- $
\require{physics}
\ket{\psi}=\frac{1}{\sqrt{2}}(\ket{00}+\ket{11})
$

- $
\unicode{65}                        % the character 'A'
\unicode{x41}                       % the character 'A'
\unicode[.55,0.05]{x22D6}           % less-than with dot, with height .55em and depth 0.05em
\unicode[.55,0.05][Geramond]{x22D6} % same taken from Geramond font
\unicode[Garamond]{x22D6}           % same, but with default height, depth of .8em,.2em
$

- $
\require{upgreek}
\upalpha
\upbeta
\upchi
\updelta
$

- $\verb|\sqrt{x}|$
