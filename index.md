---
layout: home
author_profile: true
classes: wide smaller-font
---

{% capture custom_content %}
## About Me
<div style="text-align: justify; font-size: 20px;">
Bioinformatics-oriented Biology student (CS minor) at the University of Tehran, focused on <strong>bioinformatics, Drug Discovery, genomics, and systems biology</strong>. I worked on RNA-seq/WGCNA, sequence-based ML (binding-site prediction), and cancer genomics—aiming to translate computational signals into actionable biomarkers and drug discovery leads.
</div>


{: .small}

---
## Research Interests

1. **Drug Discovery**
   - Data-driven target/biomarker discovery, Binding-site prediction from sequence, Virtual screening and molecular design

2. **Genomics**
   - RNA-seq, Functional annotation, enrichment analysis, clinical–genomic integration, survival analysis

3. **Machine Learning**
   - Sequence-level models for proteins, Benchmarking & evaluation, Feature engineering for omics, Model interpretation


4. **Systems Biology**
   - Co-expression networks (WGCNA), Network visualization & analysis (Cytoscape), network-driven candidate prioritization


---
## Technical Skills
- **Programming:** Python, R, Bash, PostgreSQL, C++, LATEX
- **Bioinformatics:** RNA-Seq, Genome Assembly, Multiple Sequence Alignment (MSA), Pairwise/Local Alignments, Systems Biology (WGCNA), QSAR, Docking (AutoDock), MD Simulation (GROMACS
- **Machine Learning & AI:** PyTorch, scikit-learn, Transformers, WGCNA, dynamicTreeCut
- **Software Tools:** Open Babel, UCSF Chimera, Oligo7, GenoPro, SnapGene, Cytoscape, IGV, Endnote, Storyline, SPSS
- **Version Control:** Git, GitHub
- **Laboratory:** Standard PCR, PCR Primer Design, DNA Electrophoresis, Genomic DNA Extraction (Salting-out), Spectrophotometry, Nanodrop, Centrifugation, ELISA, Blood Smear Preparation, Aseptic Technique, Gram Staining, Streak Plate Method

{: .small}
{% endcapture %}

{{ custom_content | markdownify }}
 ---

## Selected Projects 

### Benchmarking Protein–Ligand Binding Site Prediction with Pseq2Sites
Bachelor thesis project benchmarking deep learning approaches (CNN with attention mechanisms) for sequence-based prediction
 of protein–ligand binding sites. Focused on large-scale preprocessing of scPDB and PDBbind datasets, implementation of 
ProtTrans embeddings, and comparative evaluation to highlight strengths, challenges, and opportunities for improving drug 
discovery pipelines. [GitHub Link](https://github.com/AsalRb/Benchmarking_Protein-Ligand_Binding_Site_Prediction_with_Pseq2Sites)


### Exploring Relationships Between Ion Channels and lncRNAs in Gastric Cancer
Ongoing research project using TCGA-STAD RNA-seq data to investigate gene co-expression networks. Applied differential 
expression analysis (DESeq2), WGCNA, and survival modeling to identify lncRNA–ion channel modules correlated with clinical
 traits, aiming to uncover novel biomarkers and therapeutic targets. [GitHub Link](https://github.com/AsalRb/Exploring_Relationships_Between_Ion_Channels_and_lncRNAs_in_Gastric_Cancer)


### Read Mapping and Genome Assembly
Implemented a full NGS workflow on \textit{E. coli} short-read data, including quality control (FastQC), de novo assembly
 (SPAdes, Quast), and read mapping (BWA, SAMtools). Validated results by visualizing alignments in IGV and assessing 
concordance, mapping rates, and read depth, providing hands-on experience with genome assembly and evaluation. [GitHub Link](https://github.com/AsalRb/Read_Mapping_and_Genome_Assembly)


### Identification of Xylanase Genes
Designed and implemented a bioinformatics pipeline to identify thermostable xylanase genes from rumen metagenomic datasets.
 The analysis involved sequence similarity searches (BLAST+), clustering at 97\% identity with CD-HIT to generate 
non-redundant representatives, and conserved region modeling (HMM-based filtering) to refine candidates. Produced a 
curated set of high-confidence xylanase gene sequences. [GitHub Link](https://github.com/AsalRb/Identification_of_Xylanase_Genes_from_Rumen_Metagenome)

