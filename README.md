# ukb-cross-analysis-demo-project

The code in this repository performs a genome-wide association study on lipids in two ways:

1. A meta-analysis of GWAS results computed separately for the two cohorts:
    * [`ukb_rap_siloed_analysis`](./ukb_rap_siloed_analyses) holds notebooks for the [UK Biobank Research Analysis Platform](https://ukbiobank.dnanexus.com/panx/projects) to perform a GWAS on UK Biobank data.
    * [`aou_workbench_siloed_analysis`](./aou_workbench_siloed_analyses) holds notebooks for the [_All of Us_ Researcher Workbench](https://workbench.researchallofus.org/login) to perform a GWAS on _All of Us_ data.
    * [`meta_analysis`](./meta_analyses) holds notebooks for the meta-analysis performed via [METAL](https://genome.sph.umich.edu/wiki/METAL_Documentation).
2. A GWAS using the two cohorts pooled together as inputs:
    * [`aou_workbench_pooled_analyses`](./aou_workbench_pooled_analyses) holds notebooks for the [_All of Us_ Researcher Workbench](https://workbench.researchallofus.org/login) to perform a GWAS on _All of Us_ data pooled together with UK Biobank data.

# Project context

![Title slide](./docs/title_slide.jpg)
---

![What is this project](./docs/what_slide.jpg)
---

![Why do this project](./docs/why_slide.jpg)
---

![How are we doing this project](./docs/how_slide.jpg)
---

![Siloed approach](./docs/siloed_approach.jpg)
---

![Pooled approach](./docs/pooled_approach.jpg)
---

![Current status](./docs/current_status.jpg)
