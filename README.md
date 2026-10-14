# 24-hour movement behaviour intervention analyses

R code accompanying **Comparative Effects of Interventions on 24-Hour Movement Behaviours in Children and Adolescents: A Systematic Review with Network and Component Network Meta-Analyses**.

## Download

[Download the complete R code package](24h-movement-nma-cnma_20261014.zip).

The code is distributed as a ZIP archive that preserves the analysis directory structure. Extract the archive and open the `24h-movement-nma-cnma` directory. Its README contains the full running instructions.

## Contents

- 11 R scripts covering pairwise meta-analysis, standard network meta-analysis, sensitivity analyses, network meta-regression, exploratory additive component analyses, auxiliary analyses and code verification.
- Input-format documentation and 15 CSV templates containing column headers only.
- Recorded software versions, source provenance, documented portability changes and SHA-256 checksums.

**Actual analysis input data and result datasets are not included.** Model execution requires the separately supplied populated input files described in the package. The manuscript and published-paper PDFs are not part of this code release.

## Verification

The R files passed syntax/dependency checks. The portable copies were run locally, and the matching archived numerical outputs from 10 tables were identical. The pre-existing optional S07 sensitivity branch executed successfully but has no archived numerical counterpart; its documented count-verification correction is confined to the release copy. See `docs/VERIFICATION.md` and `docs/PORTABILITY_CHANGES.md` inside the archive for the precise scope.

## Quick start

After extracting the archive and installing the packages listed in its README:

```sh
Rscript --vanilla verify_code.R
```

This command checks syntax and installed dependencies; it does not reproduce results without actual input data.

## Archive integrity

SHA-256 of `24h-movement-nma-cnma_20261014.zip`:

```
bca81c4debbbddfe8c8f27af879ce7ff8d135b3ad28449511a74354cc66e8714
```

## Code Availability

The R code used for the statistical analyses, together with input-format documentation, is publicly available at https://github.com/anlongd354-gif/24h-movement-nma-cnma.
