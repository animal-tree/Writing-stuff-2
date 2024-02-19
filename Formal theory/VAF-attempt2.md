# "Average-velocity"-addition formula

$$
\begin{align}
\frac{\Delta x_{t^{(j)}}^{(j)}}{\Delta t^{(j)}} &= \frac{x_{t_2^{(j)}}^{(j)} - x_{t_1^{(j)}}^{(j)}}{t_2^{(j)} - t_1^{(j)}}\\
&= \frac{\Bigg(\frac{x_{t_2^{(i)}}^{(i)} - v^{(i, j)} t_2^{(i)}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}} - \frac{x_{t_1^{(i)}}^{(i)} - v^{(i, j)} t_1^{(i)}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}\Bigg)}{\Bigg(\frac{t_2^{(i)} - \frac{v^{(i, j)} x_{t_2^{(i)}}^{(i)}}{c^2}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}} - \frac{t_1^{(i)} - \frac{v^{(i, j)} x_{t_1^{(i)}}^{(i)}}{c^2}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}\Bigg)} \\
\end{align}
$$

$$
\begin{align}
\quad \quad \quad \quad \quad \quad &= \frac{\Bigg(x_{t_2^{(i)}}^{(i)} - v^{(i, j)} t_2^{(i)} - (x_{t_1^{(i)}}^{(i)} - v^{(i, j)} t_1^{(i)})\Bigg)}{\Bigg(t_2^{(i)} - \frac{v^{(i, j)} x_{t_2^{(i)}}^{(i)}}{c^2} - (t_1^{(i)} - \frac{v^{(i, j)} x_{t_1^{(i)}}^{(i)}}{c^2})\Bigg)} \\
&= \frac{\Delta x_{t^{(i)}}^{(i)} - v^{(i, j)} \Delta t^{(i)}}{\Delta t^{(i)} - \frac{v^{(i, j)} \Delta x_{t^{(i)}}^{(i)}}{c^2}} \\
&= \frac{(\frac{1}{\Delta t^{(i)}})(\Delta x_{t^{(i)}}^{(i)} - v^{(i, j)} \Delta t^{(i)})}{(\frac{1}{\Delta t^{(i)}})(\Delta t^{(i)} - \frac{v^{(i, j)} \Delta x_{t^{(i)}}^{(i)}}{c^2})} \\
&= \frac{\frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}} - v^{(i, j)}}{1 - \frac{v^{(i, j)}}{c^2} \frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}}} \\
\end{align}
$$

---

**Aside:**

This is the "average-velocity"-addition formula. Converting this into partial derivatives isn't as easy as taking the limit to an infinitesimal delta, because that infinitesimal delta might not be the same value (or even infinitesimal) when translated across reference frames.

However, if $x_{0}^{(i)} = 0$, then the two infinitesimalities might be substitutable even under translation since both terms infinitesimally approach $0$ as the infinitesimality approaches $0$. Can't this spatial translation always be considered without loss of generality since velocities are invariant to collinearly moving reference frames?

$$
\begin{align}
\frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}} &= \lim\limits_{h \to 0} \frac{x_{t^{(j)} + h}^{(j)} - x_{t^{(j)}}^{(j)}}{h}\\
&= \lim\limits_{h \to 0} \frac{\Bigg(\frac{x_{\hat{t}}^{(i)} - v^{(i, j)} \hat{t}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}} - \frac{x_{t^{(i)}}^{(i)} - v^{(i, j)} t^{(i)}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}\Bigg)}{\frac{h - \frac{v^{(i,j)} x_{h}^{(i)}}{c^2}}{\sqrt{1 - \frac{{v^{(i,j)}}^2}{c^2}}}} \\
&= \lim\limits_{h \to 0} \frac{x_{\hat{t}}^{(i)} - v^{(i, j)} \hat{t} - (x_{t^{(i)}}^{(i)} - v^{(i, j)} t^{(i)})}{h - \frac{v^{(i,j)} x_{h}^{(i)}}{c^2}} \\
\ldots
\end{align}
$$

where $\hat{t} = \mathcal{T}(x_{t^{(j)} + h}^{(j)}, t^{(j)} + h, v^{(i,j)})$.

---

**Resume:**

Picking $t_2^{(j)}, t_1^{(j)}$ in a small enough range that the velocity in that range can be said to be "uniform" or constant, we have the following equivalence relationship:

$\frac{\Delta x_{t^{(j)}}^{(j)}}{\Delta t^{(j)}} = \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}}$

due to the fact that a constant-velocity is always equal to its average-velocity.

Then, we have:

$\frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}} = \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}$,

since a constant-velocity from one inertial reference frame is always a constant-velocity in another inertial reference frame.

Thus:

$$
\begin{align}
\frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}} &= \frac{\Delta x_{t^{(j)}}^{(j)}}{\Delta t^{(j)}} \\
&= \frac{x_{t_2^{(j)}}^{(j)} - x_{t_1^{(j)}}^{(j)}}{t_2^{(j)} - t_1^{(j)}}\\
&= \frac{\frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}} - v^{(i, j)}}{1 - \frac{v^{(i, j)}}{c^2} \frac{\Delta x_{t^{(i)}}^{(i)}}{\Delta t^{(i)}}} \\
&= \frac{\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} - v^{(i, j)}}{1 - \frac{v^{(i, j)}}{c^2} \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}}}. \\
\end{align}
$$

If there exists no small enough range of $t_2^{(j)}, t_1^{(j)}$ such that the velocity in that range can be said to be "uniform" or constant, then I don't know how to get this into partial derivative form.

If there exists a planck time unit however, then this can always hold since such a small enough range always exists, e.g. the time traversed one planck length.


