## Group members (GitHub usernames)
- @esonar
- @seanxie7
- @TrucTBui
- @GonCas12


# Bubble-seq

Bubble-seq captures DNA replication *bubbles* in agarose, enriches them, and sequences to map genome-wide replication origin (ORI) locations and activity.

## Shortly it does:
- Isolates replicating DNA regions (“bubbles”) → fragments → NGS.
- Peaks = candidate replication origins; coverage/timing = activity & efficiency.

## Applications
- Genome-wide **origin mapping** (human & model organisms).
- **Replication timing** and **origin efficiency** profiling.
- Compare **normal vs cancer** or **treated vs control** for replication stress.
- Link **genome instability** hotspots to ORIs and fragile sites.
- Validate/benchmark **in silico** ORI predictors.

## How to analyze (stats/ML toolbox)
- **Signal calling:** peak callers (MACS-style), local-enrichment over background, GC/mappability normalization.
- **Multiple testing:** q-values / **FDR** control (Benjamini–Hochberg).
- **Comparisons:** Wald tests / DESeq2-like GLMs for count data; non-parametric (Wilcoxon) if sketchy distributions.
- **Segmentation:** **HMMs**, Bayesian changepoint, or **CBS** to define replication domains.
- **Clustering:** k-means / hierarchical on timing/efficiency matrices; silhouette/GAP for k.
- **Integration:** overlap with G4 motifs, CpG islands, promoters, DNase/ATAC, ChIP-seq (ORC/MCM); **permutation tests** for enrichment.
- **QC:** FRiP-like metrics, IDR for replicate agreement, cross-correlation for peak quality.

---
## Links to relevant resources
- https://emea.illumina.com/science/sequencing-method-explorer/kits-and-arrays/bubble-seq.html
- https://pubmed.ncbi.nlm.nih.gov/23861383/
