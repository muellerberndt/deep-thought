# DEEP-THOUGHT: A self-referential, category-theoretic model of reality

DEEP-THOUGHT is a proposal for how the Universe can emerge from the simplest possible starting point, without the need for an external first cause.  
It begins with only one primitive: a single relation of something to itself.  
This primitive is the minimal act of distinction: recognising that one thing is not another, and relating it back to itself.

From this starting point, new relations form by composition, pairing, and symmetry.  
Each new relation changes the context of all others, assigning **meaning** to the entire network.  
Reality is modelled as this network repeatedly assigning meaning to itself.  
Over time, the network grows into a self-referential structure rich enough to display the large-scale patterns we call spacetime, matter, forces, and observers.

The theory is expressed in the **free symmetric monoidal dagger-compact category** on a single generating object.  
Morphisms are built from identities, symmetries, cups, caps, tensor product, and composition.  
The dagger is diagrammatic reflection.

---

## Minimal assumptions

1. **Self-reference**  
   The initial state is the identity morphism on the generating object: a loop relating only to itself.

2. **Relations as primitives**  
   Objects have no intrinsic properties; all structure comes from how they relate.

3. **Evolution by feedback**  
   The state of the Universe at step `t` is a diagram `D_t`.  
   It evolves by applying a local transformation `K_t` and feeding part of the result back into its input using the categorical trace:  
   `D_{t+1} = Tr_X( K_t ∘ ( D_t ⊗ 1_X ) )`  
   This ensures that every new state is generated from, and explained by, the state before it.

4. **Optimisation drives**  
   At each step, `K_t` is chosen to:
   - maximise **symmetry** (`S`)
   - maximise **integration** (`Φ`)
   - minimise **entropy** (`H`)

   These simple drives favour structures that are coherent, unified, and yet sufficiently differentiated.

---

## Emergent physics

From this single self-referential growth process, the following features appear:

| Phenomenon | Mechanism in DEEP-THOUGHT | Status |
|------------|---------------------------|--------|
| **3+1 spacetime** | The interaction graph of `D_t` has spectral dimension ≈ 3; the trace direction provides a time ordering. | derived |
| **Standard Model gauge groups** | Stable local valences 1, 2, 3 correspond to automorphism groups U(1), SU(2), SU(3). | derived |
| **Three fermion families** | CP-violation requires at least 3; entropy penalises more; optimisation yields exactly three. | derived |
| **Arrow of time** | Local reversibility from the dagger, global irreversibility from entropy growth. | qualitative |
| **Dark-matter-like effects** | Relational curvature mimics unseen mass; predicts lensing–entropy correlations. | testable |
| **No fourth fermion family** | Higher generations fail optimisation; absence is a prediction. | testable |
| **Primordial gravitational wave feature** | First global oscillation mode redshifted to nano-Hertz frequencies; predicts a spectral break detectable by PTAs. | testable |

---

## Why this matters

- **No first cause required**: reality is a closed, self-referential loop that explains itself.
- **Single generative rule**: one process produces space, matter, forces, and observers.
- **Derivation of structure**: features normally assumed in physics (spacetime dimension, gauge groups, particle families) appear as consequences of the optimisation.
- **Predictive power**: the framework yields concrete observational tests in gravitational waves, lensing, and particle physics.
- **Falsifiability**: failure of a key prediction forces revision of the model.

---

## Current status

This is an active research project. The current working paper can be found here:  
[DEEP-THOUGHT v0.1 PDF](https://github.com/muellerberndt/deep-thought/blob/main/paper/DEEP_THOUGHT_v0.1.pdf)

The next steps are to refine the optimisation rule, test its predictions with simulations, and compare directly with astrophysical and particle physics data.
