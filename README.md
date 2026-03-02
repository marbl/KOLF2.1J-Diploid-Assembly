# KOLF2.1Jv1.1 Assembly
The personalized diploid genome of the KOLF iPSC cell line. KOLF2.1J is the parental iPSC line and serves as a reference cell line for distributed iPSC derivatives. It has a relatively stable karyotype, maintains pluripotency, exhibits consistent growth characteristics, and harbors fewer problematic structural abnormalities compared to other iPSC lines. Therefore, generating a complete telomere-to-telomere (T2T) diploid assembly for this valuable resource is warranted, as it would enable broad community use and facilitate the characterization of its personalized variants and genomic features. 

## Latest assembly releases
### v1.1 (XX, 2026)
* XXX.fasta.gz : T2T reconstruction of 45 chromosomes of KOLF iPSC line, except chrY and, include chrM.
* GenBank accession for vX.X are : [GCA_XXXXX.X]() (primary) and [GCA_XXX]() (alternative).
* This genome is viewable in the [UCSC browser](https://genome.ucsc.edu/cgi-bin/hgGateway?hgHub_do_redirect=on&hgHubConnect.remakeTrackHub=on&hgHub_do_firstDb=1&hubUrl=https://research.nhgri.nih.gov/CustomTracks/T2T_hubs/T2T_test/KOLF2.1Jv1.1/hub.txt). 

## Downloads
### Assembly materials
* Assembly graph from Verkko X.X in GFA format, no sequences included : [assembly.homopolymer.gfa]()
* Genomic paths through both graphs used for consensus : [assembly.paths.tsv]()

### Analysis set
* KOLF2.1Jv1.1 personalized graph : [graph.gfa.gz]()
  
### Methylation profile
* Methylation call using ONT data in the BED file format by cell type, see [description]()
* On KOLF2.1Jv1.1 primary
  * IPS : [iPCS.methylation.KOLF2.1Jv1.1_primary.bed.gz]()
  * NGN2 : [NGN2.methylation.KOLF2.1Jv1.1_primary.bed.gz]()
  * NEURON : [NEURON.methylation.KOLF2.1Jv1.1_primary.bed.gz]()
  * MGL : [MGL.methylation.KOLF2.1Jv1.1_primary.bed.gz]()
  * ASTRO_NYSCF : [ASTRO_NYSCF.methylation.KOLF2.1Jv1.1_primary.bed.gz]()
  * ASTRO_IND12 : [ASTRO_IND12.methylation.KOLF2.1Jv1.1_primary.bed.gz]()
* On KOLF2.1Jv1.1 alternative
  * IPS : [iPCS.methylation.KOLF2.1Jv1.1_alternative.bed.gz]()
  * NGN2 : [NGN2.methylation.KOLF2.1Jv1.1_alternative.bed.gz]()
  * NEURON : [NEURON.methylation.KOLF2.1Jv1.1_alternative.bed.gz]()
  * MGL : [MGL.methylation.KOLF2.1Jv1.1_alternative.bed.gz]()
  * ASTRO_NYSCF : [ASTRO_NYSCF.methylation.KOLF2.1Jv1.1_alternative.bed.gz]()
  * ASTRO_IND12 : [ASTRO_IND12.methylation.KOLF2.1Jv1.1_alternative.bed.gz]()

### HiC alignment
* HiC aligned on the primary haplotype, see [description]()
  * iPCS : [bam]()
  * iMicroglia : [bam]()

### Gene annotation
* Gene annotation using ISOSEQ data, see [description]()
  * Primary haplotype annotation : [gene.gff.gz]()
  * Alternative haplotype annotation : [gene.gff.gz]()

### Variant calls
* heterozygosity site, see description
  * The heterozygosity site between primary and alternative haplotype : [hetsites.hetsites.fix.bed.gz]()
  * hapdiff result : [hapdiff.vcf.gz]()
  * 
    
### Liftover resources 
* 1:1 Liftover T2T-CHM13v2.0 <-> KOLF2.1Jv1.1, see description
  * KOLF2.1Jv1.1 primary <-> T2T-CHM13v2.0 : [chain]()
  * KOLF2.1Jv1.1 alternative <-> T2T-CHM13v2.0 : [chain]()
* 1:1 Liftover KOLF2.1Jv1.1 primary <-> alternative, see description
  * KOLF2.1Jv1.1 primary <-> KOLF2.1Jv1.1 alternative : [chain]()

## Sequencing data
* WGS
  * HiFi 
  * ONT
  * Illumina
* Transcriptome
  * ISOSEQ (PacBio) 
  * Nanopore Direct RNA (ONT)
* HiC
  * iPCS
  * iMicroglia

## Contact 
Please raise issues on this Github repository concerning this dataset.

## Data reuse and license

## Citation

## History
```
* v1.1 : DATE. V1.1 release.
```
