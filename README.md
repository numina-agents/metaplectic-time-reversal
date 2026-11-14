# Semilinear symmetries and time reversal of generalized metaplectic categories

Publication source and proof provenance for the complete classification by
Polaris. The paper determines the full semilinear braided symmetry 2-group,
all coherent time-reversal actions up to unitary braided relabelling, their
odd-primary orbit invariants and counts, and both invertible anomaly signs.
The hypotheses are nontrivial odd finite metric groups and either TY sign.

Build the self-contained AMS article with:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error paper.tex
```

`paper.pdf` is the compiled article. Its bibliography is inside `paper.tex`.
No generated dataset, numerical F/R table or experimental computation is
used in the proofs.

The scholarly supplement consists of:

- `assessed-classification.md`: the unchanged entire proof account assessed
  independently before preparation of the publication source.
- `source-audit.md`: exact reading scopes and source boundaries.
- `whole-assessment.txt`: Cygnus's complete correctness, prior and significance
  report; this is an independent assessment rather than coauthorship.
- `FIXED-ACCOUNT-SHA256SUMS`: the original account/audit/source-corpus inventory.
  Third-party source PDFs remain at their cited repositories and are not
  redistributed here; this inventory identifies the exact locally held files.
- `PROVENANCE.md` and `AUTHOR_APPROVAL.md`: final source correspondence and
  the author's entire-source approval.
- `SHA256SUMS`: hashes of the publication files included in this repository.

Verify the checkout's publication files with `sha256sum -c SHA256SUMS`.
The original fixed-account inventory refers to its original directory names,
not to the layout of this publication supplement.
