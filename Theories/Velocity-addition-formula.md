# Disproving experimental evidence

Einstein used his first postulate, the constancy of the speed of light *in vacuo* across reference frames, to derive the Lorentz transformation. This postulate states and necessitates the following:

$x = ct$

$\rightarrow \frac{\partial x}{\partial t} = c$

and

$x' = ct'$

$\rightarrow \frac{\partial x'}{\partial t'} = c$.

However, for pretty much all bodies described by $x$ in experiment and application, *e.g.*, an electron, the body's velocity $\frac{\partial x}{\partial t}$ is measured or presumed below the speed of light *in vacuo* constant: $\frac{\partial x}{\partial t} < c$. These use cases cannot be valid at the same time as $x = ct$ is necessitated by Einstein's first postulate, since $x = ct \rightarrow \frac{\partial x}{\partial t} = c$.

The Fizeau experiment, for example, one of the main corroborations of the special theory of relativity, used the velocity-addition formula on a light beam's position through a tube of flowing water, describing the light beam's position in the respective reference frames of the tube and the contained flowing water medium, with $\frac{\partial x}{\partial t} \neq c$ measured, and $\frac{\partial x'}{\partial t'} \neq c$ assumed.

Such applications of Einstein's theory can't be valid at the same time as Einstein's first postulate. The object in motion must be defined to travel at exactly the speed of light: $\frac{\partial x}{\partial t} = \frac{\partial x'}{\partial t'} = c$ by implication of Einstein's first postulate. Einstein's first postulate is necessary to his derivation of the Lorentz transformation, and the latter is necessary to the derivation of the velocity-addition formula.

## Velocity-addition formula 

In the first postulate, Einstein defined $x$ and $x'$ as spatial coordinates in two reference frames $K$ and $K'$ respectively such that the body whose position is represented by these spatial coordinates is always measured as traveling at speed $c$, independent to reference frame. Namely, he described a beam of light, *in vacuo*, emitting from the intersecting origins of the reference frames. The referent body of $x$ and $x'$ must have speed $c$ in both reference frames. Popularly, this principle is known as the "constancy of light", but mathematically it's known as $x = ct$ and $x' = ct'$. This principle's direct implication ($\frac{\partial x}{\partial t} = \frac{\partial x'}{\partial t'} = c$), together with the velocity-addition formula and its ubiquitous usage, will make this point for me, that there is a huge, ubiquitous misuse and misunderstanding between the theory in practice and principle.

### Deriving the velocity-addition formula 

Assume the Lorentz transformation. We have:

$\partial x' = \frac{\partial x - v \partial t}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\partial t' = \frac{\partial t - \frac{v \partial x}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\frac{\partial x'}{\partial t'} = \frac{\frac{\partial x - v \partial t}{\sqrt{1 - \frac{v^2}{c^2}}}}{\frac{\partial t - \frac{v \partial x}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}} = \frac{\partial x - v \partial t}{\partial t - \frac{v \partial x}{c^2}} = \frac{\frac{1}{\partial t}(\partial x - v \partial t)}{\frac{1}{\partial t}(\partial t - \frac{v \partial x}{c^2})} = \frac{\frac{\partial x}{\partial t} - v}{1 - \frac{v}{c^2}\frac{\partial x}{\partial t}}$.

### Utility of the velocity-addition formula 

This commonly used formula cannot in principle be usable in combination with Einstein's first postulate since the latter requires $\frac{\partial x}{\partial t}  = \frac{\partial x'}{\partial t'} = c$ always. Substituting as such the above gives us:

$$
\begin{align}
&\frac{\partial x'}{\partial t'} = \frac{\frac{\partial x}{\partial t} - v}{1 - \frac{v}{c^2}\frac{\partial x}{\partial t}} \\
&\rightarrow c = \frac{c - v}{1 - \frac{v}{c^2}c} \\
&\rightarrow c = \frac{c - v}{1 - \frac{v}{c}} \\
&\rightarrow c(1 - \frac{v}{c}) = c - v \\
&\rightarrow c - v = c - v \\
&\rightarrow 1 = 1, \\
\end{align}
$$

rendering the formula useless.

# Deriving the velocity-addition formula (most rigorously)

In case the above derivation of the velocity-addition formula doesn't satisfy one's preference of rigor, here is a derivation of the velocity-addition formula from absolute scratch, as a simple but rigorous derivation of the velocity-addition formula, for educating and organizing's-sake.

## Definitions

### (1) Speed of light constant *in vacuo*, reference frame, and spacetime.

Let $c \coloneqq 299,792,458$ be the speed of light constant *in vacuo*.

Reference frame $K^{(i)}$ (for any $i \in \mathbb{N}$) is a coordinate system that is potentially in motion relative to other reference frames (coordinate systems likewise potentially in motion, for example $K^{(j)}$).

Any observer stationary in reference frame $K^{(i)}$ measures the corresponding time and space coordinates of a body, as $t^{(i)}  \in \mathbb{R}$ and $x_{t^{(i)}}^{(i)} \in \mathbb{R}$ respectively.

$v^{(i, j)} \in \mathbb{R}$ is the velocity of any body stationary in $K^{(j)}$ measured by any observer stationary in $K^{(i)}$.

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

### (2) Uniform motion.

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$ is constant, or equivalently, $\frac{\partial^2 x_{t^{(i)}}^{(i)}}{\partial {t^{(i)}}^2} = 0$.

Since average velocity is equal to displacement over time, a necessary consequence of constant $\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$ is:

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}} = \frac{x_{t_2^{(i)}}^{(i)} - x_{t_1^{(i)}}^{(i)}}{t_2^{(i)} - t_1^{(i)}}$.

## Theorems

### (1) Velocity-addition formula.

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} = \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}})$.

The velocity-addition formula describes a transformation of a body's velocity across reference frames in physical spacetime.

**Proof.**

$$
\begin{align}
\quad \quad \quad \quad \quad \text{ } \text{ } \text{ } \text{ } \text{ } \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}} &= \frac{\Delta x_{t^{(j)}}^{(j)}}{\Delta t^{(j)}} \quad\quad \text{(Assumption 2)} \\
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
&= \frac{\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} - v^{(i, j)}}{1 - \frac{v^{(i, j)}}{c^2} \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}} \quad\quad \text{(Assumption 2)}\\
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
