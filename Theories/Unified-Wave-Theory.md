# A Unified Wave Theory of Light and General Relativity

$`K \in \mathbb{Z}`$. 

$`N, M, L, n, m \in \mathbb{N}`$. 

$`\sigma, f \in \mathbb{R}`$. 

$`\gamma_1, \gamma_2 \in [0, 1]`$.

$`t \in \mathbb{N}`$.

$`i \in 1, 2, ..., N`$.

$`j \in 1, 2, ..., M`$.

$`k \in 1,2, ..., L`$.

$`\mathrm{h_x}^{(0,0,i,j)}, \mathrm{h_v}^{(0,0,i,j)} \in \mathbb{R}^3`$ and $`\mathrm{h_\varphi}^{(0,0,i,j)} \in [0, 2\pi)`$.

$`\mathrm{p}^{(K, t, i)} \sim \mathbf{P}(\mathcal{W}^{(K, t, i)})`$.

$`\mathcal{W}^{(K, t, i)} = \langle h^{(K, t, i, j')} \bigm| \forall j' \in 1,2,..., M \rangle`$.

$`\mathrm{h}^{(K, t, i, j)} = \mathcal{S}_j^{(K, t, i)}`$.

$`\mathcal{S}^{(K, t, i)} = \langle b \sim \mathbf{P}(\mathcal{G}^{(K, t, i)}) \bigm| |\mathcal{S}^{(K,t,i)}| = M \rangle`$.

$`\mathcal{G}^{(K, t, i)} = \langle \hat{\mathrm{h}}^{(K,t,i,j',k')} \bigm| \forall j' \in 1, 2, ..., M, \forall k' \in 1,2, ..., L \rangle`$.

$`D(\mathrm{p}, \mathrm{h}, K, t, i, j) = \sum\limits_{q \in \mathrm{p_i}^{(K, t, i)}} \mathrm{p_\omega}^{(K,t,q)}(\mathrm{h_x}^{(K,t,i,j)})`$.

$`\mathrm{p_\omega}^{(K,t,q)}(\cdot)`$ depends on $`\mathrm{p_x}`$ (inverse square laws and momentum, e.g., [the wavelets described here](https://github.com/animal-tree/Writing-stuff-2/blob/main/Theories/Bendy-Ball.md)).

$`\mathrm{\hat{h}_a}^{(K,t,i,j,k)} = -\frac{\partial D(\mathrm{p}, \mathrm{h}, K, t, i, j)}{\partial\mathrm{h_x}^{(K,t,i,j)}}`$.

Note: these are element-wise vector operations.

$`\mathrm{\hat{h}_\hat{v}}^{(K, t, i, j, k)} = \mathrm{h_v}^{(K, t-1, i, j)} + \mathrm{\hat{h}_a}^{(K, t-1,i,j,k)}`$.

$`\mathrm{\hat{h}_\mu}^{(K,t,i,j,k)} = \frac{\mathrm{\hat{h}_\hat{v}}}{\lVert \mathrm{\hat{h}_\hat{v}}^{(K,t,i,j,k)} \rVert}`$.

$`\mathrm{\hat{h}_d}^{(K,t,i,j,k)} \sim \mathcal{N}(\mathrm{\hat{h}_\mu}^{(K,t,i,j,k)}, \sigma)`$.

$`\mathrm{\hat{h}_K}^{(K,t,i,j,k)} = K, \mathrm{\hat{h}_t}^{(K,t,i,j,k)} = t, \mathrm{\hat{h}_i}^{(K,t,i,j,k)} = i`$.

$`\mathrm{\hat{h}_v}^{(K,t,i,j,k)} = \frac{\mathrm{\hat{h}_d}^{(K, t, i, j, k)} \lVert \mathrm{\hat{h}_\hat{v}}^{(K,t,i,j,k)} \rVert}{\lVert \mathrm{\hat{h}_d}^{(K,t,i,j,k)} \rVert}`$.

$`\mathrm{\hat{h}_\varphi}^{(K,t,i,j,k)} = \sin(ft)`$.

$`\mathrm{\hat{h}_x}^{(K,t,i,j,k)} = \mathrm{\hat{h}_x}^{(K,t-1,i,j,k)} + \mathrm{\hat{h}_v}^{(K,t,i,j,k)}`$.

$`\mathrm{\hat{h}}_{\mathrm{p}^{(t)}}^{(K,t,i,j,k)} = \mathcal{N}(\mathrm{\hat{h}_d}^{(K,t,i,j,k)} \bigm| \mathrm{\hat{h}_\mu}^{(K,t,i,j,k)}, \sigma)\mathcal{B}(\mathrm{\hat{h}}^{(K,t,i,j,k)} \bigm| \mathcal{G}^{(K, t, i)})`$.

$`\mathcal{B}(b \in H \bigm| H) = \frac{m^{(b_\mathrm{K}, b_\mathrm{t}, b_\mathrm{x})}}{\sum\limits_{g \in H} m^{(g_\mathrm{K}, g_\mathrm{t}, g_\mathrm{x})}}`$.

$`m^{(K,t,x)} = \lVert \sum\limits_{i,j,k} \sum\limits_{T=0}^n \gamma_1^T s(x, \mathrm{\hat{h}}^{(K,t - T,i,j,k)}) \rVert`$ sums over vectors in $`[-1, 1]^2`$, then norms.

$`s(x,b) = \mathrm{ReLU}(-f \lVert x - b_\mathrm{x} \rVert + 1) \langle \cos^{-1}(b_\varphi), \sin^{-1}(b_\varphi) \rangle`$ multiplies a scalar by a vector in $`[-1, 1]^2`$.

$`\mathrm{\hat{h}_x}^{(K,t,i,j,k)} = \mathrm{\hat{h}_x}^{(K,t-1,i,j,k)} + \mathrm{\hat{h}_v}^{(K,t,i,j,k)}`$.

$`\mathbf{P}(b \in H \bigm| H) = \frac{\sum\limits_{T=0}^{m} \gamma_2^T b_{\mathbb{p}^{(b_\mathrm{t} - T)}}}{\sum\limits_{g \in H} \sum\limits_{T=0}^{m} \gamma_2^T g_{\mathbb{p}^{(b_\mathrm{t} - T)}}}`$.


