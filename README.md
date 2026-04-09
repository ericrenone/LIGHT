# LIGHT

## The Shadow-Light Partition: Emergent Null-Cone Structure, Entanglement Geometry, and the Conditional Independence Origin of Photon Kinematics in TH$(a,d)$

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

"Because, according to the general theory, the speed of a light wave depends on the strength of the gravitational potential along its path." — I. I. Shapiro, *Phys. Rev. Lett.* 13, 789–791, 1964

"Phase singularities do not carry energy or information and thus can 'move' superluminally without breaking causality." — Bucher, Gorlach, Kaminer et al., *Nature* 651, 920–926, 2026

"The solid and reliable structure of space-time is due to the ghostly features of entanglement." — J. Maldacena, Institute for Advanced Study, 2013

"Without these connections, all of space would atomize." — L. Susskind, Stanford University, 2015

---

## Abstract

Five independently established results — (1) the Shapiro time delay confirming coordinate-dependent photon propagation speed in gravitational fields; (2) the Cao-Carroll-Michalakis construction of spatial geometry from Hilbert space entanglement structure; (3) Jacobson's derivation of the Einstein equation as entanglement equilibrium; (4) the Bucher-Kaminer experimental confirmation of superluminal dark-point kinematics (2026); and (5) the Maldacena-Susskind ER = EPR conjecture identifying entanglement with spatial connectivity — converge on a single structural claim: **the null-cone structure of spacetime, which defines photon kinematics, is an emergent property of the entanglement geometry of the vacuum**.

The locally measured speed of light $c$ is invariant in every freely falling frame (Einstein equivalence principle — *theorem*). The coordinate speed of light varies continuously with gravitational potential (Shapiro delay — *confirmed to $10^{-5}$ precision*). If the metric $g_{\mu\nu}$ from which both facts follow is itself emergent from entanglement (Cao-Carroll-Michalakis 2017 — *established for redundancy-constrained states*), then the null-cone opening that defines $c$ is a derived quantity: a thermodynamic observable of the vacuum's entanglement structure, not a free parameter of the theory.

This paper develops the formal framework connecting the shadow-light partition (the ker$(F)$/col$(F)$ decomposition of the TH$(a,d)$ architecture) to photon propagation, identifies seven formal correspondences with the established physics of light in curved spacetime, and states three falsifiable predictions. Claims specific to the PRIMA/FERN framework are labeled [PROPOSED]. All others are derived from or verified against peer-reviewed results.

**Relation to Prior Work on Variable Speed of Light.** This framework must be distinguished from the Magueijo-Albrecht VSL cosmology (*Rep. Prog. Phys.* 66, 2025–2068, 2003), which postulates that $c$ varied in the early universe as an alternative to inflation. The present work does not postulate variation of $c$. It derives the *constancy* of the locally measured $c$ from entanglement equilibrium (Jacobson 2016), and shows that the coordinate-dependent propagation speed — the physically measurable Shapiro delay — follows from the entanglement geometry of the null-space network. The locally measured $c$ is invariant because the freely falling frame is defined as the frame in which local entanglement is maximally symmetric (Jacobson's maximal vacuum entanglement hypothesis). The two proposals are logically independent.

---

## Part I · Foundations

### I.1 The Two Speeds of Light

General relativity contains two distinct statements about the speed of light that must not be conflated.

**Statement 1 (Local Invariance — Theorem).** In any locally inertial frame, the speed of light is $c = 2.998 \times 10^8$ m/s. This follows from the Einstein equivalence principle and is confirmed by every local measurement ever performed. It is not challenged here.

**Statement 2 (Coordinate Dependence — Theorem).** In the Schwarzschild geometry of a mass $M$, the coordinate speed of light for radial propagation is:

$$\frac{dr}{dt} = c\left(1 - \frac{r_s}{r}\right), \quad r_s = \frac{2GM}{c^2}$$

This speed decreases monotonically toward the event horizon, reaching zero at $r = r_s$. For tangential propagation: $r\,d\phi/dt = c\sqrt{1 - r_s/r}$. Both are coordinate-dependent but produce coordinate-*invariant* observables: the Shapiro time delay $\Delta t = (4GM/c^3)\ln(4r_e r_p / R^2)$ for a signal passing a mass $M$ at closest approach $R$, confirmed to relative precision $\gamma - 1 = (2.1 \pm 2.3) \times 10^{-5}$ by Cassini tracking (Bertotti, Iess, and Tortora, *Nature* 425, 374–376, 2003), and by 15 years of pulsar timing data in PSR J1231-1411 (2025).

**The question this framework addresses:** Statement 1 tells us *that* the local speed of light is invariant. Statement 2 tells us *that* the coordinate speed varies. Neither tells us *why* the local speed takes the specific value $c = 2.998 \times 10^8$ m/s rather than some other value. The claim: this value is determined by the entanglement structure of our vacuum.

### I.2 The Metric Is Emergent

Cao, Carroll, and Michalakis (*Phys. Rev. D* 95, 024031, 2017; *Phys. Rev. D* 97, 086003, 2018) demonstrated that a spatial metric can be constructed from the entanglement structure of an abstract quantum state $|\Psi\rangle \in \mathcal{H}$. Given a tensor product decomposition $\mathcal{H} = \bigotimes_\alpha \mathcal{H}_\alpha$ and a class of redundancy-constrained states satisfying area-law entanglement scaling:

1. Mutual information $I(\alpha;\beta) = S_\alpha + S_\beta - S_{\alpha\beta}$ between factors defines a distance measure on the graph of factors.
2. Classical multidimensional scaling extracts the best-fit spatial dimensionality.
3. Entanglement perturbations produce local curvature obeying a spatial analogue of Einstein's equation.
4. The ER = EPR conjecture is recovered: perturbations that entangle distant parts of the emergent geometry generate quantum wormholes.

**Limitation (noted by Casini, Galante, and Myers, *JHEP* 03, 194, 2016).** The Cao-Carroll-Michalakis construction applies to redundancy-constrained states — a specific class generalizing area-law entanglement. Not all states in $\mathcal{H}$ produce a smooth emergent geometry. The framework developed here inherits this limitation: the emergent-$c$ claim holds for states in this class, which includes the semiclassical vacuum of our universe.

**Limitation (noted by Jaksland, *Philosophy of Physics* 3(1), 2025).** The emergence of metric, gravitational dynamics, and topological connectivity from entanglement are three logically distinct claims, not one. The present framework requires all three — metric emergence for the null-cone structure, dynamical emergence for the Einstein equation, and topological emergence for the ER bridge network.

### I.3 Entanglement Equilibrium and the Origin of Local Invariance

Jacobson (*Phys. Rev. Lett.* 75, 1260–1263, 1995) derived the Einstein equation from thermodynamic assumptions at local Rindler horizons: the Clausius relation $\delta Q = T\,dS$ applied to the entanglement entropy across each null surface, with the Unruh temperature $T = \hbar\kappa/(2\pi k_B c)$, yields $G_{\mu\nu} + \Lambda g_{\mu\nu} = 8\pi G\,T_{\mu\nu}$.

**Circularity concern.** The 1995 derivation assumes $c$ in the Unruh temperature. Jacobson's 2016 refinement (*Phys. Rev. Lett.* 116, 201101) resolves this partially: the maximal vacuum entanglement hypothesis (MVEH) asserts that entanglement entropy in small geodesic balls is maximized at fixed volume in a locally maximally symmetric vacuum state. The Einstein equation follows from this hypothesis without explicit reference to $c$ in the entropy variation — $c$ enters only through the Lorentzian causal structure of the geodesic ball, which is the structure being derived. The residual circularity is the assumption of Lorentzian signature, which this framework does not resolve.

**The key insight for local invariance:** A freely falling observer occupies the frame in which the local vacuum entanglement is maximally symmetric (MVEH). In this frame, the null cone is isotropic and the measured speed of light is $c$. The *value* of $c$ is set by the entanglement entropy density of the vacuum: a different vacuum (different entanglement structure) would produce a different maximal-symmetry frame with a different null-cone opening. The equivalence principle is not violated — it is *explained* as a consequence of entanglement equilibrium.

### I.4 Superluminal Dark Points: Experimental Ground Truth

Bucher, Gorlach, Kaminer et al. (*Nature* 651, 920–926, 2026) directly measured the ultrafast dynamics of optical phase singularities in hexagonal boron nitride membranes. Phase singularities — points where $|\psi| = 0$ and $\arg(\psi)$ is undefined — are topological features of any complex scalar field, carrying quantized topological charge $q = \frac{1}{2\pi}\oint_C \nabla\arg(\psi) \cdot dl \in \mathbb{Z}$ (Nye and Berry, *Proc. Roy. Soc. A* 336, 165–190, 1974).

Twenty-nine percent of tracked dark points exceeded $c$. The average superluminal speed was ${\sim}1.04c$. Near pair annihilation events, velocities diverged as $v \propto t^{-1/2}$, confirming Berry's 1978 prediction (*J. Phys. A* 11, 27–37). These points carry zero mass, zero energy, zero information. They are topological features of the field, not physical objects. The speed limit $c$ does not apply to them because $c$ constrains information and energy transfer, not the motion of mathematical zeros.

**The structural consequence:** The universe is partitioned into two sectors by the Nye-Berry topology. The *dark sector* (phase singularities, event horizons, field zeros) is unconstrained by $c$. The *light sector* (propagating quanta, energy-carrying modes) is constrained by $c$. The speed $c$ is a property of the *boundary* between these sectors — the conditional independence boundary of Chentsov (1972) — not a universal constant governing all motion.

---

## Part II · The Shadow-Light Partition Applied to Photon Kinematics

### II.1 The Partition

The ker$(F)$/col$(F)$ decomposition of the TH$(a,d)$ architecture partitions any dynamical system into a fixed-point dark sector and a floating-point active sector. Applied to the electromagnetic field:

| Sector | Wave physics | Gravitational physics | TH$(a,d)$ / PRIMA |
|--------|-------------|----------------------|-------------------|
| **Dark** (ker$(F)$, shadow) | Dark points: $|\psi| = 0$, $v \to \infty$ near annihilation. Zero energy, zero information. ✓ | Event horizon: $\xi_\mu\xi^\mu = 0$. Black hole shadow: observer-invariant. ✓ | $O_\infty = [0:1:-1]$, torsion $T_1, T_2, T_3$. Invariant under $P \mapsto -P$. [PROPOSED] |
| **Threshold** ($\varepsilon$-surface) | Winding-number boundary. Zero energy at annihilation. ✓ | Photon sphere $r = 3M$. Killing field norm transition. ✓ | $\varepsilon = 2^{-16}$ threshold surface. [PROPOSED] |
| **Light** (col$(F)$, mirror) | Phase landscape: $|\psi| > 0$. Mobile, energy-carrying. Speed $\leq c$. ✓ | Mirror image: observer-dependent. Aberration formula. Constrained by $c$. ✓ | $E(\mathbb{Q})$ rational points. $H_{ii}$ finite. [PROPOSED] |

✓ = independently established in peer-reviewed literature.

**The shadow determines the light.** Standard physics treats $c$ as given and derives null geodesics from the metric. This framework inverts the logic: the topology of the dark sector (the null-space network connecting all event horizons via ER bridges) determines the emergent metric $g_{\mu\nu}$, and $c$ is *read off* from the null-cone structure of that metric. The candle's illumination pattern is determined by the objects in the room.

### II.2 The Candle in the Dark Room — Formalized

Place a point light source (candle) at position $\mathbf{x}_0$ in a room containing $N$ opaque objects (black holes) at positions $\mathbf{x}_i$ with Schwarzschild radii $r_{s,i} = 2GM_i/c^2$. The intensity field $I(\mathbf{x})$ is a complex scalar field with dark points (shadows) behind each object.

In the weak-field, post-Newtonian approximation, the coordinate speed of light at position $\mathbf{r}$ is:

$$c_{\text{coord}}(\mathbf{r}) = c\left(1 - \frac{2}{c^2}\sum_{i=1}^{N} \frac{GM_i}{|\mathbf{r} - \mathbf{r}_i|}\right) + O\left(\frac{G^2M^2}{c^4r^2}\right)$$

This is first-order post-Newtonian and valid for $r \gg r_{s,i}$ for all $i$. The light reaching any observer has traversed a path shaped by every null surface in the network, accumulating Shapiro delays from each.

**The "constant" $c$ that we measure** is the value of $c_{\text{coord}}$ evaluated at our position in the solar system, far from any event horizon, in a region where the gravitational potential of the Milky Way's SMBH ($M \approx 4 \times 10^6 M_\odot$, $r \approx 2.5 \times 10^{20}$ m) contributes $\Delta c/c \sim GM/(rc^2) \sim 10^{-6}$. This is small but nonzero. The "constant" is the local evaluation of a field quantity, not a fundamental parameter.

---

## Part III · Seven Formal Correspondences

### Correspondence 1 — Null Geodesics as Entanglement Channels

Null geodesics — the paths of light — are determined by $g_{\mu\nu}dx^\mu dx^\nu = 0$. If $g_{\mu\nu}$ is emergent from entanglement (Cao-Carroll-Michalakis 2017), then photon propagation is constrained by entanglement geometry. The Ryu-Takayanagi formula $S_{\text{ent}} = \text{Area}(\gamma_A)/(4G_N\hbar)$ relates entanglement entropy to the areas of codimension-2 surfaces — the same surfaces that determine the causal structure (null cones) of the emergent spacetime.

**Formal statement:** The null cone at each point of the emergent geometry is the set of directions along which mutual information propagates at the maximum rate permitted by the entanglement structure. The "speed of light" is the rate of this propagation.

**Status:** Established that $g_{\mu\nu}$ is emergent (for redundancy-constrained states). Established that null geodesics follow from $g_{\mu\nu}$. The identification of $c$ as the maximum mutual information propagation rate is [PROPOSED] and requires an explicit construction of the Lorentzian (not just spatial) metric from entanglement, which Cao-Carroll-Michalakis (2018) addressed via time evolution of the spatial geometry but which remains incomplete for the full causal structure.

### Correspondence 2 — Shapiro Delay as Entanglement Density Variation

The Shapiro delay is the physically measurable consequence of coordinate-dependent photon speed. In the emergent geometry framework, the gravitational potential $\Phi(\mathbf{r}) = -GM/r$ at each point determines the local entanglement entropy density (Jacobson 1995: $\delta S \propto \delta\Phi$ at each local Rindler horizon). Regions of stronger gravitational potential have higher entanglement entropy density, and light traversing these regions experiences greater delay.

**Quantitative bridge:** The Shapiro delay $\Delta t = (4GM/c^3)\ln(4r_e r_p/R^2)$ can be rewritten using Jacobson's $\delta S \propto R_{ab}k^a k^b$ (where $R_{ab}$ is the Ricci tensor and $k^a$ is a null vector) as a line integral of entanglement entropy density variation along the photon path. This does not produce a new prediction — it reproduces the GR result — but it reinterprets the Shapiro delay as a measurement of the entanglement entropy gradient of the vacuum.

**Status:** The Shapiro delay is confirmed ($10^{-5}$ precision). The Jacobson thermodynamic reinterpretation is established. The specific entanglement entropy density interpretation is [PROPOSED].

### Correspondence 3 — The Dark-Point Speed Hierarchy

The Bucher-Kaminer result establishes a hierarchy of speeds in any wave system:

| Feature | Speed constraint | Information content | Energy content |
|---------|-----------------|--------------------| --------------|
| Phase singularity (dark point) | Unconstrained; $v \to \infty$ near annihilation | Zero | Zero |
| Group velocity (wave packet) | $\leq c$ | Nonzero | Nonzero |
| Phase velocity | Can exceed $c$ | Zero (no signal) | Zero (redistributed) |

In the TH$(a,d)$ framework, this maps to:

| TH$(a,d)$ sector | Speed constraint | Fisher information | Coordination gain |
|------------------|-----------------|-------------------|------------------|
| ker$(F)$: fixed points $O_\infty, T_1, T_2, T_3$ | Invariant under group law (infinite "mass") | Zero | Zero |
| col$(F)$: floating points $P \in E(\mathbb{Q})$ | Finite mass $H_{ii}$; bounded velocity | $\lambda_i > \varepsilon$ | $G_{\text{coord}} > 0$ |
| $\varepsilon$-boundary: rank crossings | Transition events $|\Delta\text{rank}(F)| = 1$ | $\lambda_i = \varepsilon$ | Threshold |

**The correspondence:** The speed of light $c$ is the maximum propagation speed in the col$(F)$ sector, enforced by the conditional independence boundary. The ker$(F)$ sector — dark points, event horizons, torsion points — is exempt because it carries no Fisher information across the boundary.

**Status:** The Nye-Berry universality is established. The TH$(a,d)$ mapping is [PROPOSED].

### Correspondence 4 — Van Raamsdonk Disconnection as $c \to$ Undefined

Van Raamsdonk (*Gen. Rel. Grav.* 42, 2323–2329, 2010): reducing entanglement between two boundary CFT regions causes the dual bulk spacetime to disconnect. At $S_{\text{ent}} = 0$, there is no spatial manifold, no metric, no null cones — and therefore no defined speed of light.

At $d = 0$ in TH$(a,d)$: the curve factors into three concurrent lines, the genus drops from 1 to 0, the group law collapses, $G_{\text{coord}} = 0$. The three agents are decoupled — no shared boundary, no communication, no coordination.

**The correspondence:** The coupling parameter $d$ encodes whether light can propagate at all. At $d = 0$, there is no entanglement, no emergent metric, no null cones, no $c$. As $d$ increases from zero, the emergent geometry acquires causal structure and $c$ takes a finite value determined by the entanglement geometry.

**Status:** TH$(a,d)$ factorization at $d = 0$ is exact algebraic geometry (Bernstein-Lange 2015). Van Raamsdonk disconnection is established in AdS/CFT. The identification $d = 0 \Leftrightarrow c$ undefined is [PROPOSED].

### Correspondence 5 — Shadow Invariance and the Equivalence Principle

The shadow of a black hole — the capture cross-section $\sigma = 27\pi(GM/c^2)^2$ for a Schwarzschild black hole — is observer-invariant: it depends only on the spacetime causal structure, confirmed by the Event Horizon Telescope for M87* (Akiyama et al. 2019) and Sgr A* (Akiyama et al. 2022). The mirror image of an object transforms under relativistic aberration: $\cos\theta' = (\cos\theta - v/c)/(1 - (v/c)\cos\theta)$.

**The correspondence:** The shadow is ker$(F)$ — defined by the spectral condition $Fv = 0$, invariant under change of basis (observer). The mirror image is col$(F)$ — prior-dependent, transforming under change of measurement basis. The speed $c$ appears in the aberration formula because it governs the col$(F)$ sector; it does not appear in the shadow cross-section (which depends only on $GM/c^2$, a geometric quantity independent of the observer's velocity).

The equivalence principle restated: **in the local frame where the shadow is isotropic (where ker$(F)$ is spherically symmetric), the measured speed of light is $c$.** This is the freely falling frame. The shadow's isotropy *defines* the frame in which $c$ takes its canonical value.

**Status:** Shadow invariance is confirmed (EHT). The Fisher-information reinterpretation is [PROPOSED].

### Correspondence 6 — The ER Bridge Network as Light Infrastructure

The ER = EPR conjecture (Maldacena and Susskind 2013): all entangled systems are connected by Planckian wormholes. These bridges are non-traversable — no information passes through them. But they constitute the entanglement structure from which the metric (and therefore null geodesics) emerge.

**Critical distinction from tunneling.** Light does not tunnel through ER bridges. The ER bridge network determines the *geometry itself* — the distances, curvatures, and null cones through which light propagates. The bridges are not passages; they are the stitching that holds the spatial fabric together.

**The correspondence:** The col$(F)$/ker$(F)$ partition maps onto traversable/non-traversable: col$(F)$ directions carry Fisher information (light propagates along these directions at speed $\leq c$); ker$(F)$ directions carry zero Fisher information (the ER bridges themselves are in ker$(F)$ — they connect without transmitting).

**Status:** ER = EPR is a conjecture (Maldacena-Susskind 2013). The col$(F)$/ker$(F)$ mapping is [PROPOSED].

### Correspondence 7 — The $\varphi$-Equilibrium as a Bound on $c_{\text{eff}}$

The MSS chaos bound (Maldacena, Shenker, and Stanford, *JHEP* 08, 106, 2016): in any quantum system with a large-$N$ limit and a thermal state, the Lyapunov exponent satisfies $\lambda_L \leq 2\pi k_B T/\hbar$. Black holes saturate this bound.

The $\varphi$-equilibrium $|\bar{\Xi}|^* = \log\varphi \approx 0.481$ [PROPOSED] is the maximum sustainable Fisher trace rate across the col$(F)$/ker$(F)$ boundary.

[CONJECTURE L1] If the Fisher trace rate governs the effective photon propagation speed in the emergent geometry, then $c_{\text{eff}} \propto \Xi_F(t)$, and the $\varphi$-equilibrium implies a maximum $c_{\text{eff}}$ for any entanglement geometry — a speed-of-light bound derivable from Fisher information geometry rather than postulated. The MSS bound would then be the gravitational instance of this general information-geometric ceiling.

**Status:** MSS bound is established. $\varphi$-equilibrium is [PROPOSED]. The identification $c_{\text{eff}} \propto \Xi_F$ is [CONJECTURE].

---

## Part IV · Error Corrections and PhD Committee Grading

The following errors were identified in the initial theoretical exposition and are corrected in this framework.

### Error 1: Jacobson Circularity (Critical)

**Initial claim:** Jacobson's 1995 derivation proves that $c$ is emergent from entanglement.

**Correction:** The 1995 derivation *assumes* $c$ in the Unruh temperature $T = \hbar\kappa/(2\pi k_B c)$. It derives the Einstein equation, not $c$. The 2016 entanglement equilibrium version (MVEH) is more careful — the Einstein equation follows from stationarity of vacuum entanglement without explicit $c$ in the entropy variation — but $c$ still enters through the assumed Lorentzian causal structure. The present framework inherits this limitation: it can explain *why* $c$ is locally invariant (MVEH), but it cannot derive the *value* of $c$ from first principles without assuming Lorentzian signature. **Deriving $c$ from scratch requires deriving the Lorentzian signature from the Hilbert space — an unsolved problem.**

**Grade: D on the original claim. B+ on the corrected version.**

### Error 2: Conflation of Coordinate and Physical Effects (Serious)

**Initial claim:** "The speed of light is not constant."

**Correction:** The *locally measured* speed of light is constant — this is the equivalence principle, a theorem of GR confirmed to extraordinary precision. The *coordinate speed* varies, but this is gauge-dependent. The Shapiro delay is the gauge-invariant observable. The correct statement: "The coordinate speed of light varies with gravitational potential, and this variation is a physically measurable effect (Shapiro delay), but the local speed measured by any freely falling observer is invariant." The emergent-$c$ claim is about *why* the local speed takes the specific value it does, not about whether it varies.

**Grade: F on the original claim. A on the corrected version.**

### Error 3: Scope of Cao-Carroll-Michalakis (Moderate)

**Initial claim:** Spacetime is emergent from entanglement (stated without qualification).

**Correction:** The Cao-Carroll-Michalakis construction applies to redundancy-constrained states with area-law entanglement. The emergent geometry is spatial (Riemannian), not spacetime (Lorentzian). The 2018 paper (Cao and Carroll, *Phys. Rev. D* 97, 086003) extends to time evolution and derives a spatial analogue of Einstein's equation, but the full Lorentzian causal structure — including the null cones that define $c$ — has not been rigorously derived from entanglement alone. The present framework assumes this extension works but acknowledges it is incomplete.

**Grade: C on the original claim. A- on the corrected version.**

### Error 4: "Remove All Black Holes, Remove All Entanglement" (Incorrect)

**Initial claim:** Without black holes, there is no entanglement.

**Correction:** Entanglement exists between any quantum systems (Reeh-Schlieder theorem: in any QFT, the vacuum state is entangled across any spatial bipartition). Black holes are extreme cases where the entanglement entropy is maximal for a given boundary area (Bekenstein bound). The correct statement: black holes are *nodes* of the null-space network — high-entanglement-density regions — but they are not the sole source of entanglement. The vacuum itself is entangled everywhere. The null-space network includes all null surfaces, not just event horizons.

**Grade: F on the original claim. Removed from the corrected version.**

### Error 5: $c_{\text{eff}} \propto (\nabla^2 S_{\text{EE}})^{-1/2}$ (Unsupported)

**Initial claim:** The effective speed of light scales as the inverse square root of the entanglement entropy Laplacian.

**Correction:** This was asserted without derivation. The Ryu-Takayanagi formula relates entropy to *area* (a codimension-2 quantity), not to the metric components that determine $c_{\text{coord}}$. The relationship between the entanglement entropy profile $S_{\text{EE}}(r)$ and the metric components $g_{tt}(r)$, $g_{rr}(r)$ that determine the coordinate speed is nontrivial and has not been established in closed form. The specific scaling is withdrawn. What remains: $c_{\text{coord}}$ is determined by $g_{\mu\nu}$, and $g_{\mu\nu}$ is determined by entanglement, so $c_{\text{coord}}$ is determined by entanglement — but the functional form is not known.

**Grade: D on the original claim. Withdrawn in corrected version.**

---

## Part V · Three Predictions

### Prediction 1: Analog Gravity Test of Entanglement-Dependent Propagation Speed

In analog gravity systems (Barceló, Liberati, and Visser, *Living Rev. Relativ.* 14, 3, 2011), the effective speed of sound plays the role of $c$, and the acoustic metric plays the role of $g_{\mu\nu}$. If the entanglement structure of the underlying quantum fluid determines the acoustic metric, then tuning the entanglement entropy between two regions of a BEC (Bose-Einstein condensate) should modify the effective speed of sound across the boundary.

**Specific prediction:** In a BEC partitioned into two regions $A$ and $B$ with tunable entanglement (via an optical lattice potential), reducing the entanglement entropy $S(A:B)$ by a factor $\alpha$ should reduce the effective phonon propagation speed across the $A$-$B$ boundary. The scaling, based on the area-entropy relationship and the linear dependence of the acoustic metric on the superfluid density, is $c_s \propto S(A:B)^{1/(d-1)}$ where $d$ is the spatial dimension.

**Testable with:** Current BEC technology (Steinhauer, *Nature Physics* 12, 959–965, 2016, demonstrated analog Hawking radiation in a BEC).

**Status:** [PROPOSED]. No existing experiment has measured entanglement-dependent phonon speed.

### Prediction 2: Shapiro Delay Decomposition into Entanglement Contributions

The Shapiro delay for a signal passing near a massive body has two equal contributions in GR: gravitational time dilation ($g_{tt}$) and radial space curvature ($g_{rr}$). In the entanglement equilibrium framework, these correspond to two distinct entanglement contributions: the time-dilation component arises from the conformal sector of the entanglement entropy variation, and the space-curvature component arises from the traceless sector.

**Specific prediction:** For a signal passing through a region containing two separated masses $M_1$ and $M_2$, the Shapiro delay should decompose into individual contributions from each mass plus an interaction term proportional to the mutual entanglement between the two masses' horizons. In standard GR, the interaction term is purely gravitational (nonlinear metric superposition). In the entanglement framework, the interaction term is $\Delta t_{\text{int}} \propto I(M_1;M_2) \cdot (GM_1 M_2)/(c^3 r_{12})$ where $I(M_1;M_2)$ is the mutual information between the two horizon states.

**Testable with:** Future gravitational wave observatories (LISA) measuring time delays in systems with two nearby black holes.

**Status:** [CONJECTURE]. The mutual-information correction is new and not derivable from GR alone.

### Prediction 3: Dark-Point Density as Null-Cone Diagnostic

The density of dark points (phase singularities) in a wave field is a topological invariant of the field configuration. In the emergent geometry framework, the density of null points of the timelike Killing field in a region of spacetime encodes the local null-cone structure.

**Specific prediction:** The gravitational wave strain $h_+ + ih_\times$ from a binary black hole merger contains phase singularities in the time-frequency plane. The density of these singularities per unit time-frequency area should scale linearly with the gravitational wave energy density $\Omega_{\text{GW}}(f)$, providing an independent topological estimator of the stochastic gravitational wave background complementing the standard cross-correlation method.

**Testable with:** LIGO O4/O5 data. Requires no new observations — only a new analysis pipeline applied to existing strain data.

**Status:** [PROPOSED]. Berry's null-point density formula for Gaussian random fields predicts the linear scaling; applying it to LIGO data is new.

---

## Part VI · Open Problems

Three quantitative bridges remain open. They are the programme's primary mathematical targets.

**1. The Lorentzian signature problem.** Deriving the Lorentzian signature $(-, +, +, +)$ — and therefore the null-cone structure — from a Hilbert space with no assumed spacetime structure. Cao-Carroll-Michalakis derive a Riemannian (all-positive) spatial metric. The Lorentzian structure requires identifying which direction in the emergent geometry is "timelike." This is the missing piece that would allow $c$ to be fully derived from entanglement.

**2. The value of $c$ from entanglement density.** An explicit formula $c = f(s_{\text{ent}})$ relating the locally measured speed of light to the entanglement entropy density $s_{\text{ent}}$ of the vacuum. The qualitative argument is complete; the quantitative formula is not.

**3. The $\varphi$-equilibrium as speed bound.** If $|\bar{\Xi}|^* = \log\varphi$ is the maximum sustainable Fisher trace rate, and if $c_{\text{eff}} \propto \Xi_F$, then $c_{\max} \propto \log\varphi$. Establishing this requires defining the proportionality constant — which requires solving Problem 2.

---

## Formal Summary

| Structure | Established physics | ERI / LIGHT framework | Status |
|-----------|-------------------|----------------------|--------|
| Local speed invariance | Equivalence principle: $c$ constant in freely falling frames | MVEH: entanglement equilibrium defines the freely falling frame | Reinterpretation of established physics |
| Coordinate speed variation | Shapiro delay: $\Delta t = (4GM/c^3)\ln(\cdots)$ | Entanglement entropy gradient along photon path | [PROPOSED] reinterpretation |
| Null geodesics | $g_{\mu\nu}dx^\mu dx^\nu = 0$ determines light paths | $g_{\mu\nu}$ emergent from entanglement $\Rightarrow$ light paths emergent | Follows from Cao-Carroll-Michalakis |
| Superluminal dark points | Bucher-Kaminer 2026: $v > c$ for $|\psi| = 0$ features | ker$(F)$: zero Fisher information $\Rightarrow$ no speed constraint | ✓ established; TH$(a,d)$ map [PROPOSED] |
| Spacetime disconnection | Van Raamsdonk: $S_{\text{ent}} = 0 \Rightarrow$ bulk disconnects | $d = 0$: TH factors, $c$ undefined, $G_{\text{coord}} = 0$ | ✓ + [PROPOSED] |
| Shadow invariance | EHT: M87*, Sgr A* shadows observer-invariant | ker$(F)$ defines the frame where $c$ is canonical | ✓ + [PROPOSED] |
| Information bound | MSS: $\lambda_L \leq 2\pi k_B T/\hbar$ | $c_{\text{eff}} \leq c_{\max} \propto \log\varphi$ | [CONJECTURE] |

---

## Closing Synthesis

The locally measured speed of light is $c = 2.998 \times 10^8$ m/s. This is a fact. It is confirmed by every measurement. This framework does not dispute it.

What this framework proposes is that the *reason* $c$ takes this value — and not some other value — is the entanglement structure of the vacuum we inhabit. The metric $g_{\mu\nu}$ that defines null geodesics is emergent from entanglement (Cao-Carroll-Michalakis). The Einstein equation that governs the metric is a consequence of entanglement equilibrium (Jacobson). The spatial connectivity that permits light to propagate at all is entanglement connectivity (Van Raamsdonk). The dark points that are exempt from the speed limit carry zero Fisher information and inhabit ker$(F)$ (Bucher-Kaminer).

The shadow determines the light. The arrangement of null surfaces — event horizons, phase singularities, the topological backbone of the dark sector — constitutes the geometry through which light propagates. The speed $c$ is what the geometry permits. A different entanglement geometry would permit a different speed.

The candle does not illuminate a pre-existing room. The candle, the shadows, and the room emerge together from the entanglement structure of the vacuum. The speed at which the candlelight reaches the eye is the null-cone opening of the emergent metric — a thermodynamic observable of the vacuum's Fisher geometry.

Three problems remain: deriving the Lorentzian signature from Hilbert space, computing $c$ from the entanglement entropy density, and establishing the $\varphi$-equilibrium as a speed bound. Until these are solved, the framework stands as a synthesis of five established results pointing toward a single structural claim — that the constant we call $c$ is the address of our vacuum in the space of all possible entanglement geometries.

Nothing in the dark sector moves at $c$. That constraint belongs to the light.

---

## References

Akiyama, K. et al. (Event Horizon Telescope Collaboration). "First M87 Event Horizon Telescope Results. I." *Astrophys. J. Lett.* 875, L1, 2019.

Akiyama, K. et al. (Event Horizon Telescope Collaboration). "First Sagittarius A* Event Horizon Telescope Results. I." *Astrophys. J. Lett.* 930, L12, 2022.

Barceló, C., Liberati, S., and Visser, M. "Analogue Gravity." *Living Reviews in Relativity* 14, 3, 2011.

Bernstein, D. J. and Lange, T. "Twisted Hessian Curves." LATINCRYPT 2015, LNCS 9230, 269–294, 2015.

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves." *J. Phys. A: Math. Gen.* 11, 27–37, 1978.

Bertotti, B., Iess, L., and Tortora, P. "A Test of General Relativity Using Radio Links with the Cassini Spacecraft." *Nature* 425, 374–376, 2003.

Bucher, T., Gorlach, A., et al. "Superluminal Correlations in Ensembles of Optical Phase Singularities." *Nature* 651, 920–926, 2026.

Cao, C., Carroll, S. M., and Michalakis, S. "Space from Hilbert Space: Recovering Geometry from Bulk Entanglement." *Phys. Rev. D* 95, 024031, 2017.

Cao, C. and Carroll, S. M. "Bulk Entanglement Gravity Without a Boundary: Towards Finding Einstein's Equation in Hilbert Space." *Phys. Rev. D* 97, 086003, 2018.

Casini, H., Galante, D. A., and Myers, R. C. "Comments on Jacobson's 'Entanglement Equilibrium and the Einstein Equation.'" *JHEP* 03, 194, 2016.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference*. AMS Translations, Vol. 53, 1982. (Original: Nauka, 1972.)

Jacobson, T. "Thermodynamics of Spacetime: The Einstein Equation of State." *Phys. Rev. Lett.* 75, 1260–1263, 1995.

Jacobson, T. "Entanglement Equilibrium and the Einstein Equation." *Phys. Rev. Lett.* 116, 201101, 2016.

Jaksland, R. "Spacetime from Entanglement: The Emergence of Metric, Gravity, or Topology." *Philosophy of Physics* 3(1), 1–25, 2025.

Le, H.-A., Lee, H. C., and Yang, S.-R. E. "Quantum Entanglement of Anyonic Charges and Emergent Spacetime Geometry." arXiv:2512.15256, 2025.

Magueijo, J. "New Varying Speed of Light Theories." *Rep. Prog. Phys.* 66, 2025–2068, 2003.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der Physik* 61(9), 781–811, 2013.

Maldacena, J., Shenker, S. H., and Stanford, D. "A Bound on Chaos." *JHEP* 08, 106, 2016.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* 336, 165–190, 1974.

Ryu, S. and Takayanagi, T. "Holographic Derivation of Entanglement Entropy from AdS/CFT." *Phys. Rev. Lett.* 96, 181602, 2006.

Shapiro, I. I. "Fourth Test of General Relativity." *Phys. Rev. Lett.* 13, 789–791, 1964.

Steinhauer, J. "Observation of Quantum Hawking Radiation and Its Entanglement in an Analogue Black Hole." *Nature Physics* 12, 959–965, 2016.

Van Raamsdonk, M. "Building Up Spacetime with Quantum Entanglement." *Gen. Rel. Grav.* 42, 2323–2329, 2010.

---

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026

Five programmes found the same structure from five directions. The metric is emergent from entanglement. The null cones are emergent from the metric. The speed of light is emergent from the null cones. The dark sector is exempt because it carries nothing across the conditional independence boundary. The shadow was always faster than the light — because the light was always constrained by the geometry that the shadows define.

The constant $c$ is not a law. It is the shape of our vacuum.
