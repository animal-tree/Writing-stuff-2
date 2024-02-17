# Disproving experimental evidence

The constancy of light postulate Einstein uses to derive the Lorentz transformation necessitates:

$x = ct$

$\rightarrow \frac{\partial x}{\partial t} = c$

and

$x' = ct'$

$\rightarrow \frac{\partial x'}{\partial t'} = c$.

However, this contradicts pretty much all experimentally tested velocities $\frac{\partial x}{\partial t} \neq c$, e.g. an electron or light through a medium.

The Fizeau experiment, for example, one of the main corroborations of the theory, used the velocity addition formula and computed both $\frac{\partial x}{\partial t} \neq c$ and $\frac{\partial x'}{\partial t'} \neq c$.

## Deriving the velocity addition formula 

Assume the Lorentz transformation. We have:

$\partial x = \frac{\partial x' + v \partial t'}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\partial t = \frac{\partial t' + \frac{v \partial x'}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\frac{\partial x}{\partial t} = \frac{\frac{\partial x' + v \partial t'}{\sqrt{1 - \frac{v^2}{c^2}}}}{\frac{\partial t' + \frac{v \partial x'}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}} = \frac{\partial x' + v \partial t'}{\partial t' + \frac{v \partial x'}{c^2}} = \frac{\frac{1}{\partial t'}(\partial x' + v \partial t')}{\frac{1}{\partial t'}(\partial t' + \frac{v \partial x'}{c^2})} = \frac{\frac{\partial x'}{\partial t'} + v}{1 + \frac{v}{c^2}\frac{\partial x'}{\partial t'}}$

## Deriving the velocity addition formula - Most rigorously

In case the above doesn't satisfy one's preference of rigor, here is a derivation from absolute scratch.

### Definitions.

**(1) Speed of light constant *in vacuo*, reference frame, and spacetime.**

Let $c \coloneqq 299,792,458$ be the speed of light constant.

Reference frame $K^{(i)}$ (for any $i \in \mathbb{N}$) has time points $t^{(i)}  \in \mathbb{R}$ and corresponding spatial coordinates $x_{t^{(i)}}^{(i)} \in \mathbb{R}$.

$v^{(i, j)} \in \mathbb{R}$ is the velocity of $K^{(j)}$ measured by an observer on $K^{(i)}$.

**(2) Lorentz transformation.**

$\mathcal{X}(X, T, V) \coloneqq \frac{X - VT}{\sqrt{1 - \frac{V^2}{c^2}}}$

$\mathcal{T}(X, T, V) \coloneqq \frac{T - \frac{XV}{c^2}}{\sqrt{1 - \frac{V^2}{c^2}}}$

**(3) Velocity-addition formula.** 

$\mathcal{V}(V, W) \coloneqq \frac{W + V}{1 + \frac{V}{c^2}W}$.

### Assumptions

**(1) Lorentz transformation.**

$x_{t^{(j)}}^{(j)} \coloneqq \mathcal{X}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$

$t^{(j)} \coloneqq \mathcal{T}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$

The Lorentz transformation describes reference frame transformations in physical spacetime.

**(2) Mutual velocity perspective.**

$v^{(i, j)} \coloneqq -v^{(j, i)}$

This is assumed generally as well as in Einstein's second postulate ("the principle of relativity").

<!--
**(3) Einstein's first postulate: The speed of light *in vacuo* across all reference frames is constant.**

$x_{t^{(i)}}^{(i)} = c t^{(i)}$

**(4)** $\frac{\partial x}{\partial t} \neq c$.

As assumed in most experimentally tested setups, e.g., Fizeau.
-->

**(3) Uniform motion ($K^{(i)}$ is an inertial reference frame).**

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$ is constant.

This is assumed in special relativity.

**(4) $x_{0}^{(i)} = 0$.**

This is assumed in special relativity and derivable from the constancy of light postulate $x_{t^{(i)}}^{(i)} = ct^{(i)} \rightarrow x_{0}^{(i)} = c(0) = 0$.

### Theorems

**(1) Velocity-addition formula.** 

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}})$.

The velocity-addition formula describes reference frame velocity transformations in physical spacetime.

**Proof.**

$$
\begin{align}
  \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} &= \frac{x_{t^{(i)}}^{(i)} - x_{0}^{(i)}}{t^{(i)} - 0} \quad\quad \text{(Assumption 3)}\\
  \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} &= \frac{x_{t^{(i)}}^{(i)}}{t^{(i)}} \quad\quad \text{(Assumption 4)}\\
  &= \frac{\mathcal{X}(x_{t^{(j)}}^{(j)}, t^{(j)}, v^{(j, i)})}{\mathcal{T}( x_{t^{(j)}}^{(j)}, t^{(j)}, v^{(j, i)})} \quad\quad \text{(Assumption 1)}\\
  &= \frac{\mathcal{X}(x_{t^{(j)}}^{(j)}, t^{(j)}, -v^{(i, j)})}{\mathcal{T}( x_{t^{(j)}}^{(j)}, t^{(j)}, -v^{(i, j)})} \quad\quad \text{(Assumption 2)}\\
\end{align}
$$

$$
\begin{align}
  &= \frac{\Bigg(\frac{x_{t^{(j)}}^{(j)} + v^{(i, j)} t^{(j)}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}\Bigg)}{\Bigg(\frac{t^{(j)} + \frac{v^{(i, j)} x_{t^{(j)}}^{(j)}}{c^2}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}\Bigg)} \quad\quad \text{(Definition 2)}\\
  &= \frac{x_{t^{(j)}}^{(j)} + v^{(i, j)} t^{(j)}}{t^{(j)} + \frac{v^{(i, j)} x_{t^{(j)}}^{(j)}}{c^2}} \\
  &= \frac{(\frac{1}{t^{(j)}})(x_{t^{(j)}}^{(j)} + v^{(i, j)} t^{(j)})}{(\frac{1}{t^{(j)}})(t^{(j)} + \frac{v^{(i, j)} x_{t^{(j)}}^{(j)}}{c^2})}\\
\end{align}
$$


$$
\begin{align}
&= \frac{\frac{x_{t^{(j)}}^{(j)}}{t^{(j)}} + v^{(i, j)}}{1 + \frac{v^{(i, j)}}{c^2}\frac{x_{t^{(j)}}^{(j)}}{t^{(j)}}} \\
&= \frac{\frac{x_{t^{(j)}}^{(j)} - x_{0}^{(j)}}{t^{(j)} - 0} + v^{(i, j)}}{1 + \frac{v^{(i, j)}}{c^2}\frac{x_{t^{(j)}}^{(j)}- x_{0}^{(j)}}{t^{(j)} - 0}} \quad\quad \text{(Assumption 4)} \\
&= \frac{\frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}} + v^{(i, j)}}{1 + \frac{v^{(i, j)}}{c^2}\frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}}} \quad\quad \text{(Assumption 3)}\\
&= \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}}) \quad\quad\quad \square
\end{align}
$$

> Note: The velocity-addition formula can't actually be true at the same time as Einstein's first postulate, unless the object in motion is traveling at exactly the speed of light, e.g., not an electron or any experimentally tested massive object, or even light traveling through a medium. One or the other has to go.
