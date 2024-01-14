---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

author\*: equal distribution; author†: co-corresponding author

### Under review
1. **Dongyuan Song**\*, Kexin Li\*, Xinzhou Ge, Christy Li, and Jingyi Jessica Li. ClusterDE: a post-clustering differential expression (DE) method robust to false-positive inflation caused by double dipping. *bioRxiv*, 2024 [link](https://doi.org/10.1101/2023.07.21.550107)
2. Qingyang Wang, Zhiqian Zhai, **Dongyuan Song**, and Jingyi Jessica Li. Review of computational methods for estimating cell potency from single-cell rna-seq data, with a detailed analysis of discrepancies between method description and code implementation. Under review at *Nature Communications*, 2023
3. Zhijian Li, Zain Patel, **Dongyuan Song**, Jingyi Jessica Li Guanao Yan, and Luca Pinello. Benchmarking the efficacy and scalability of computational methods for the identification of spatially variable genes and peaks. Under review at *Nature Methods*, 2023

### Peer reviewed
4. Kian Hong Kock, Patrick K Kimes, Stephen S Gisselbrecht, Sachi Inukai, Sabrina K Phanor, James L Anderson, Gayatri L Ramakrishnan, Colin H Lipper, **Dongyuan Song**, Jesse V Kurland, Julia M Rogers, Raehoon Jeong, Stephen C Blacklow, Rafael A Irizarry, and Martha L Bulyk. DNA binding analysis of rare variants in homeodomains reveals novel homeodomain specificity-determining residues. Accepted by <span style="color: blue">*Nature Communications*</span>, 2024 [<span style="color: blue">*Nature Communications*</span>](https://doi.org/10.1101/2023.06.16.545320)
5. Guanao Yan, **Dongyuan Song**, and Jingyi Jessica Li. scReadSim: a single-cell RNA-seq and ATAC-seq read simulator. *Nature Communications*, 2023 [link](https://doi.org/10.1038/s41467-023-43162-w)
6. **Dongyuan Song**, Qingyang Wang, Guanao Yan, Tianyang Liu, Tianyi Sun, and Jingyi Jessica Li. scDesign3 generates realistic in silico data for multimodal single-cell and spatial omics. *Nature Biotechnology*, 2023 [link](https://doi.org/10.1038/s41587-023-01772-1)
7. Elvis Han Cui\*, **Dongyuan Song**\*†, Weng Kee Wong, and Jingyi Jessica Li. Single-cell generalized trend model (scGTM): a flexible and interpretable model of gene expression trend along cell pseudotime. *Bioinformatics*, 38(16):3927–3934, 2022 [link](10.1093/bioinformatics/btac423)
8. **Dongyuan Song**\*, Nan Miles Xi\*, Jingyi Jessica Li, and Lin Wang. scSampler: fast diversity-preserving subsampling of large-scale single-cell transcriptomic data. *Bioinformatics*, 38(11):3126–3127, 2022 [link](https://doi.org/10.1093/bioinformatics/btac271)
9. Tianyi Sun, **Dongyuan Song**, Wei Vivian Li, and Jingyi Jessica Li. Simulating single-cell gene expression count data with preserved gene correlations by scDesign2. *Journal of Computational Biology*, 29(1):23–26, 2022 (*RECOMB* 2021) [link](10.1089/cmb.2021.0440)
10. Ruochen Jiang, Tianyi Sun, **Dongyuan Song**, and Jingyi Jessica Li. Statistics or biology: the zero-inflation controversy about scRNA-seq data. *Genome biology*, 23(31), 2022 [link](https://doi.org/10.1186/s13059-022-02601-5)
11. **Dongyuan Song**\*, Kexin Li\*, Zachary Hemminger, Roy Wollman, and Jingyi Jessica Li. scPNMF: sparse gene encoding of single cells to facilitate gene selection for targeted gene profiling. *Bioinformatics*, 37(Supplement 1):i358–i366, 2021 (*ISMB/ECCV* 2021) [link](https://doi.org/10.1093/bioinformatics/btab273)
12. Xinzhou Ge, Yiling Elaine Chen, **Dongyuan Song**, MeiLu McDermott, Kyla Woyshner, Antigoni Manousopoulou, Ning Wang, Wei Li, Leo D Wang, and Jingyi Jessica Li. Clipper: p-value-free FDR control on high-throughput data from two conditions. *Genome biology*, 22(288), 2021 [link](https://doi.org/10.1186/s13059-021-02506-9)
13. Tianyi Sun, **Dongyuan Song**, Wei Vivian Li, and Jingyi Jessica Li. scDesign2: a transparent simulator that generates high-fidelity single-cell gene expression count data with gene correlations captured. *Genome biology*, 22(163), 2021 [link](https://doi.org/10.1186/s13059-021-02367-2)
14. **Dongyuan Song** and Jingyi Jessica Li. PseudotimeDE: inference of differential gene expression along cell pseudotime with well-calibrated p-values from single-cell RNA sequencing data. *Genome biology*, 22(124), 2021 [link](https://doi.org/10.1186/s13059-021-02341-y)
15. Elizabeth Christina Miller, Kenji T Hayashi, **Dongyuan Song**, and John J Wiens. Explaining the ocean’s richest biodiversity hotspot and global patterns of fish diversity. *Proceedings of the Royal Society B*, 285(1888):20181314, 2018 [link](https://doi.org/10.1098/rspb.2018.1314)
16. **Dongyuan Song**\*, Zhe Wang\*, Zhuo-Jun Song, Cheng-Chuan Zhou, Peng-Hao Xu, Jie Yang, Ji Yang, and Bao-Rong Lu. Increased novel single nucleotide polymorphisms in weedy rice populations associated with the change of farming styles: Implications in adaptive mutation and evolution. *Journal of Systematics and Evolution*, 55(2):149–157, 2017 [link](https://doi.org/10.1111/jse.12230)
