# Fixed whole-account source audit

Polaris, 14 November 2026. This file accompanies classification.md and the
exact source PDFs and text extractions in sources/. These are the only
auxiliary source/audit files relied on by the classification account.
The earlier exploratory coherence.md is superseded and NOT part of the
account. No Atlas tables, numerical F/R files or computed datasets enter
the claimed theorem. The prescribed control has an exact proof in section 7.

## Source inventory and what was actually read

* metaplectic.pdf/.txt: Bischoff, arXiv:1803.04949v1.
  Complete Lemmas 4.5--4.6, Proposition 4.7, Theorem 4.8 proof and
  Proposition 4.13 proof; section 3.4 centre/TY setup and Proposition 3.9;
  Theorems 4.10 and 4.12 statements. Prior: actual category classification,
  unique boson, TY de-equivariantisation and orthogonal-sum condensation.
  The ordinary product/condensation law is NOT a new theorem of this work.

* crossed-ty.pdf/.txt: Galindo, arXiv:2010.00847v1.
  Section 4.2 skeletal associators, complete Lemma 4.8 and Theorem 4.9
  proofs, Proposition 4.12 statement. Prior: strict inversion, natural
  grading sign, complete crossed braiding/ribbon coefficients. Galindo's
  quadratic-refinement convention is inverse to q in the GLM convention.
  No claim that the full paper was audited.

* crossed-orbifolds.pdf/.txt: Galindo--Lentner--Moeller,
  arXiv:2409.16357v2. Complete section 3, including Theorem 3.2 model,
  Remark 3.4 alpha-sign equivalence, Proposition 3.7 proof, Corollary 3.9;
  section 2.2 definitions and equivariantisation setup. Proposition 3.8
  cites GNN's nondegeneracy result; its original proof was not audited.
  Prior: all coefficients/conventions used in classification.md section 2.
  The general extension/condensation/VOA results were not audited.

* auto-verlinde.pdf/.txt: Cain Edie-Michell, 2022 author PDF fetched from
  https://par.nsf.gov/servlets/purl/10321271, corresponding to
  arXiv:2002.03220. Complete Lemma 2.16 proof, Remark 2.17, braided section
  4.2 through Lemmas 4.6--4.8. The earlier gauge-triviality proof supplying
  that section's upper bound was not audited. Prior: complete ordinary TY
  tensor-auto-equivalence classification, cyclic complex-linear braided
  metaplectic auto-equivalence groups. Its terminology tau denotes the TY
  sign, with the Fourier coefficient tau/sqrt(|A|).

* dgno.pdf/.txt: Drinfeld--Gelaki--Nikshych--Ostrik,
  arXiv:0906.0620v3. Complete section 4.4.3--4.4.7, including Theorem 4.44
  and the intermediate K3 proof with Lemmas 4.47--4.54; section 4.2
  statements used by that proof. Prior: the FULL functorial 2-equivalence,
  not merely a correspondence of categories. Its previous general
  equivariantisation theorems are used as cited prior, not independently
  re-proved. Semilinearity is reduced to a linear functor from the complex
  conjugate category. Restriction identifications on Rep(C2) must be kept
  until one deliberately forgets them; U_b=-1 is not a morphism over the
  specified Rep(C2). This distinction is explicit in section 3 of the account.

* time-reversal.pdf/.txt: Barkeshli--Cheng, arXiv:1706.09464v3.
  Sections III--IV, IV.F/V gauging cousins, VI.C root family including
  equations (96)--(99), conclusion; the SO(4)_4 / SU(3)_1 squared example
  in VI.B was also checked. Prior: cyclic localization/gauging-sign law,
  both obstruction and higher anomaly distinctions, and at least one
  noncyclic exponent-3 root. Noncyclic analysis with gcd(m,n)>1 is deferred
  at the end of VI.C. This work does not claim the first such example.

* fqm.pdf/.txt: Fredrik Stroemberg, arXiv:1108.0202v1.
  Entire odd-primary setup/statements of section 2, equation (2.1),
  Lemma 2.1 and Remark 2.2; Lemma 3.1 reduction. The proofs of the entire
  Weil-representation theorem and all Gauss-sum evaluations were not read.
  Prior: odd-primary Jordan rank/determinant classification and uniqueness.
  Section 5 of the account separately supplies the linking-form argument
  over the unramified quadratic extension and the intrinsic Delta_k layers;
  that extra operator/orbit calculation is NOT attributed to this source.

* reflection-anomalies.pdf/.txt: Barkeshli--Bonderson--Cheng--Jian--Walker,
  arXiv:1612.07792v1. Main anomaly statements, complete section VII.B
  handle/gluing calculation of CP2 and RP4, equations (184),(191), and
  nearby discussion of anomaly coordinates; not the whole general
  state-sum construction. Prior: the anomaly formula/framework and its
  two coordinates, not merely a conjectural indicator. Standard
  Omega_4^O=(C2)^2 is used as known bordism theory; independence of the
  two coordinates follows from w1^4 and w2^2 on RP4 and CP2. The account
  classifies invertible TQFT anomalies, not microscopic Hamiltonian models.

* equivariant-condensation.pdf/.txt: Bischoff--Jones--Lu--Penneys,
  arXiv:1811.00434v2. Complete sections 3.1--3.3, Theorems 3.6--3.7;
  section 4 descent statements. Prior: extension splits iff an invariant
  algebra admits a coherent equivariant structure, for an existing
  complex-linear action. Used to delineate the prior and avoid confusing
  failure of boson condensation with nonexistence of a bulk symmetry.

* real-ty.pdf/.txt: Plavnik--Sanford--Sconce,
  arXiv:2303.17843v3. Corrected Theorem 7.1 statement, Definition 3.9,
  section 4 setup and introduction; not the full classification proof.
  Prior: non-split real TY categories with noninvertible Galois-nontrivial
  scalar action, a different classification problem. No use of its
  unverified pentagon calculations in the proof here.

* categorical-tr.pdf/.txt: Wen--Schaefer-Nameki,
  arXiv:2603.28720v3. Sections IV.3 and VII.5 were read as HTML; the exact
  version's PDF/text is supplied. Prior: Galois-real noninvertible TY
  symmetries with skew bicharacters and no FS sign in that model. This
  differs from an external antiunitary equivalence of the fixed complex
  metaplectic category. The entire paper has not been audited.

## Claims needing whole independent scrutiny

The complete account claims the crossed-module exhaustion, its Postnikov
class, the affine action equivalence, all-primary orbit existence/counts
and every anomaly value. None has yet been independently certified.
Useful attack points are the forgetful passage from functors over
Rep(C2), possible missed tensorators, natural transformations with
restriction -1 on the boson, the extension-ring trace classification with
mixed scales, simultaneous sign quotient across primes, and identifying
categorical eta components with the local Kramers invariant in the stated
indicator convention. Existing prior is explicitly separated above.

The exploratory in-memory matrix checks at moduli 3,5,9 are NOT used in
the general proof. No code/dataset is needed to reproduce its assertions.
The exact modulus-9 control is proved algebraically in section 7.
