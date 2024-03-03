> Huge disclaimer: this is in part humor, with a philosophical point about deduction and the "knowability" of any cosmogenesis theory.

# Archetypal Madness

I am Chenliang, Sam's advisor. He writes this with telepathic interference from Josh, Sam's friend. Together, and this is Sam speaking, we shall derive the universe. Not derivatively of course. That would require ample physical sciences background. But sufficiently well-reasonedly, with made-up words here and there. Let's begin with a less exhausting setup. "I observe." It is true, therefore it is. At any rate, fading into sleep-deprivative exhaustion as I may be, I am reluctant to say this won't work. Largely because of the intensive time and money — "minimum wage" Josh chimes in — investment that has gone into this project. Well, so be it. The whole of the universe, in one shebang. It starts with time. But time exists as a physical construct not a mathematically deduced one. So let us find an incredibly stupid place to hide it. In equivalence.

Alright. Given $A = B$, we know $A \rightarrow B$ and $B \rightarrow A$. We don't know *when* $A \rightarrow B$. Is it in $1$ deductive step $A \rightarrow_1 B$? Is it in $n$ deductive steps $A \rightarrow_n B$. From this, we get a cheap hacky way to derive something out of literally nothing.

Let us start with nothing $\emptyset$.

Don't regard it as the empty set. Don't regard it at all.

$\emptyset_0 = \emptyset_1 = \cdots$

are all nothing, with just subscripts added.

There we now have causality, constrained only to a cyclical loop between every nothing and every other nothing. e.g.

$\emptyset_0 \rightarrow \emptyset_1 \rightarrow \cdots$

$\emptyset_0 \leftarrow \emptyset_1 \leftarrow \cdots$

These nodes can connect in any number of ways and create a multi-branched graph. The ambiguities are not necessary. Let us define one such branch/construct that we can say is "Turing equivalent" and be done with it.

Cosmogenesis:

A "grammar" — or word (if we want to make Biblical allusions/puns) — that is Turing equivalent, from nothing.

Go:

How about a tape of $\emptyset_{0,i}$ and $\emptyset_{1,i}$ (zeros and ones, or yins and yangs if you want), where $i$ lets us hackily denote the position on the tape, with implications from each non-sensical bit at deductive step $n$ to each non-sensical bit at deductive step $n + 1$.

The "halt" can be cosmo-genocide, which we are not interested in solving. $\square$

# Math

Okay, we've gotten a construct for time and an unhalting Turing machine that presumably eventually (or somehow) cycles back to its origin starting state. We got this from hacking the definition of equivalence. We will take a step back now and derive it a little more formally. It is stupid, but perhaps there's nothing stopping us from doing this re-defining and obtaining a deductive logic from which cosmogenesis could theoretically make sense, noting: the Big Bang Theory is not a cosmogenesis theory but chronicles the early moments and evolution of the observable beginning of the universe. An un-mythological cosmogenesis theory has, perhaps, yet to be proposed in the scope of deduction. Myths, such as my favorite being Tolkien's cosmogenesis allegory (yes it is an allegory) of the universe arising from a musical theme, do exist.

Assuming nothing but math, I'll derive "something from nothing".

## Deduction

> This is a succinct definition of deduction. It's consistent with historical uses, and permits the derivation of arbitrary representation from nothing without additional axiom.

### Proofs

**Definition 1.** Axiom.

$($ Axiom  $A ) \coloneqq (\exists A)$.

**Definition 2.** Definition.

$($ Definition $A \coloneqq B) \coloneqq (\exists (A \coloneqq B))$. 

**Definition 3.** Equivalence.

$($ Equivalence $A = B) \coloneqq (A \rightarrow_n B, B \rightarrow_m A, n, m \in \mathbb{N})$, where $n, m$ are deductive steps, meaning $n-1, m-1$ statements must be deduced between $A$ and $B$ and $B$ and $A$ respectively. 

Instantaneous equivalence $(A \coloneqq B) \coloneqq (A \rightarrow_1 B, B \rightarrow_1 A)$.

For example, $(A \rightarrow_2 C) \coloneqq (A \rightarrow_1 B \rightarrow_1 C)$ for some mandatory intermediary $B$.

**Definition 4.** Implication.

$($ Implication $A \rightarrow_1 B) \coloneqq (\exists A \rightarrow_1 \exists B)$.

**Definition 5.** Proof.

$($ Deduction/theorem/proof $A \rightarrow B) \coloneqq (A \rightarrow_n B) \coloneqq (\exists A \rightarrow_n \exists B)$ for some $n \in \mathbb{N}$.

### Existence and Cause

**Definition 6.** Hypotheticals.

$($ Sets of anything defined... $(A, B, ...))$ $\coloneqq ((A, B, ...))$

denoted by parentheticals. 

$A$ is a single hypothetical.

**Definition 7.** Sets of existence.

$(\langle X_1, X_2, ... \rangle) \coloneqq (\exists X_1, X_2, ...)$

hypotheticals whose elements exist.

**Axiom 1.** Existence exists. $\langle X_1, X_2, ... \rangle \coloneqq \langle\langle X_1, X_2, ... \rangle\rangle$.

**Axiom 2.** Cause exists. $\exists \rightarrow$.

## Nothing and The Universe

**Definition 8.** Nothing.

The empty existence set $\emptyset \coloneqq \langle \rangle$.

**Definition 9.** Nothing equivalents.

$\emptyset_K = \emptyset, \text{ } \forall K \subseteq \mathbb{N}$.

**Definition 10.** The universe.

$\Omega^{(0)} \coloneqq \emptyset$.

$\Omega^{(n)} \coloneqq (( \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K ), \rightarrow_n),$ $\forall n \in \mathbb{N}$.

$\Omega \coloneqq (\Omega^{(0)}, \Omega^{(1)}, ...)$.

In other words, defined as: some sequence of numerically representable deductions from the initial nothing.

> &#9432; See [here](https://github.com/slerman12/Detective-Sam/blob/main/Philosophy/Consciousness.md) for an *ad absurdum* argument why representation and matter can't be the same thing (nor representation and consciousness). 

## Something From Nothing

**Theorem 1.** Nothing exists. $\exists \emptyset$.

**Proof.**

$(()) \rightarrow (\langle\rangle)$. (Definition 7)

$(\langle\rangle)  \rightarrow (\langle\langle\rangle\rangle)$. (Axiom 1)

$(\langle\langle\rangle\rangle)  \rightarrow (\exists \langle\rangle)$. (Definition 7)

$((\emptyset \coloneqq \langle \rangle), (\exists \langle\rangle)) \rightarrow (\exists \emptyset)$. (Definition 8) $\square$

**Theorem 2.** All nothings exist. $\exists \emptyset_K \vert K \subseteq \mathbb{N}$.

**Proof.**

$((\exists \emptyset), (\emptyset = \emptyset_K \forall K \subseteq \mathbb{N})) \rightarrow (\exists \emptyset_K \vert K \subseteq \mathbb{N})$. (Theorem 1, Definition 9) $\square$

**Theorem 3.** The universe exists. $\exists \Omega$.

**Proof.**

$((\exists \emptyset), (\Omega^{(0)} \coloneqq \emptyset)) \rightarrow (\exists \Omega^{(0)})$. (Theorem 1, Definition 10)

$((\exists \emptyset_K \vert K \subseteq \mathbb{N}), (\exists \rightarrow_n)) \rightarrow \langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle$. (Theorem 2, Axiom 2, Definition 5, Axiom 1)

$\langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle \rightarrow (\exists \Omega^{(n)})$. (Definition 10)

$((\exists \Omega^{(0)}), (\exists \Omega^{(n)})) \rightarrow (\Omega^{(0)}, \Omega^{(1)}, ...) \rightarrow (\exists \Omega)$. (Definition 10) $\square$

**Theorem 4.** The universe $\Omega$ is at least a non-halting Turing machine. 

**Proof.**

Construct a tape of binary zeroes and ones $\emptyset_{0,i, t}, \emptyset_{1,i, t}$ where $i$ denotes the position on the tape and $t$ denotes the time point.

$\emptyset \rightarrow_1 \emptyset_{\tau,i,0} \forall i \in \mathbb{N}, \tau \in (0, 1)$.

This is the initial state, defined by $\tau$.

At each time step modify one bit:

$\emptyset_{\tau,i,t} \rightarrow_1 \emptyset_{-\tau + 1,i,t+1}$

or "stay":

$\emptyset_{\tau,j,t} \rightarrow_1 \emptyset_{\tau,j,t+1}$.

Now, complete the equivalence cycle required by Theorem 2 and Definitions 3 and 9 by the following limit:

$\lim_{n\rightarrow\infty} \emptyset_{\tau,i,n} \rightarrow_1 \emptyset$. 

The infinitum allows us to leave the potential cyclicality of the universe a mystery. $\square$

**Theorem 5.** A universe capable of simulating a Turing machine (sans halting) can arise from nothing, assuming just the properties of deduction: existence of existence and cause, defining nothing as the empty set of existence.

**Proof.**

By Theorem 4. $\square$

---

We thus obtain a strongly connected directed graph (potentially expanding in real-time) with nodes and edges that may be defined as non-deterministic and/or non-stationary, whose grammatical "word" is chosen by the un-specified deducer.

> I've derived the representable universe without making any assumptions (except deduction itself), and therefore either this derivation is true, and we have just uncovered cosmogenesis, or representation and deduction cannot be all there is fundamentally in nature and the physical universe. For home-hitting's sake, here's a Q.E.D. symbol: $\square$.

# Afterward

Hypothetically, how far can we get without axioms?

Well, a hidden axiom contained in the definition of definition is the existence of all definitions. Any definition, given any pair of hypotheticals $A, B$, $A \coloneqq B$ "exists" (is true).

From that we can derive a variable $\emptyset = (A \coloneqq B)$, and its definition equivalents:

$\emptyset = \emptyset_K \vert K \subseteq \mathbb{N}$.

So this together with Axiom 2 suffices to obtain $\Omega$. Then we can ask "what is definition?" Perhaps there is a set of all possible definitions. Each equivalent can be regarded as a unique number on the natural number scale $\mathbb{N}$ and each non-equivalent given its own dimension of equivalents $\mathbb{N}^\mathbb{N}$. We thus obtain the natural numbers and vector spaces. The way they relate to each other is by implication with respect to each dimension: some order, for example:

$1 \rightarrow_1 2 \rightarrow_1 3 \rightarrow_1 \cdots$

with some connecting universal node $0 \coloneqq i \forall i \in \mathbb{N}$ to complete the strongly connected directed graph.

Instead, we could discard causality and Axiom 2.

Instead, let's define existence as a recursive function. Its input is any definition, chosen by a deducer, and its output is the existence of that definition paired with a recursion to a new application of itself to a new definition.

$\exists(\emptyset_i) = (\exists\emptyset_i, \exists(\emptyset_j))$,

Thus creating a limited set of definitions at each recursive step $n$, not easily denoted in the expressivity of recursive functional form. We can denote that $n\text{th}$ recursive step set of existence, and perhaps each source and sink to each existence, as $\Omega^{(n)}$ PERHAPS allowing us to derive a universe from nothing but definition and the axiom that this existence function, as described, exists.

Perhaps, further in consideration, Axiom 1 can "create" Axiom 2 and Axiom 2 can "create" Axiom 1, each depending only on the definition of definition, axiomatically assumed without axiom I guess.

As a matter of point, for a recursive function to be defined and it exist, it must be actively recursing.

Piecing these together, we could probably derive a non-axiomatic universe, but I want to move on to the question of what the deducer is, that is, why THE laws of physics instead of some other laws of physics?

---

Note: no matter what, as long as there is a definition or an axiom, there is *something* and so what we are actually deriving from is not *nothing* but a primordial something, and it can be defined to be something else e.g. a recursive self-duplicating observer function that encapsulates both definition and cause, e.g. $\mathrm{I}(x) = (\exists x, \mathrm{I}(\max\limits_{y\subseteq \Omega} Q(\Omega)))^\text{ \color{blue}[1.]}$, with a qualia to justify the development of that something into something specific. 

$\text{\color{blue}[1.]:}$ Just spitballing at this time.

## Alternative Set of Definitions of Math and Philosophy

**Physics:**

$\mathbf{P}((y, h^{(n)}) \sim \mathrm{R}^n(x, h^{(0)}) \vert y)$

where $\mathrm{R}$ is a recursive dynamics model and a random variable, $h$ is the hidden state (the non-observable universe) at any time point up to some conceivable horizon (in order to make $\mathrm{R}$ defined), composed $n$ times. $y$ is the observable universe.

**Causal reasoning:**

$\mathbf{P}((y, h^{(n)}) \sim \mathrm{R}^n(x, h^{(0)}) \vert y, \mathrm{R})$

$x$ is the cause, $y$ is the effect, under some dynamics system $\mathrm{R}$.

**Axiomatic math:**

$\mathbf{P}((y, h^{(n)}) \sim \mathrm{R}^n(x, h^{(0)}) \vert h^{(n)}, n \in \mathcal{N}, \mathrm{R}, x, h^{(0)})$

where $\mathrm{R}$ is the rules of math. $y$ is a theorem or theorem set, $x$ is an axiom or axiom set. $\mathrm{R}$ is Turing-complete due its rewritable memory state $h$. Ordinarily, $\mathrm{R}$'s rules are deterministic, a side effect being that the probability of a theorem $y$ is also deterministic, $1$ or $0$. 

Non-deterministic math, e.g. an "Occam's razor" "theorem", we will refer to as epistemological math, rooted in belief.

**Belief:**

$\mathbf{P}(B \vert E) = \frac{\mathbf{P}(E \vert B)\mathbf{P}(B)}{\mathbf{P}(E)}$

Physics, causality, and math have utility and correlative predictiveness to our memories and senses, but beyond observing what's in front of us, these established beliefs are symbolic references within the brain, and the referents are memories, observations, and beliefs. As René Descartes derived with "*cogito, ergo sum*": "I doubt, therefore I am," we can further deduce inwardly. If I may: 

"I observe, therefore I am observing, therefore I am. 

I observe many referents to my observation, including memories, feelings, and viscera. There's also belief. I believe X, Y, Z. I justify X, Y, Z by reasons, another element of belief, X', Y', Z'."

Each step is deeper into the psyche.

Physics, causality, and math are beliefs. 

Philosophy includes these meta-beliefs as well as others.

Perhaps, philosophically speaking, philosophy is the random variable set encompassing all random variables:

**Philosophy:**

$\langle B \vert (B \in \Omega) \sim \mathbf{P}(B \in \Omega) \rangle$,

though to define it as such would contradict that definition since a random variable set encompassing all random variables would have to be contained within itself, making the definition self-referentially undefined. This would be analogous to defining a word in a dictionary by some other words plus itself. Perhaps contextually useful to make some inferences about its meaning based on the other words but ultimately meaningless since any reference to itself within the definition would point back to a non-converging turtles-all-the-way-down recursion of itself (though not technically prohibited, especially since all definitions must eventually become circular, given that each definition in a finite dictionary needs its references defined). Furthermore, something about Gödel's incompleteness theorem, and the infinite meta-mathematics needed to make any formal system complete.

Random variables may be also expressed as random variables relating other random variables, such as $\mathbf{P}(x > y)$.

For the sake of deduction to derive axioms to theorems, they may also define implications:

**Theorem-derivation steps:**

$\mathbf{P}(x > z \vert x > y, y > z) = 1$

Transitivity of the greater-than inequality for example, using conditionals to specify the valid axioms or theorems $(x > y, y > z)$ that would imply the prior $x > z$.

They may even be cross-referential:

$\mathbf{P}(w > z \vert w > x, \mathbf{P}(x > z \vert x > y, y > z) = 1) = 1$,

Treating each other as random variables.

Could such an ontology form the basis of a data structure to represent $R, h^{(0)}$ in axiomatic math? Using deterministic conditionals with probabilities $1$ as proof steps and a defined set of initial conditionals and beliefs (random variables), it seems so.

Furthermore, it can generalize to a new type of math where proof steps can be epistemological, non-deterministic beliefs applied to other beliefs to quantify a looser proof. This is standardly done in physical sciences with the use of p-values, and I draw a formal unambiguous connection between that to AI and reasoning generally, keeping these notations and formalities that tie together the larger sciences.
