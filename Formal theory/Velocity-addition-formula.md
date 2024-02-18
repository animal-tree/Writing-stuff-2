# Disproving experimental evidence

Einstein used his first postulate, the constancy of the speed of light *in vacuo* across reference frames, to derive the Lorentz transformation. This postulate states and necessitates the following:

$x = ct$

$\rightarrow \frac{\partial x}{\partial t} = c$

and

$x' = ct'$

$\rightarrow \frac{\partial x'}{\partial t'} = c$.

However, for pretty much all experimentally tested and applied bodies representing $x$, *e.g.*, an electron or light propagating through a medium, the body's velocity is measurably below the speed of light *in vacuo* constant: $\frac{\partial x}{\partial t} < c$.

The Fizeau experiment, for example, one of the main corroborations of the special theory of relativity, used the velocity addition formula on light traveling through the medium of water, where it was assumed and computed both: $\frac{\partial x}{\partial t} \neq c$ and $\frac{\partial x'}{\partial t'} \neq c$.

> Einstein assumed $x$ and $x'$ to be the spatial coordinate points (for reference frames $K$ and $K'$ respectively) of a single light beam, *in vacuo* —  or otherwise of some object traveling at speed $c$, independent to reference frame — in the first postulate. There is no circumventing that, despite the ubiquitous misunderstanding. Below, the misunderstanding is emphasized via this postulate's implication to the velocity addition formula.

## Velocity addition formula 

### Deriving the velocity addition formula 

Assume the Lorentz transformation. We have:

$\partial x = \frac{\partial x' + v \partial t'}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\partial t = \frac{\partial t' + \frac{v \partial x'}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\frac{\partial x}{\partial t} = \frac{\frac{\partial x' + v \partial t'}{\sqrt{1 - \frac{v^2}{c^2}}}}{\frac{\partial t' + \frac{v \partial x'}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}} = \frac{\partial x' + v \partial t'}{\partial t' + \frac{v \partial x'}{c^2}} = \frac{\frac{1}{\partial t'}(\partial x' + v \partial t')}{\frac{1}{\partial t'}(\partial t' + \frac{v \partial x'}{c^2})} = \frac{\frac{\partial x'}{\partial t'} + v}{1 + \frac{v}{c^2}\frac{\partial x'}{\partial t'}}$.

### Utility of the velocity addition formula 

This commonly used formula therefore cannot in principle be usable in combination with Einstein's first postulate since the latter requires $\frac{\partial x}{\partial t}  = \frac{\partial x'}{\partial t'} = c$ always. Substituting as such the above gives us:

$$
\begin{align}
&\frac{\partial x}{\partial t} = \frac{\frac{\partial x'}{\partial t'} + v}{1 + \frac{v}{c^2}\frac{\partial x'}{\partial t'}} \\
&\rightarrow c = \frac{c + v}{1 + \frac{v}{c^2}c} \\
&\rightarrow c = \frac{c + v}{1 + \frac{v}{c}} \\
&\rightarrow c(1 + \frac{v}{c}) = c + v \\
&\rightarrow c + v = c + v \\
&\rightarrow 1 = 1, \\
\end{align}
$$

rendering the formula useless.

# Deriving the velocity addition formula (most rigorously)

In case the above derivation of the velocity addition formula doesn't satisfy one's preference of rigor, here is a derivation of the velocity addition formula from absolute scratch. This derivation is besides the point of the earlier disproof, and is constructed just as a simple but rigorous derivation of the velocity addition formula, for educating and organizing's-sake.

## Definitions.

### (1) Speed of light constant *in vacuo*, reference frame, and spacetime.

Let $c \coloneqq 299,792,458$ be the speed of light constant *in vacuo*.

A body on reference frame $K^{(i)}$, for any $i \in \mathbb{N}$, has time points $t^{(i)}  \in \mathbb{R}$ and corresponding spatial coordinates $x_{t^{(i)}}^{(i)} \in \mathbb{R}$.

$v^{(i, j)} \in \mathbb{R}$ is the velocity of any stationary body on $K^{(j)}$ measured by any stationary observer on $K^{(i)}$.

### (2) Lorentz transformation.

$\mathcal{X}(X, T, V) \coloneqq \frac{X - VT}{\sqrt{1 - \frac{V^2}{c^2}}}$.

$\mathcal{T}(X, T, V) \coloneqq \frac{T - \frac{XV}{c^2}}{\sqrt{1 - \frac{V^2}{c^2}}}$.

### (3) Velocity-addition formula.

$\mathcal{V}(V, W) \coloneqq \frac{W + V}{1 + \frac{V}{c^2}W}$.

## Assumptions

### (1) Lorentz transformation.

$x_{t^{(j)}}^{(j)} \coloneqq \mathcal{X}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$.

$t^{(j)} \coloneqq \mathcal{T}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$.

The Lorentz transformation describes reference frame transformations of a body's position and corresponding time in physical spacetime.

### (2) Mutual velocity perspective.

$v^{(i, j)} \coloneqq -v^{(j, i)}$.

This is assumed generally as well as in Einstein's second postulate ("the principle of relativity").

<!--
**(3) Einstein's first postulate: The speed of light *in vacuo* across all reference frames is constant.**

$x_{t^{(i)}}^{(i)} = c t^{(i)}$

**(4)** $\frac{\partial x}{\partial t} \neq c$.

As assumed in most experimentally tested setups, e.g., Fizeau.
-->

### (3) Uniform motion.

$K^{(i)}$ is an inertial reference frame:

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$ is constant, or equivalently, $\frac{\partial^2 x_{t^{(i)}}^{(i)}}{\partial {t^{(i)}}^2} = 0$.

This is always assumed in special relativity.

Since average velocity is equal to displacement over time, a necessary consequence of constant $\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$ is:

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}} = \frac{x_{t^{(i)}}^{(i)} - x_{0}^{(i)}}{t^{(i)} - 0}$.

### (4) $x_{0}^{(i)} = 0$.

The origin of any reference frame $K^{(i)}$ is conformed with wherever $x_{0}^{(i)}$ is. If not already the case, reference frame $K^{(i)}$ can be redefined such that $x_{0}^{(i)} = 0$ by means of a fixed translation in space of the measuring system. Such a re-centering has no effect on relative velocities $v^{(i,j)}$ or $v^{(j,i)}$ between observers and bodies on and across reference frames. Alternatively, if this isn't satisfying, $x_{0}^{(i)} = 0$ may also be derived directly as a necessary consequence of the constancy of light postulate, which states that $x_{t^{(i)}}^{(i)} = ct^{(i)}$: 

$x_{t^{(i)}}^{(i)} = ct^{(i)} \rightarrow x_{0}^{(i)} = c(0) = 0 \rightarrow x_{0}^{(i)} = 0$.

## Theorems

### (1) Velocity-addition formula.

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}})$.

The velocity-addition formula describes reference frame transformations of a body's velocity in physical spacetime.

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
\quad \text{ }\text{ }&= \frac{\frac{x_{t^{(j)}}^{(j)}}{t^{(j)}} + v^{(i, j)}}{1 + \frac{v^{(i, j)}}{c^2}\frac{x_{t^{(j)}}^{(j)}}{t^{(j)}}} \\
&= \frac{\frac{x_{t^{(j)}}^{(j)} - x_{0}^{(j)}}{t^{(j)} - 0} + v^{(i, j)}}{1 + \frac{v^{(i, j)}}{c^2}\frac{x_{t^{(j)}}^{(j)}- x_{0}^{(j)}}{t^{(j)} - 0}} \quad\quad \text{(Assumption 4)} \\
&= \frac{\frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}} + v^{(i, j)}}{1 + \frac{v^{(i, j)}}{c^2}\frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}}} \quad\quad \text{(Assumption 3)}\\
&= \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}}). \quad\quad\quad \square
\end{align}
$$

> Note: The velocity-addition formula can't actually be true at the same time as Einstein's first postulate, unless the object in motion is traveling at exactly the speed of light, e.g., not an electron or any experimentally tested massive object, or even light traveling through a medium. One or the other has to go.
