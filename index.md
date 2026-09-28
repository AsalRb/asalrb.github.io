---
layout: home
author_profile: true
classes: wide smaller-font
---

{% capture custom_content %}
## About Me
<div style="text-align: justify; font-size: 20px;">
Bioinformatics-oriented Biology graduate with a Computer Science minor from the University of Tehran, with interests in <strong>computational genomics, transcriptomics, systems biology, and machine learning</strong>. My research experience spans RNA-seq and gene co-expression network analysis, deep learning-based protein-ligand binding-site prediction, and structure-based drug discovery. I am particularly interested in applying computational and data-driven approaches to genomics, gene regulation, and biologically and clinically relevant research questions.
</div>


{: .small}

---
## Research Interests

1. **Genomics**
   - Genome assembly, read mapping, sequence analysis, functional annotation, and comparative genomics

2. **Transcriptomics & Systems Biology**
   - RNA-seq analysis, gene co-expression networks (WGCNA), gene regulation, non-coding RNA, and network-based candidate prioritization

3. **Machine Learning for Biological Data**
   - Protein sequence modeling, representation learning, model benchmarking and evaluation, and high-dimensional biological data analysis

4. **Computational Drug Discovery**
   - Protein-ligand binding-site prediction, molecular docking, virtual screening, and structure-based drug discovery

---
## Technical Skills

- **Bioinformatics:** RNA-seq Analysis, Systems Biology (WGCNA), Sequence Alignment (Clustal Omega, BLAST+), Reference Mapping (BWA, SAMtools), Genome Assembly (SPAdes, Quast)
- **Programming:** Python, R, Bash, SQL, C++, LaTeX
- **Machine Learning:** PyTorch, Scikit-Learn, TensorFlow/Keras, Transformers
- **Molecular Modeling:** QSAR, Molecular Docking (AutoDock, Schrödinger Maestro), Molecular Dynamics (GROMACS)
- **Software Tools:** Cytoscape, IGV, UCSF Chimera, Open Babel, SnapGene, Oligo7, GenoPro, SPSS, EndNote
- **Version Control:** Git, GitHub
- **Laboratory:** PCR and Primer Design, DNA Electrophoresis, Genomic DNA Extraction (Salting-out), Spectrophotometry, Nanodrop, Centrifugation, Blood Smear Preparation, ELISA, Aseptic Technique

{: .small}
{% endcapture %}

{{ custom_content | markdownify }}
 ---

## Selected Projects 

### Benchmarking Protein-Ligand Binding Site Prediction with Pseq2Sites
Bachelor thesis project benchmarking a CNN + attention model for sequence-based protein-ligand binding-site prediction. Focused on preprocessing scPDB and PDBbind datasets, implementation of ProtTrans embeddings, and model evaluation to identify limitations and potential methodological improvements. [GitHub Link](https://github.com/AsalRb/Benchmarking_Protein-Ligand_Binding_Site_Prediction_with_Pseq2Sites)


### Exploring Relationships Between Ion Channels and lncRNAs in Gastric Cancer
Ongoing research project using TCGA-STAD RNA-seq data to investigate gene co-expression networks. Applied differential expression analysis (DESeq2), WGCNA, and survival analysis to identify lncRNA-ion channel modules associated with clinical traits and prioritize candidate genes for further investigation. [GitHub Link](https://github.com/AsalRb/Exploring_Relationships_Between_Ion_Channels_and_lncRNAs_in_Gastric_Cancer)


### Read Mapping and Genome Assembly
Implemented a full NGS workflow on E. coli short-read data, including quality control (FastQC), de novo assembly (SPAdes, Quast), and read mapping (BWA, SAMtools). Validated results by visualizing alignments in IGV and assessing concordance, mapping rates, and read depth, providing hands-on experience with genome assembly and evaluation. [GitHub Link](https://github.com/AsalRb/Read_Mapping_and_Genome_Assembly)


### Identification of Xylanase Genes
Designed and implemented a bioinformatics pipeline to identify thermostable xylanase genes from rumen metagenomic datasets. The workflow included sequence similarity searches (BLAST+), clustering at 97% identity with CD-HIT to generate non-redundant representatives, multiple sequence alignment (Clustal Omega) to detect conserved motifs, and HMM-based filtering to refine candidates. Produced a curated set of high-confidence xylanase gene sequences. [GitHub Link](https://github.com/AsalRb/Identification_of_Xylanase_Genes_from_Rumen_Metagenome)
