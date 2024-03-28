# TextCraft-Talk
TextCraft: Enhancing Documentation with Latex and Markdown in SageMaker

# Table of Contents
1. [Greek Letters](#GreekLetters)
2. [Arrows](#Arrows)
3. [Miscellaneous Symbols](#MiscellaneousSymbols)
3. [Binary Operation/Relation Symbols](#BinaryOperationRelationSymbols)
4. [Math Constructs](#MathConstructs)
5. [Matrix](#Matrix)
6. [Aligning Equations](#AligningEquations)

<a name="GreekLetters"></a>
## Greek Letters 

|     Greek Letters      | Jupyter Notebook Upper Case |Jupyter Notebook Lower Case |
|:----------------------:|:---------------------------:|:--------------------------:|
|   &Alpha;,$`\alpha`$   |           \Alpha            |           \alpha           |
|    &Beta;,$`\beta`$    |            \Beta            |           \beta            |
|   &Gamma;,$`\gamma`$   |           \Gamma            |           \gamma           |
|   &Delta;,$`\delta`$   |           \Delta            |           \delta           |
| &Epsilon;,$`\epsilon`$ |          \Epsilon           |          \epsilon          |
|    &Zeta;,$`\zeta`$    |            \Zeta            |           \zeta            |
|     &Eta;,$`\eta`$     |            \Eta             |            \eta            |
|   &Theta;,$`\theta`$   |           \Theta            |           \theta           |
|    &Iota;,$`\iota`$    |            \Iota            |           \iota            |
|   &Kappa;,$`\kappa`$   |           \Kappa            |           \kappa           |
|  &Lambda;,$`\lambda`$  |           \Lambda           |          \lambda           |
|      &Mu;,$`\mu`$      |             \Mu             |            \mu             |
|      &Nu;,$`\nu`$      |             \NU             |            \nu             |
|      &Xi;,$`\xi`$      |             \Xi             |            \xi             |
| &Omicron;,$`\omicron`$ |          \Omicron           |          \omicron          |
|      &Pi;,$`\pi`$      |             \Pi             |            \pi             |
|     &Rho;,$`\rho`$     |            \Rho             |            \rho            |
|   &Sigma;,$`\sigma`$   |           \Sigma            |           \sigma           |
|     &Tau;,$`\tau`$     |            \Tau             |            \tau            |
| &Upsilon;,$`\upsilon`$ |          \Upsilon           |          \upsilon          |
|     &Chi;,$`\chi`$     |            \Chi             |            \chi            |
|     &Psi;,$`\psi`$     |            \Psi             |            \Psi            |
|   &Omega;,$`\omega`$   |           \Omega            |           \omega           |



<a name="Arrows"></a>
## Arrows 


|       Symbol        |   Latex Syntax   |       Symbols        |    Latex Syntax    |
|:-------------------:|:----------------:|:--------------------:|:------------------:|
|    $\leftarrow$     |   \leftarrow     |     $\Leftarrow$     |     \Leftarrow     |
|    $\rightarrow$    |   \rightarrow    |    $\Rightarrow$     |    \Rightarrow     |
|  $\leftrightarrow$  | \leftrightarrow  | $\rightleftharpoons$ | \rightleftharpoons |
|     $\uparrow$      |     \uparrow     |     $\downarrow$     |     \downarrow     |
|     $\Uparrow$      |     \Uparrow     |     $\Downarrow$     |     \Downarrow     |
|  $\Leftrightarrow$  | \Leftrightarrow  |    $\Updownarrow$    |    \Updownarrow    |
|      $\mapsto$      |     \mapsto      |    $\longmapsto$     |    \longmapsto     |
|     $\nearrow$      |     \nearrow     |      $\searrow$      |      \searrow      |
|  $\leftharpoonup$   |  \leftharpoonup  |  $\rightharpoonup$   |  \rightharpoonup   |
| $\leftharpoondown$  | \leftharpoondown | $\rightharpoondown$  | \rightharpoondown  |

<a name="MiscellaneousSymbols"></a>
## Miscellaneous Symbols 

|    Symbol    |Latex Syntax |  Symbol  | Latex Syntax |
|:------------:|:-----:|:--------:|:------------:|
|   $\infty$   | \infty|$\forall$ |   \forall    |
|   $\Re $ 	   |\Re 	| $\Im$ |     	\Im     |
|   $\nabla$   |	\nabla 	| $\exists$ |  	\exists    |
|  $\partial$  | 	\partial |	 $\nexists$  |	\nexists |  
| $\emptyset $  |  	\emptyset | $\varnothing$ | 	\varnothing|
|  $   \wp$      |	\wp 	| $\complement$|  	\complement|
|   $\neg$  	    |\neg |	 $\cdots$  |	\cdots|
|  $\square$  	  |\square |	$ \surd$ | 	\surd|
| $\blacksquare$ |  	\blacksquare |	 $\triangle$ |	\triangle|


<a name="BinaryOperationRelationSymbols"></a>
## Binary Operation/Relation Symbols 

| Symbol | Latex Syntax|  Symbol   | Latex Syntax | 
| :------: |:------: |:---------:|:------: |
|  $\times$ | 	\times | 	 $\cdot$ |  	\cdot|
| $\div$  |	\div 	|  $\cap$   |	\cap|
| $\cup$  |	\cup 	|  $\neq$   |	\neq|
| $\leq$ | 	\leq 	|  $\geq$   |	\geq|
| $\in$ | 	\in 	|  $\perp$  |	\perp|
| $\notin$ | 	\notin 	| $\subset$ | 	\subset|
| $\simeq$ | 	\simeq 	| $\approx$ | 	\approx|

<a name="MathConstructs"></a>
## Math Constructs


|         Math Construct         |                Latex Code                |                    Output                    |
|:------------------------------:|:----------------------------------------:|:--------------------------------------------:|
|            Sumation            |     Sum \sum_{n=1}^{\infty} 2^{-n}=1     |     Sum $$\sum_{n=1}^{\infty} 2^{-n}=1$$     |
|            Product             |        \[\prod_{i=a}^{b} f(i) \]         |        $$\[\prod_{i=a}^{b} f(i) \] $$        |
|           Coproduct            |            \coprod{abc}^{xyz}            |            $$\coprod{abc}^{xyz}$$            |
|            Integral            |             \int_{abc}^{xyz}             |               \int_{abc}^{xyz}               |
| Integral Over a Closed Contour |             \oint{abc}{xyz}              |             $$\oint{abc}{xyz}$$              |
|        Double integral         |            \iint_{abc}^{xyz}             |           $$\iint_{abc}^{xyz}$$              |
|            Fracton             |             \frac{abc}{xyz}              |             $$\frac{abc}{xyz}$$              |
|             Prime              |                    f`                    |                    $$f`$$                    |   
|          Square Root           |                \sqrt{abc}                |                $$\sqrt{abc}$$                |
|            Nth-Root            |              \sqrt[n]{abc}               |              $$\sqrt[n]{abc}$$               |
|            Overline            |              \overline{abc}              |              $$\overline{abc}$$              | 
|           Underline            |             \underline{abc}              |             $$\underline{abc}$$              |
|            wide hat            |              \widehat{abc}               |              $$\widehat{abc}$$               |


<a name="Matrix"></a>
## Matrix 

### 3x3 Matrix
```latex
\begin{bmatrix}
\frac{5}{6} & \frac{1}{6} & 0 \\
\frac{5}{6} & 0 & \frac{1}{6} \\
0 & \frac{5}{6} & \frac{1}{6}
\end{bmatrix}
```

$$\begin{bmatrix}
\frac{5}{6} & \frac{1}{6} & 0 \\
\frac{5}{6} & 0 & \frac{1}{6} \\
0 & \frac{5}{6} & \frac{1}{6}
\end{bmatrix}$$

### MxN Matrix
```latex
$$
A_{m,n} = 
\begin{bmatrix}
a_{1,1} &  a_{1,2} & \cdots & a_{1,n} \\ 
a_{2,1} &  a_{2,2} & \cdots & a_{2,n} \\
\vdots & \vdots & \ddots & vdots \\
a_{m,1} &  a_{m,2} & \cdots & a_{m,n}
\end{bmatrix}
$$
```
$$
A_{m,n} =
\begin{bmatrix}
a_{1,1} &  a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} &  a_{2,2} & \cdots & a_{2,n} \\
\vdots & \vdots & \ddots & vdots \\
a_{m,1} &  a_{m,2} & \cdots & a_{m,n}
\end{bmatrix}
$$

<a name="AligningEquations"></a>

```latex
\begin{align}
\sigma &= \sqrt{E\left[ \left(X -\mu\right)^2 \right] } \\
&= \sqrt{E\left[ X^2 \right]+ E\left[\left(-2\mu X\right)\right] +E\left[ \mu^2\right]} \\
&= \sqrt{E\left[ X^2 \right] -2\mu E\left[X\right] + \mu^2}\\
&= \sqrt{E\left[X^2 \right]- 2\mu^2 + \mu^2 }\\
&= \sqrt{E\left[ X^2 \right]-\mu^2}\\
&= \sqrt{E\left[ X^2 \right] - \left(E\left[X\right]\right)^2}
\end{align}
```

$$
\begin{align}
\sigma &= \sqrt{E\left[ \left(X -\mu\right)^2 \right] } \\
&= \sqrt{E\left[ X^2 \right]+ E\left[\left(-2\mu X\right)\right] +E\left[ \mu^2\right]} \\
&= \sqrt{E\left[ X^2 \right] -2\mu E\left[X\right] + \mu^2}\\
&= \sqrt{E\left[X^2 \right]- 2\mu^2 + \mu^2 }\\
&= \sqrt{E\left[ X^2 \right]-\mu^2}\\
&= \sqrt{E\left[ X^2 \right] - \left(E\left[X\right]\right)^2}
\end{align}
$$
