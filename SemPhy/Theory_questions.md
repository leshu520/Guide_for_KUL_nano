1. Explain why we can reduce the bandstructure of a crystalline solid to the first Brillouin zone.

**Bloch’s Theorem and Periodicity**: Bloch’s theorem states that the wavefunctions in a periodic potential, such as that of a crystalline solid, can be expressed as a plane wave modulated by a periodic function: $\psi_{\mathbf{k}}(\mathbf{r}) = e^{i\mathbf{k} \cdot \mathbf{r}} u_{\mathbf{k}}(\mathbf{r}) $ where $u_{\mathbf{k}}(\mathbf{r})$  has the periodicity of the lattice, and  $\mathbf{k}$  is the wavevector. 

**Bloch waves property**: Bloch waves with wavevectors outside the first Brillouin zone can be equivalently described by wavevectors within the first zone due to the equation that adding a reciprocal vector $G$ at the wavefunction is the same as adding it in the $E(k)$ which is $E(k+\bar G)$ corresponding to $\mu_{k+\bar G}$ in SC equation. Also, with the inversion symmetry, the left and right side of the dispersion relation is exact symmetry. 

**Reduced BZ**: Thus, for a wavevector  $\mathbf{k}$  outside the first zone, there exists a reciprocal lattice vector  $\mathbf{G}$  such that  $\mathbf{k} - \mathbf{G} $ takes the same behaviour but falls inside the first zone. This is due to the property that adding a reciprocal lattice vector to a wavevector does not change the physical properties of the wave since it corresponds to a phase shift of $2\pi$ and replicas. 

**Why first BZ?**: The perodicity is engaged with the lattice ions so WS cells. And from the section of X-ray reflection, we concludes that the reciprocal lattice vector  $\mathbf{G} $ associated with the reflection plane determines the change in the wave vector:  $\mathbf{k} \to \mathbf{k} + \mathbf{G} $. And the first BZ is determined by the first bragg plane surrounded. 

(The figure of G with parabolic $E(k)$)

2. Explain how the effective mass theory can be used to describe the motion of electrons as semi-classical particles. 

The effective mass theory simplify the characterisation of the electron at the CB by adapting the effective mass on the electron. With that, the effective mass theory is more able to describe the motion of the electron. 

For the derivation of the motion of electrons, if we apply the wavepacket function $F(x,t)$ on it to describe the localized electron behaviour with the peak at the minima which is $c_k$ and this is sharply around the $k_0$. And the wavepacket equation could be adapt into the wavefunction that is same as the effect mass theory by assuming the external potential variation is much bigger than the variation of the electron and the electron variation is bigger than the lattice constant. The uncertainty of $k$ will be restricted into the 1st BZ. 

These derivation seperate the influence from the external potential voltage and make the dynamic movement of the electron under the framework of classical physic theory. The wavepacket moving speed could considered as $v_g$ and it is able to construct the equation $P_C = m^*v_g$ for the momentum as long as the dispersion relation is still parabolic. For the external potential force $F_{ext}$, we can even use the electrical field and magnetic field to describe. 

3. Explain how the effective mass approximation is obtained. Why you can limit yourself to the 1 dimensional case (I guess it's the CB example). Why is it useful?

The starting point is from the Taylor expansion of $E(k)$ and with the 2nd component, then for the any $k$ point on the CB. Then we can conduct the equation from free electron $E(k)={\mathscr{h}^2k^2}/{2m^*}$ with designated mass $m^*$ for different $k$ points. If put the formula in two direction $i$ and $j$ the equation becomes 

$$ E(\mathbf{k}) \approx E(\mathbf{k}_0) + \frac{1}{2} \sum{i,j} \frac{\partial^2 E}{\partial k_i \partial k_j} \Bigg|_{\mathbf{k}=\mathbf{k}_0} (k_i - k_{0i})(k_j - k_{0j})$$ 

with the defination of $m^*$

 $$\left(\frac{1}{m^*}\right)_{ij} = \frac{1}{\hbar^2} \frac{\partial^2 E}{\partial k_i \partial k_j} $$

After the diagonalization at the $\Gamma$- point of the CB, we can find that $m^* = m^*_x = m^*_y=m^*_z$ that means the 3-dimension is exactly same as the 1 dimension. Reducing the complexity to one dimension simplifies the mathematical expressions and focuses on the core physical insights without the clutter of higher-dimensional vector calculus. n cases of isotropic materials or along specific crystallographic directions, this tensor simplifies to a scalar, making the physics more accessible. 

4. How is semi-classical dynamics related with Bloch electrons? What approximations are made?

Almost the same as 2. 

approximation: only 1 band. only $k$ value near band extrema. 

5. Explain 6 equivalent energy band minima in silicon, also write the energy dispersion relation in these minima. 

Silicon is a indirect semiconductor, the maximal point for VB is no longer $\Gamma$ , it is $X$ -point. Each direction $k_y$, $k_x$ and $k_z$ has two minimal on the axis. After the diagonalization, the effect mass has two values, one mass on the main direction are $m_l^*$ and the rest directions which are $m_t^*$ , that gives ellipsoidal surface. 

(with the figure)
