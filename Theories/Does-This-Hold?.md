The "orbit" / "shell" / "energy-level" of an electron in an atom corresponds proportionally (or rather monotonically, positively increasing) with the radius of the electron's orbit away from the nucleus of the atom. Let's write that as

$$
\begin{align}
n \propto r, \quad\quad \text{(Relationship 1)}
\end{align}
$$

where $n \in \mathbb{N}$ is the energy-level, $r$ is the radius, and $\propto$ represents monotonic proportionality (monotonic meaning not necessarily linear, can be a curved monotonic proportionality, e.g. exponential, or can be linear).

According to de Broglie,

$$p = \frac{h}{\lambda}.$$

Then:

$$\lambda = \frac{h}{p} = \frac{h}{mv},$$

since the momentum of fermions moving at non-relativistic speeds, such as electrons in atoms (which travel at less than $1$% the speed of light, according to Bohr), is $p$ $=$ $mv$, where $m$ is the mass and $v$ is the tangential velocity.

This gives us:

$$
\begin{align}
v = \frac{h}{m\lambda}. \quad\quad \text{(First de Broglie velocity equation)}
\end{align}
$$

de Broglie also says:

$$2\pi r = \hat{n}\lambda,$$

that is, requiring the wavelength to fit into the circumference of each energy-level $\hat{n} \in \mathbb{N}$ times.

Standardly, the energy-level is assumed to be the same as the wavelength-count integer ($n$ $=$ $\hat{n}$ is standardly assumed). Sometimes $n = 2\hat{n}$ is standardly assumed. However, when it comes to monotonic proportionality and the atomic radius proportions considered in this proof, there is no loss in generality choosing either, so let the assumed standard be $n = \hat{n}$.

We thus standardly have:

$$2\pi r = n\lambda.$$

Rewriting this equation for $\lambda$ and plugging it into the "First de Broglie velocity equation," you get:

$$v = \frac{hn}{m2\pi r}. \quad\quad \text{(Second de Broglie velocity equation)}$$

So now we have the following relationship:

$$
\begin{align}
v \propto \frac{n}{r}. \quad\quad \text{(Relationship 2)}
\end{align}
$$

Finally, according to Coulomb, the centripetal force of the orbit of the electron around the nucleus ($F_c$ $=$ $ma_c$, where $a_c$ is the centripetal acceleration) is:

$$
\begin{align}
ma_c = \frac{Kq_1q_2}{r^2}, \quad\quad \text{(Coulomb's law)}
\end{align}
$$

where $q_1, q_2$ are the charges of the electron and nucleus respectively, and $K$ is Coulomb's constant. 

Meanwhile, the centripetal acceleration of a circular orbit of tangential velocity $v$ and radius $r$ [is](https://www.britannica.com/science/centripetal-acceleration): 

$$a_c = \frac{v^2}{r}.$$

Plugging this into Coulomb's law, we get:

$$m\frac{v^2}{r} = \frac{Kq_1q_2}{r^2},$$

which gives us (by rearrangement):

$$\rightarrow v = \sqrt{\frac{Kq_1q_2}{mr}}$$

and subsequently a new relationship:

$$
\begin{align}
v \propto \frac{1}{r}. \quad\quad \text{(Relationship 3)}
\end{align}
$$

So we now have three necessary relationships, if all standard assumptions hold:

$$
\begin{align}
n &\propto r \\
v &\propto \frac{n}{r} \\
v &\propto \frac{1}{r}
\end{align}
$$

So $v$ has to decrease when $r$ increases, and $v$ has to increase when $\frac{n}{r}$ increases. In other words, velocity decreases with radius, and only *increases* with respect to the quotient of energy-level and radius. Meanwhile, energy-level increases with radius.

Since $n$ increments by integer values and $r$ is constrained by the size of an atom (in meters), $r$ has to increase much slower than $n$ since $n$ increases by 1 per energy-level and $r$ increases at much smaller fractions of 1 (in meters) per energy-level. (Call this "the reality of the radial size of an atom").

Is there a contradiction here?

When $r$ increases, $v$ must decrease (Relationship 3). Then $\frac{n}{r}$ decreases (Relationship 2). But Relationship 1 requires that $n$ increase when $r$ increases. So $\frac{n}{r}$ must be able to decrease even when $n$ and $r$ increase. How is that possible? Only if $n$ can increase slower than $r$.

Then $r$ can increase faster than $n$, which contradicts "the reality of the radial size of an atom."

That means something about the standard assumptions must be wrong. $\square$
