This repository contains the source of the **O20** Cosmochrony paper  
*Projective Persistence and the Physical Sub-Spectrum:
A Dynamical Selection Criterion for the Capacity Exponent*.

This work extends the **spectral admissibility sub-programme** by addressing
the next structural issue left open by **O19**:

> Given a supplied observable, threshold and power law, which exponent interval corresponds to
> a crossing within a specified cascade window?

**Version 1.17.** The former physical interpretation of $[7.4,10.6]$ is withdrawn.
O6 proves only $\beta_{\mathrm{eff}}\leq1/(\alpha+1/2)$ under its effective growth hypothesis
(G_R) and a power-law redundancy Ansatz in the exploration variable $p$.
Its countermodel $\alpha=8$, $p=n^{1/17}$ satisfies those premises but refutes equality.
The reciprocal is retained only as a defined legacy diagnostic; the historical range $[7.4,10.6]$
is neither a necessary nor a sufficient condition selecting the charged-lepton cascade window.

# Context

**O19** established that:

- the physically relevant observable is the **canonical pair-level**
  quantity
  \[
  \sigma_{\mathrm{pair}}^{\mathrm{can}}(n)
  \]
- the residual amplitude ambiguity inherited from the O12/O13
  Gram–Schmidt pipeline can be removed canonically
- the exponent \(\delta_{\mathrm{pair}}\) is invariant under this
  canonicalisation
- the measured fibre-level exponent remains
  \[
  \delta_{\mathrm{pair}} \approx 7.44
  \]

This closed the normalisation problem of **O19**:

- the observable class had already been fixed by **O16–O18**
- the amplitude is now canonically normalised
- the threshold-crossing template must determine its own symbolic interval;
  it supplies no physical restriction to the historical range $[7.4,10.6]$

This defines the scope of **O20**.

# Core Result

The paper proposes a **projective persistence criterion**.

A fibre
\[
\{c,q-c\}
\]
is declared physically admissible if and only if the canonical observable
\[
\sigma_{\mathrm{pair}}^{\mathrm{can}}(n)
\]
reaches a Born–Infeld saturation threshold
\[
\sigma_{\mathrm{BI}}
\]
within the effective cascade window
\[
[n_0,n_1]
\]
defined by the pre-saturation regime.

Under two structural hypotheses,

- **[H1]** \(\sigma_{\mathrm{pair}}^{\mathrm{can}}(n)\) is a monotone
  function of an effective fibre-level amplitude
- **[H2]** this amplitude inherits the Born–Infeld saturation bound
  \[
  A_n^{\max}=\frac{c_{\mathrm{BI}}}{\sqrt{\lambda_n}}
  \]

the persistence condition becomes equivalent to an admissible exponent window
\[
\delta_{\mathrm{pair}} \in [\delta_{\min},\delta_{\max}]
\]
with endpoints determined by \(\sigma_{\mathrm{BI}}\), \(n_0\), and \(n_1\).

The contribution of O20 is therefore precise:

> it does not yet derive the saturation threshold from first principles,  
> it identifies the structural criterion that a physical fibre-level observable
> must satisfy in order to belong to the admissible sub-spectrum.

# Main Structural Results

## 1. Observable hierarchy fixed

The paper starts from the hierarchy established by O12–O19:

- raw cumulative span
  \[
  \Sigma^{(c)}(n)
  \]
- normalised block observable
  \[
  \sigma_c(n)
  \]
- pair observable
  \[
  \sigma_{\mathrm{pair}}(n)=\sigma_c(n)\,\sigma_{q-c}(n)
  \]
- canonical pair observable
  \[
  \sigma_{\mathrm{pair}}^{\mathrm{can}}(n)
  \]

The key point is:

> O20 does not redefine the observable.  
> It uses the canonical fibre-level observable already fixed by O19.

## 2. Block-level mismatch is now definitively bypassed

The paper recalls that:

- the block-level exponent
  \[
  \hat{\delta}_{\mathrm{exact}} \approx 3.72
  \]
  is structurally below the physical target range
- O15 proved that no reweighting of block data can recover the target
- O16–O18 motivate the pair-level observable (the reading of pairs as fibres of \(\Pi\)
  remains the open bridge of O18 Remark 3.2)
- O19 made this pair-level observable canonical at the amplitude level

Thus O20 works entirely beyond the block-level mismatch.

## 3. Conditional persistence criterion

The central proposition states that, under [H1] and [H2], a fibre is
**projectively persistent** if and only if there exists
\[
n^* \in [n_0,n_1]
\]
such that
\[
\sigma_{\mathrm{pair}}^{\mathrm{can}}(n^*)=\sigma_{\mathrm{BI}}.
\]

Under the empirically established power-law ansatz
\[
\sigma_{\mathrm{pair}}^{\mathrm{can}}(n)\sim C\,n^{-\delta_{\mathrm{pair}}},
\]
this gives
\[
n^*(\delta_{\mathrm{pair}})
=
\left(\frac{C}{\sigma_{\mathrm{BI}}}\right)^{1/\delta_{\mathrm{pair}}}
\]
and therefore the admissible interval
\[
\delta_{\mathrm{pair}}
\in
\left[
\frac{\log(C/\sigma_{\mathrm{BI}})}{\log n_1},
\frac{\log(C/\sigma_{\mathrm{BI}})}{\log n_0}
\right].
\]

## 4. No derived numerical lower endpoint

The doubling identity $\delta_{\mathrm{pair}}=2\delta_c$ does not select $\delta_c$ or the number 7.4.
A supplied value near 7.44 lies in the historical comparison range, but does not fix the lower endpoint
of the threshold interval.

## 5. No reciprocal inference of an upper endpoint

The value 10.6 is not an endpoint consequence of O6/O7 or of the persistence hypotheses.
The old equality cannot be used to infer it from $\beta^*\in(0.09,0.13)$.
The threshold, amplitude and cascade window must determine their own endpoints.

## 6. The central open problem is identified precisely

The main unresolved issue is now:

> derive \(\sigma_{\mathrm{BI}}\) directly from the Born–Infeld saturation
> constraint
> \[
> |\partial_t \chi_v|\le c_{\mathrm{BI}}
> \]
> without using the phenomenological window as input.

This is the key problem that separates a conditionally consistent persistence
window from a physical construction; supplying the threshold alone would not select numerical endpoints.

# Mathematical Role of O20

The mathematical contribution is a symbolic threshold-crossing interval under explicit premises.
It does not convert $[7.4,10.6]$ into a derived physical selection window.

More precisely, the paper does the following:

- imports the canonical observable from O19
- formulates two explicit structural hypotheses
- derives a necessary and sufficient threshold-crossing condition
- translates that condition into an admissible interval for
  \(\delta_{\mathrm{pair}}\)
- shows that the measured value
  \[
  \delta_{\mathrm{pair}} \approx 7.44
  \]
  can be compared numerically with the historical range, without fixing either endpoint

The central point is:

> O20 is not a paper about changing the exponent,  
> but about assigning a structural admissibility criterion to it.

# Epistemic Structure of the Paper

A major feature of O20 is that it separates clearly:

## Established input

- the existence of the power-law regime
- the measured value \(\delta_{\mathrm{pair}}\approx 7.44\)
- the necessity of the pair-level observable (its fibre reading is an open bridge, O18 Remark 3.2)
- the canonical amplitude normalisation of O19

## Conditional proposal

- the identification of persistence with threshold crossing
- the interpretation of
  \(\sigma_{\mathrm{pair}}^{\mathrm{can}}(n)\)
  as a monotone image of a fibre-level amplitude
- the inheritance of a Born–Infeld saturation threshold at the fibre level

## Open problems

- derive the threshold \(\sigma_{\mathrm{BI}}\) intrinsically
- derive the monotone correspondence between span-based redundancy and
  fibre-level amplitude
- determine the large-\(q\) stability of the persistence window

This epistemic separation is part of the contribution of O20 itself.

# Interpretation of the Result

The conceptual significance of O20 is that the question is no longer:

> Why is \(\delta_{\mathrm{pair}}\) numerically close to the target window?

but instead:

> Under what structural condition does a fibre-level observable belong to the
> physical sub-spectrum?

This shifts the programme:

- from exponent extraction
- to admissibility selection
- from empirical compatibility
- to projective persistence

O20 therefore plays the role of a structural bridge between:

- the observable identification programme of O16–O19
- and the dynamical \(\delta_{\mathrm{pair}}\to\beta^*\) programme of O21

# Structural Role of O20

O20 occupies a very specific place in the O-series:

- **O16**: pair observable identified
- **O17**: pair dynamics derived
- **O18**: Born–Infeld parity established as a covariance of the response family; the fibre identification
  stated as an open problem
- **O19**: canonical amplitude normalisation derived
- **O20**: conditional threshold-crossing template, with no selected numerical exponent window

Thus:

- the observable is structurally motivated (its fibre reading remains an open bridge)
- the amplitude is canonical
- a supplied threshold defines a symbolic crossing interval; its physical interpretation remains conditional

Neither the persistence criterion nor a later fibre identification repairs the false O6/O7 equality.
The reciprocal evaluation remains a legacy numerical comparison.

# What O20 Adds

- explicit formulation of the **projective persistence criterion**
- explicit statement of hypotheses **[H1]** and **[H2]**
- derivation of the crossing-rank condition
  \[
  \exists\,n^*\in[n_0,n_1]:
  \sigma_{\mathrm{pair}}^{\mathrm{can}}(n^*)=\sigma_{\mathrm{BI}}
  \]
- derivation of the induced exponent window
  \[
  \delta_{\mathrm{pair}} \in [\delta_{\min},\delta_{\max}]
  \]
- separation of the symbolic interval from the historical benchmarks 7.4 and 10.6
- withdrawal of the inference of either endpoint from doubling or the former reciprocal equality
- explicit identification of the intrinsic derivation of
  \(\sigma_{\mathrm{BI}}\) as the central open problem
- a fully explicit separation between:
    - what is established
    - what is proposed
    - what remains open

# Outcome

The spectral admissibility framework is now:

- parity-equivariant at the Born–Infeld level (**O18**), with the fibre identification open
- amplitude-level canonical (**O19**)
- persistence-level structured (**O20**)

The pair observable is now:

- structurally motivated (fibre identification open, O18 Problem 2.8)
- canonically normalised
- equipped with a conditional physical admissibility criterion

# Residual Open Problems

The main remaining questions are now:

1. **Intrinsic derivation of \(\sigma_{\mathrm{BI}}\)**  
   Derive the saturation threshold directly from the Born–Infeld constraint
   and substrate dynamics

2. **Derivation of the monotone amplitude correspondence**  
   Prove the link between Gram–Schmidt redundancy growth and a fibre-level
   saturating amplitude

3. **Large-\(q\) stability of the persistence window**  
   Determine whether the selected sub-spectrum remains stable in the
   large-prime limit

4. **Capacity-to-rate boundary (O21)**
   Neither shell alignment nor an additional transport identification implies the reciprocal equality.
   A physical rate needs an independently justified growth carrier and selection mechanism.

5. **Extension beyond the current Weil/Heisenberg setting**  
   Determine how universal the persistence criterion is across broader
   admissibility models

# Status

The programme is now:

- observationally well-defined (**O17**)
- parity-equivariant, with the fibre identification stated as an open problem (**O18**)
- canonically normalised (**O19**)
- conditionally selection-based (**O20**)

Remaining work is now concentrated on:

- deriving the persistence threshold from substrate dynamics
- deriving the monotone amplitude correspondence
- completing the fibre-level cascade interpretation
- extending the analysis beyond the present spectral realisation

# Repository Structure

```text
paper/
├── out/      # Compiled O20 PDF
├── tex/      # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau,
Projective Persistence and the Physical Sub-Spectrum:
A Dynamical Selection Criterion for the Capacity Exponent,
Zenodo, 2026.

# Acknowledgements

Portions of the derivations, conceptual synthesis, numerical strategy,
and editorial refinement benefited from iterative interactions with
large language models used as analytical assistants.
All theoretical results, computations, and interpretations remain the
sole responsibility of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and further analysis of:

- projective persistence
- fibre-level admissibility
- Born–Infeld saturation thresholds
- canonical pair observables

are welcome.

Please open an issue to discuss conceptual points,
technical details, or possible extensions.
