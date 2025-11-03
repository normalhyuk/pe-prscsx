## Polygenic risk for pre-eclampsia and the long-term risk of incident hypertension and cardiovascular disease: A population-based cohort study

---
Eun-Saem Choi, MD†, Sang-Hyuk Jung, PhD†, Young Mi Jung, MD, Chan-Wook Park, MD, PhD, Joong Shin Park, MD, PhD, Jong Kwan Jun, MD, PhD, Jaeyoung Kim, MS, Beomsu Kim, PhD, Chamlee Cho, PhD, Injeong Shim, PhD, Dokyoon Kim, PhD, Hong-Hee Won, PhD*, Seung Mi Lee, MD, PhD*

---

### Pre-eclampsia Polygenic risk score (PRS)
> [prscsx-pe-multi.zip](https://github.com/normalhyuk/pe-prs-csx/blob/main/prs-model/prscsx-pe-multi.zip)

## Data Source (GWAS summary statistics)
To generate enhanced cross-ancestry-based PRS with transferability, the genome-wide association study (GWAS) summary statistics from three worldwide biobanks, including the FinnGen Consortium (n=173,746; EUR), UKBB (n=220,617; EUR), and BioBank Japan (BBJ) (n=82,085; Asian), were used.

## PRS Generation
PRS for PE was constructed using the Bayesian cross-ancestry polygenic prediction method, PRS-CSx (extension version of PRS-CS), which infers the posterior mean effect size of each variant using linkage disequilibrium reference panels by population and GWAS summary statistics from multiple populations. [1,2] The individual PRSs were computed from beta coefficients as the weighted sum of the risk alleles using PLINK 1.90 with the score command. [3]


## References
1.	Ge, Tian, et al. "Polygenic prediction via Bayesian regression and continuous shrinkage priors." _Nature communications_ **10.1** (2019): 1776.
2.	Ruan, Yunfeng, et al. "Improving polygenic prediction in ancestrally diverse populations." _Nature genetics_ **54.5** (2022): 573-580.
3.	Chang, Christopher C., et al. "Second-generation PLINK: rising to the challenge of larger and richer datasets." _Gigascience_ **4.1** (2015): s13742-015.
