<h1 align="center">Computational Biology</h1>

<p align="center">
  <em>Where machine learning meets biological data.</em>
</p>

<p align="center">
  <a href="../">← Back to BenchToModel</a>
</p>

## 👋 About This Section

This is where the ML and DL foundations from the other sections get applied to real biological questions.

The focus here is on learning notes and small experiments — understanding how biological data differs from typical ML datasets, and what that changes about preprocessing, model choice, and interpretation. Fully developed projects live in their own repositories (linked below).

## 🧬 Topics Covered

- **Biological data types** — sequences, expression matrices, images, and their quirks
- **Genomics & Transcriptomics** — working with sequencing and expression data
- **Bioimage Analysis** — cells, tissues, and phenotype classification
- **Microbiome Analysis** — compositional data and its challenges
- **Explainable AI in Biology** — why interpretability matters more when the output informs a hypothesis
- **Reproducibility** — pipelines, environments, and version control for biological analyses

## ⚠️ What Makes Biological Data Different

Notes on the recurring gotchas: high dimensionality with few samples, batch effects, class imbalance, compositional constraints, and the fact that a good AUC doesn't automatically mean a biologically meaningful model.

## 🛠️ Tools & Libraries

`Python` · `R` · `Biopython` · `scanpy` · `scikit-learn` · `PyTorch` · `Bioconductor`

## 🔗 Related Projects

Standalone repositories where these methods are applied in full:

- [Bioimage_ML_Classification](https://github.com/nkirtipal/Bioimage_ML_Classification) — CNN-based bioimage classification with Explainable AI
- [MultiModal_RNAseq_Workflow](https://github.com/nkirtipal/MultiModal_RNAseq_Workflow) — bulk and single-cell RNA-seq integration
- [NikSeqRecur](https://github.com/nkirtipal/NikSeqRecur) — DNA sequence analysis for repeat detection
- [NikOmicsDogma](https://github.com/nkirtipal/NikOmicsDogma) — multiomics relationships and systems biology visualization

## 🔗 Related Sections

- 📁 [Machine_Learning](../Machine_Learning/) — foundations and classical algorithms
- 📁 [Deep_Learning](../Deep_Learning/) — neural networks and modern architectures
