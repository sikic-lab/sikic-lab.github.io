---
title: "Internship Positions"
date: 2025-12-02
categories:
tags:
---

We offer a variety of exciting projects for possible interns.  
You can find the list of possible internship projects below. <br />

<body>

<h2>Project A: From Events to Nucleotides: Improved Segmentation Leads to Accurate Lightweight Basecallers</h2>

Nanopore sequencing is a cutting-edge technology that enables real-time analysis of nucleic acids by measuring fluctuations in electrical current caused by the molecule's translocation through the nanopore. The output of the nanopore sequencing, a one-dimensional signal of electrical current measurements taken in the pore carries information on the corresponding nucleic acid sequence and additional information about the state of the sequenced sample.<br /><br />

The raw signal is converted into a nucleotide sequence through a process known as basecalling. Early basecallers, such as Scrappie, used an event-based approach in which the signal was first segmented into discrete units, or events, each representing the passage of a single nucleotide. These events were then translated into a nucleotide sequence. The segmentation relied on a rolling-window statistical method that, due to a low signal-to-noise ratio, often under- or over-segmented the signal, resulting in high basecalling error rates.<br /><br />

To overcome these limitations, modern basecallers no longer depend on explicit signal segmentation. Instead, they employ large-scale deep neural networks that process raw signals directly to produce accurate basecalls. While this approach has greatly improved accuracy, it has also increased computational complexity, recent “super-accurate” basecallers are based on Transformer architectures with roughly 80 million parameters.<br /><br />

Recent efforts in improving segmentation of nanopore signals, namely Campolina, has demonstrated significant gains in real-time signal processing quality. These advances raise the question of whether high-quality segmentation could also enhance event-based basecalling, potentially enabling a new class of lightweight yet accurate basecallers.<br /><br />

This project aims to explore the potential for developing a new deep learning-based basecalling framework that would leverage high-quality segmentation based on the Campolina architecture and output accurate basecalls while reducing computational requirements compared with current large-scale deep neural architectures.<br /><br />

Ultimately, this approach could revive and advance event-based basecalling, paving the way for the next generation of efficient, accurate basecallers, an essential component of nanopore sequencing technology.<br /><br />

<strong>Expected outcomes:</strong><br />
- Deep understanding of basecalling problem, existing architectures, and prominent approaches.  
- Hands-on experience in developing and evaluating a deep learning-based framework for event-based basecalling.  
- Skills in preprocessing genomic data, model design, basecalling evaluation and error interpretation in a genomics context.<br /><br />

</body>


<body>

<h2>Project B: Towards a Universal Protein–RNA Foundation Model: Generating Sequences and Understanding Functions, Structures, and Interactions (ProtRNA-FM)</h2>

Ribonucleic acid (RNA) plays a variety of crucial roles in fundamental biological processes, from gene regulation and catalysis to serving as structural scaffolds in complex cellular machineries. Recently, RNA has also emerged as a promising drug target, underscoring the need to advance our understanding of its structures, functions, and interactions. Over the years, sequencing technologies have generated vast amounts of RNA and protein sequence data, much of which remains unlabeled, yet likely encodes critical biological insights.<br /><br />

At the same time, proteins remain at the core of virtually all cellular processes, and their interactions with RNA are central to gene expression regulation, RNA modification, and other essential pathways. The capacity to model RNA and proteins jointly, and predict their interactions from sequences alone, remains a significant challenge in computational biology.<br /><br />

This project aims to develop a unified protein and RNA foundation model, ProtRNA-FM, capable of learning generalizable representations of RNA and protein sequences, predicting their properties, and modeling RNA–protein interactions. Leveraging recent advances in deep learning and Transformer-based architectures, the project will explore novel multi-modal modeling strategies to jointly embed RNA and protein sequences in a shared latent space. This will allow the model to understand sequence patterns relevant to RNA and protein functions, as well as capture features governing their interactions.<br /><br />

This project has the potential to contribute toward the development of next-generation foundation models in molecular biology, enabling a deeper understanding of RNA and proteins and opening new avenues for therapeutic discovery.<br /><br />

<strong>Training duration:</strong><br />
- 4 or 8 months<br /><br />

<strong>Training plan and objectives:</strong><br />

<strong>Literature Review</strong><br />
- Conduct a review of protein and RNA language models.  
- Study sequence-based RNA–protein interaction prediction methods.  
- Explore Transformer-based architectures for biological sequences (e.g., LLaDA).<br /><br />

<strong>Dataset Collection and Preparation</strong><br />
- Curate RNA data (RNAcentral).  
- Curate protein sequences (UniProt).  
- Collect RNA–protein interaction datasets.  
- Preprocess datasets for training.  
- Implement dataset tokenization and data loaders.<br /><br />

<strong>Model Development</strong><br />
- Integrate existing foundation models (RiNALMo, ESM2) into a unified protein–RNA foundation model.  
- Implement diffusion language modeling for RNA and protein sequences.  
- Begin with smaller models (~100M parameters).<br /><br />

<strong>Training and Optimization</strong><br />
- Train initial small-scale models.  
- Perform early evaluations:  
  - Intrinsic tasks: perplexity, masked token recovery.  
  - Extrinsic tasks: protein/RNA classification, protein/RNA function prediction.  
- Monitor cross-modality generalization.  
- Scale up to large joint model training.  
- Optimize hyperparameters for performance and efficiency.<br /><br />

<strong>Evaluation and Benchmarking</strong><br />
- Benchmark on RNA–protein interaction datasets.  
- Benchmark separately on RNA and protein structure/function datasets.  
- Compare against existing baselines (RiNALMo, ESM2).  
- Visualize and interpret attention maps and embeddings.  
- Evaluate RNA and protein sequence generation capabilities.<br /><br />

<strong>Reporting & Refinement</strong><br />
- Refine models and conduct robustness checks.  
- Draft technical report and/or manuscript.  
- Prepare presentations for lab and conference submissions.  
- Fully document code and pipelines.<br /><br />

</body>


<body>

<h2>Project C: Improving Deep Learning Architectures for HERRO Error Correction</h2>

HERRO is a computational method that uses deep learning and haplotype information to improve the accuracy of long-read sequencing data (Oxford Nanopore reads). By correcting common sequencing errors, HERRO strengthens the reliability of downstream tasks such as genome assembly. The project is an excellent opportunity to work at the intersection of genomics and machine learning, with a strong focus on practical impact.<br /><br />

As part of this internship, the student will:<br />
- Explore and evaluate alternative neural network architectures.  
- Benchmark models on key metrics: read-level error rates, runtime, memory usage, and generalization.  
- Perform detailed error analysis to identify which error types (e.g., homopolymer indels, substitutions, systematic biases) are most impacted.  
- Investigate strategies for model improvement, such as:  
  - Improved input representations and data augmentation.  
  - Regularization and training techniques.  
- Assess impact on downstream applications, especially genome assembly accuracy and contiguity.<br /><br />

<strong>Expected Outcomes</strong><br />
- Identification of promising architectures that reduce sequencing error rates.  
- Deeper understanding of error patterns and their relationship to model design.  
- Insights into how improved correction benefits genome assembly.<br /><br />

<strong>Learning Opportunities for the Intern</strong><br />
- Hands-on experience in applying deep learning to real genomic data.  
- Exposure to benchmarking pipelines and large-scale biological datasets.  
- Skills in model design, evaluation, and interpretation in a genomics context.<br /><br />

<strong>Requirements</strong><br />
- Familiarity with working in a terminal environment (bash).  
- Familiarity with Python.  
- Understanding of basic algorithms and data structures.  
- Preferably, basic knowledge of machine learning and data science.<br /><br />

</body>


<body>
<h2>Project D: Development of a Cancer Genome Foundation Model</h2>

Compared with healthy genomes, cancer genomes are qualitatively different:
they accumulate point mutations, copy-number shifts, structural
rearrangements, and epigenetic rewiring. Yet most existing genome
foundation models are trained on healthy or single-reference sequences, use a
four-letter DNA alphabet, and operate on short windows. Thus, such models
can miss long-range regulatory interactions and ignore methylation or
chromatin accessibility signals that are central in cancer. This leaves a gap: we
need models that read sequence and epigenome together, at scales large
enough to span domains and rearrangements, while retaining single-
nucleotide detail.<br /><br />

This project builds a genome–epigenome foundation model that “reads”
cancer DNA using a unified representation that captures base identity (A, C, G,
T) together with methylation (5mC, 5hmC) and chromatin-state signals (open,
closed) at single-nucleotide resolution, so it can learn how mutations and
epigenetic rewiring jointly drive disease. The student will train sequence
models that combine standard Transformers (strong local context and motif
learning) with state-of-the-art sub-quadratic long-sequence alternatives (e.g.,
Mamba, Hyena) to scale to chromosome-arm inputs while preserving single-
nucleotide detail. A multi-scale regimen will pair long-range training with
focused models on cancer-relevant regions (e.g., topologically associating
domains), enabling the model to link point mutations, indels, methylation
changes, accessibility marks, and structural breakpoints to regulatory
consequences. The result is a practical, cancer-specific foundation model
whose embeddings and variant scores flag disrupted enhancers/silencers,
differentially methylated regions, and recurrent rearrangements that
distinguish tumour types. <br /><br />

<strong> Training Duration </strong><br />
- 4 or 8 months
<strong>Training plan and objectives</strong><br />
- Literature review
  - Survey long-context Transformers and sub-quadratic sequence
models for genomics, study pros/cons, and context limits.
  - Explore state-of-the-art methods on methylation and accessibility
modelling, and their importance in cancer development.
- Dataset collection and preparation
  - Explore publicly available data (e.g., HG008 pancreatic cancer
sequencing datasets), familiarize yourself with different
sequencing technologies
  - Process methylation and chromatin accessibility data, map them
to the cancer genome assembly
  - Define promoter/distal regions and TADs
  - Implement the dataset tokenizer, define downstream tasks
- Model development
  - Implement a baseline short-window Transformer (masked-token /
next-token objectives)
  - Add long-context Transformer variants (sliding/sparse or
kernel/linear attention), explore sub-quadratic alternatives
(Mamba/Hyena) and diffusion language modelling.
  - Integrate interpretability (SHAP / Integrated Gradients; attention
summaries).
- Training and optimization
  - Train initial small-scale models
  - Curriculum learning from promoters (±2 kb), to TAD windows, to
chromosome-arm spans.
  - Hyper-parameter sweeps, mixed precision, gradient
checkpointing; early stopping by validation loss and calibration.
  - Ablation studies: DNA-only vs unified representation of DNA,
methylations, and chromatin accessibility.
- Evaluation and benchmarking
  - Evaluate against existing genome foundation models
  - Reporting & Refinement
  - Refine models and conduct robustness checks.
  - Draft technical report and/or manuscript.
  - Prepare presentations for lab and conference submissions.
  - Fully document code and pipelines.
<br /><br />


</body>

