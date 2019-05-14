#  mock-coi1

DNA extracted from voucher arthropod specimen was amplified using ANML primers described in [Jusino et al. 2019](https://onlinelibrary.wiley.com/doi/full/10.1111/1755-0998.12951). PCR products were cloned into plasmid vectors and Sanger sequenced. While that paper describes a single mock community, the researchers in fact created a series of distinct mock samples with varying community membership. This mock community consists of a subset of the species described in their paper: specifically there are 24 representative COI sequences derived from 23 taxa. One of the distinct taxa (_Harmonia axyridis_) generated two distinct COI amplicons. The mock community used in this project consists of equimolar concentrations of plasmids, not post-plasmid PCR product. Taxonomic identities were assigned by a trained entomologist’s visual identification and were confirmed by manually aligning sequences to NCBI’s nt database.

#  Known Issues / Notes

Note:
The mock sample described above was sequenced in conjunction with hundreds of bat guano samples in a single MiSeq run. All data are availble as BioSamples [here at NCBI](https://www.ncbi.nlm.nih.gov/bioproject/518082). Individual sequence data specific to the mock sample are found in the `dataset-metadata.tsv` document.

These reads contain dual-index barcodes modeled after the Schloss lab [workflow described here](https://github.com/SchlossLab/MiSeq_WetLab_SOP/blob/master/MiSeq_WetLab_SOP.md). Reads were processed in QIIME2 as described in [this GitHub repo](https://github.com/devonorourke/tidybug/blob/master/docs/sequence_filtering.md#raw-sequence-data-processing).

Taxonomic information is listed in the fasta header for each expected mock sequence.
