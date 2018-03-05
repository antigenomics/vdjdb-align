## Notebooks on 'VDJmatch: a software for database-guided T-cell receptor specificity prediction'

**Summary**

The repository contains R markdown notebooks describing each stage of the VDJmatch algorithm development

- `scope.Rmd` where we benchmark and select optimal parameters for the first stage of VDJmatch: searching for homologous CDR3 amino acid sequences within a fixed *scope*, i.e. `(#substitutions, #indels)`
- `scoring.Rmd` where we describe VDJAM, a substitution scoring matrix optimized for CDR sequences
- `segments.Rmd` where we explore Variable and Joining segment matching for TCRs recognizing the same antigen
- `metric.Rmd` where we put everything together, compute TCR homology score and subject database record informativeness, and benchmark the algorithm using data from our tetramer-sorting experiments