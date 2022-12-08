# ukb-cross-analysis-demo-project

The code in this repository performs a genome-wide association study on lipids in two ways:

1. A meta-analysis of GWAS results computed separately for the two cohorts:
    * [`ukb_rap_siloed_analysis`](./ukb_rap_siloed_analyses) holds notebooks for the [UK Biobank Research Analysis Platform](https://ukbiobank.dnanexus.com/panx/projects) to perform a GWAS on UK Biobank data.
    * [`aou_workbench_siloed_analysis`](./aou_workbench_siloed_analyses) holds notebooks for the [_All of Us_ Researcher Workbench](https://workbench.researchallofus.org/login) to perform a GWAS on _All of Us_ data.
    * [`meta_analysis`](./meta_analyses) holds notebooks for the meta-analysis performed via [METAL](https://genome.sph.umich.edu/wiki/METAL_Documentation).
2. A GWAS using the two cohorts pooled together as inputs:
    * [`aou_workbench_pooled_analyses`](./aou_workbench_pooled_analyses) holds notebooks for the [_All of Us_ Researcher Workbench](https://workbench.researchallofus.org/login) to perform a GWAS on _All of Us_ data pooled together with UK Biobank data.

# Project context

Please see our [preprint on bioRxiv](https://www.biorxiv.org/content/10.1101/2022.11.29.518423):
> **Cloud gazing: demonstrating paths for unlocking the value of cloud genomics through cross-cohort analysis**
> Nicole Deflaux, Margaret Sunitha Selvaraj, Henry Robert Condon, Kelsey Mayo, Sara Haidermota, Melissa A. Basford, Chris Lunt, Anthony A. Philippakis, Dan M. Roden, Josh C. Denny, Anjene Musick, Rory Collins, Naomi Allen, Mark Effingham, David Glazer, Pradeep Natarajan, Alexander G. Bick
> bioRxiv 2022.11.29.518423; doi: https://doi.org/10.1101/2022.11.29.518423