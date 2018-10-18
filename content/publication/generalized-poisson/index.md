+++
title = "A two-parameter generalized Poisson model to improve the analysis of RNA-seq data"
date = 2010-07-29
draft = false

selected = true

tags = ["RNA-seq", "Modeling"]

authors = ["Sudeep Srivastava", "Liang Chen"]

publication_types = ["2"]

publication = "IN *Nuclear Acids Research*"

doi = "10.1093/nar/gkq670"

abstract = "Deep sequencing of RNAs (RNA-seq) has been a useful tool to characterize and quantify transcriptomes. However, there are significant challenges in the analysis of RNA-seq data, such as how to separate signals from sequencing bias and how to perform reasonable normalization. Here, we focus on a fundamental question in RNA-seq analysis: the distribution of the position-level read counts. Specifically, we propose a two-parameter generalized Poisson (GP) model to the position-level read counts. We show that the GP model fits the data much better than the traditional Poisson model. Based on the GP model, we can better estimate gene or exon expression, perform a more reasonable normalization across different samples, and improve the identification of differentially expressed genes and the identification of differentially spliced exons. The usefulness of the GP model is demonstrated by applications to multiple RNA-seq data sets."

abstract_short = "In this work, we focused on the position-level read count (i.e. the number of reads starting from each position). we propose a two-parameter generalized Poisson (GP) model to the position-level read counts. We show that the GP model fits the data much better than the traditional Poisson model."

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Links
url_pdf = "https://watermark.silverchair.com/gkq670.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAikwggIlBgkqhkiG9w0BBwagggIWMIICEgIBADCCAgsGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMwk0kAgzSYmLPqZbKAgEQgIIB3P3US7r2W68vwZ-bqXnIS5jZ31P-eRy4rO62-RrICSDy-xUgXKk2aOAe71C1xJ4oHJCmr0duBp2_StdbkKdzNe2qz1xsPuRfWggOegHBhFHVC3Z8dP9_bO4cRdg5ZP96YmvuEIwIuSNt9ysT7pFy7Io-Gxu5tz4NDMDkoB3fDFRxW1GCKT_Ni_ZUvyRiFEmxNwW0Oz6b7GuSPEDxWmeDV6MFys6KWp1iIr_14s-T-uigEfapeMjWsFzutQiryfbXuAIi5SAYnYTudnr5JLPnH5MeOH4KSoQmno3qboWVMak6m2whNBypbzr1SCd-VgJzLJBnZ8P5IAZXuHoMNmIBNbwHIjeA0QXDW0E3Lu1Jl6DH_lpoTB9X4Ef87CY3WkhrC30m5iOvrWqA-aaA708IrNBlfbV_ipnDmv0d2lCE7FDpZSTjWUlDN14vWPj-XShutu_Cv8F6yfqFvrHtFdsZvThQq_SNYK-CdI5LlUKEUX-Fwi6wLh33Sh2nrkos-gc9uT2m3YP_tuUIf8Sjbm5Jl1z9hbuydTUb61lv-ty92EUSsNS6BLknMtY-c4GJs7Gw3JSHbOIUO3oG1ls6GymRU34miaFMfqNnqgnYJA0Mf5zXmAZ0S9sC4lcq6NB6"

[image]
  # Caption (optional)
  caption = "Figure 3. ROC curves"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Top"
+++

Figure 3. ROC curves for the GP, the Poisson and the GLM (Poisson, negative binomial and quasi-Poisson links) in the identification of differentially expressed genes. Genes with the estimates in the six models and a reliable log-ratio value in the qRT-PCR experiments were considered. We further limited our studies on the standard positives (qRT-PCR absolute log-ratio >2.0, n = 218) and the standard negatives (qRT-PCR absolute log-ratio <0.2, n = 74). A true positive was required to be differentially expressed in the same direction according to both RNA-seq and qRT-PCR.
