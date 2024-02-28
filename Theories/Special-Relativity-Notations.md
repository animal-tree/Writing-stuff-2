# Special Relativity Notations

## Definitions

### (1) Speed of light constant *in vacuo*, reference frame, and spacetime.

Let $c \coloneqq 299,792,458$ be the speed of light constant *in vacuo*.

Reference frame $K^{(i)}$ (for any $i \in \mathbb{N}$) is a coordinate system that is potentially in motion relative to other reference frames (coordinate systems likewise potentially in motion, for example $K^{(j)}$).

> Leaving this out since not a necessary constraint: ~Inertial reference frame $K^{(i)}$ (for any $i \in \mathbb{N}$) is a coordinate system that is in rectilinear (non-accelerative) motion (or stationary) relative to other inertial reference frames (other such coordinate systems, for example $K^{(j)}$).~

Any observer stationary in reference frame $K^{(i)}$ measures the corresponding time and space coordinates of a body, as $t^{(i)}  \in \mathbb{R}$ and $x_{t^{(i)}}^{(i)} \in \mathbb{R}$ respectively.

$v^{(i, j)} \in \mathbb{R}$ is the velocity of any body stationary in $K^{(j)}$ measured by any observer stationary in $K^{(i)}$.

> Can specify $v_{t^{(i)}}^{(i, j)}$ in case of acceleration of either $K^{(i)}$ or $K^{(j)}$.
>
> e.g.
>
> $v^{(i, j)} \in \mathbb{R}$ is the velocity of any body stationary in $K^{(j)}$ measured by any observer with time coordinate $t^{(i)}$ stationary in $K^{(i)}$.

### (2) Lorentz transformation.

$\mathcal{X}(X, T, V) \coloneqq \frac{X - VT}{\sqrt{1 - \frac{V^2}{c^2}}}$.

$\mathcal{T}(X, T, V) \coloneqq \frac{T - \frac{XV}{c^2}}{\sqrt{1 - \frac{V^2}{c^2}}}$.

### (3) Velocity-addition formula.

$\mathcal{V}(V, W) \coloneqq \frac{W + V}{1 + \frac{V}{c^2}W}$.

## Assumptions

### (1) Lorentz transformation.

$x_{t^{(j)}}^{(j)} \coloneqq \mathcal{X}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$.

$t^{(j)} \coloneqq \mathcal{T}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$.

The Lorentz transformation describes a transformation of a body's corresponding space and time coordinates across reference frames in physical spacetime.

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

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$ is constant, or equivalently, $\frac{\partial^2 x_{t^{(i)}}^{(i)}}{\partial {t^{(i)}}^2} = 0$.

Since average velocity is equal to displacement over time, a necessary consequence of constant $\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$ is:

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}} = \frac{x_{t_2^{(i)}}^{(i)} - x_{t_1^{(i)}}^{(i)}}{t_2^{(i)} - t_1^{(i)}}$.

### (4) $x_{0}^{(i)} = 0$.

$x_{0}^{(i)} = 0$ means that the origin ($0$-point) of reference frame $K^{(i)}$ is conformed with wherever the body (whose spatial coordinate is represented by $x_{t^{(i)}}^{(i)}$) is at time $t^{(i)} = 0$, denoted by $x_{0}^{(i)}$. If this conformation isn't already the case, then reference frame $K^{(i)}$ can be redefined such that $x_{0}^{(i)} = 0$ by means of a fixed translation in space of the measuring system, simply by subtracting the previous value of $x_{0}^{(i)}$ from all measurements of $x_{t^{(i)}}^{(i)}$. Such a re-centering has no effect on relative velocities $v^{(i,j)}$ or $v^{(j,i)}$ between observers and bodies on and across reference frames, including for those velocities referred to by the velocity-addition formula. Alternatively, if this isn't satisfying, $x_{0}^{(i)} = 0$ may also be derived directly as a necessary consequence of the constancy of light postulate, which states that $x_{t^{(i)}}^{(i)} = ct^{(i)}$: 

$x_{t^{(i)}}^{(i)} = ct^{(i)} \rightarrow x_{0}^{(i)} = c(0) = 0 \rightarrow x_{0}^{(i)} = 0$.

## Theorems

### (1) Velocity-addition formula.

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}})$.

The velocity-addition formula describes a transformation of a body's velocity across reference frames in physical spacetime.

**Proof.**

$$
\begin{align}
\quad \quad \quad \quad \quad \text{ } \text{ } \text{ } \text{ } \text{ } \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}} &= \frac{\Delta x_{t^{(j)}}^{(j)}}{\Delta t^{(j)}} \quad\quad \text{(Assumption 3)} \\
&= \frac{x_{t_2^{(j)}}^{(j)} - x_{t_1^{(j)}}^{(j)}}{t_2^{(j)} - t_1^{(j)}} \\
&= \frac{\mathcal{X}(x_{t_2^{(i)}}^{(i)}, t_2^{(i)}, v^{(i, j)}) - \mathcal{X}(x_{t_1^{(i)}}^{(i)}, t_1^{(i)}, v^{(i, j)})}{\mathcal{T}(x_{t_2^{(i)}}^{(i)}, t_2^{(i)}, v^{(i, j)}) - \mathcal{T}(x_{t_1^{(i)}}^{(i)}, t_1^{(i)}, v^{(i, j)})} \quad\quad \text{(Assumption 1)}\\
\end{align}
$$

$$
\begin{align}
\quad \quad \quad \text{ } \text{ } \text{ } \text{ } \text{ } &= \frac{\Bigg(\frac{x_{t_2^{(i)}}^{(i)} - v^{(i, j)} t_2^{(i)}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}} - \frac{x_{t_1^{(i)}}^{(i)} - v^{(i, j)} t_1^{(i)}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}\Bigg)}{\Bigg(\frac{t_2^{(i)} - \frac{v^{(i, j)} x_{t_2^{(i)}}^{(i)}}{c^2}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}} - \frac{t_1^{(i)} - \frac{v^{(i, j)} x_{t_1^{(i)}}^{(i)}}{c^2}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}\Bigg)} \quad\quad \text{(Definition 2)}\\
\end{align}
$$

$$
\begin{align}
&= \frac{\Bigg(x_{t_2^{(i)}}^{(i)} - v^{(i, j)} t_2^{(i)} - (x_{t_1^{(i)}}^{(i)} - v^{(i, j)} t_1^{(i)})\Bigg)}{\Bigg(t_2^{(i)} - \frac{v^{(i, j)} x_{t_2^{(i)}}^{(i)}}{c^2} - (t_1^{(i)} - \frac{v^{(i, j)} x_{t_1^{(i)}}^{(i)}}{c^2})\Bigg)} \\
&= \frac{\Bigg((x_{t_2^{(i)}}^{(i)} - x_{t_1^{(i)}}^{(i)}) - v^{(i, j)}(t_2^{(i)} - t_1^{(i)})\Bigg)}{\Bigg((t_2^{(i)} - t_1^{(i)}) - \frac{v^{(i, j)} (x_{t_2^{(i)}}^{(i)} - x_{t_1^{(i)}}^{(i)})}{c^2}\Bigg)} \\
&= \frac{\Delta x_{t^{(i)}}^{(i)} - v^{(i, j)} \Delta t^{(i)}}{\Delta t^{(i)} - \frac{v^{(i, j)} \Delta x_{t^{(i)}}^{(i)}}{c^2}} \\
&= \frac{(\frac{1}{\Delta t^{(i)}})(\Delta x_{t^{(i)}}^{(i)} - v^{(i, j)} \Delta t^{(i)})}{(\frac{1}{\Delta t^{(i)}})(\Delta t^{(i)} - \frac{v^{(i, j)} \Delta x_{t^{(i)}}^{(i)}}{c^2})} \\
\end{align}
$$

$$
\begin{align}
\quad \quad \text{ } \text{ } \text{ } &= \frac{\frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}} - v^{(i, j)}}{1 - \frac{v^{(i, j)}}{c^2} \frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}}} \\
&= \frac{\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} - v^{(i, j)}}{1 - \frac{v^{(i, j)}}{c^2} \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}} \quad\quad \text{(Assumption 3)}\\
&= \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}). \quad\quad \text{(Definition 3)} \quad\quad\quad \square
\end{align}
$$

## Disproofs

### (1) Joint Einstein's first postulate and velocity-addition formula usefulness

Einstein's first postulate, the constancy of the speed of light *in vacuo* across reference frames, states: $x_{t^{(i)}}^{(i)} = ct^{(i)} \text{ } \forall i$.

$$
\begin{align}
x_{t^{(i)}}^{(i)} = ct^{(i)} &\text{ and } x_{t^{(j)}}^{(j)} = ct^{(j)}  \quad\quad \text{(Einstein's first postulate)} \\
&\rightarrow \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}} = c \\
&\rightarrow c = \mathcal{V}(v^{(i, j)}, c),  \quad\quad \text{(Theorem 1)} \\
\end{align}
$$

rendering the velocity-addition formula useless.
