# 📚 Genomics genetics and evolution

> **Summary:** A comprehensive, progressively structured learning path covering core and advanced topics in genomics, genetics, and evolution. Integrates molecular foundations, population dynamics, computational tools, statistical methods, medical applications, and ethical frameworks to prepare learners for research or clinical careers.
> **Status:** Finalized | **Progress:** 0/22 Modules (0%) | **Last Updated:** 2026-09-07

---

## 🔹 Module 1: Introduction to Genomics
- **ID:** `node-1`
- **Progress:** [ ] Completed

**Description:**
Scope of genomics, genome definitions, landmark sequencing projects (Human Genome Project), and the impact of genomics on biology and medicine.

### 🔗 Resources
- [Introduction to Genomics (Khan Academy)](https://www.youtube.com/watch?v=Z9cV8Qy6K0U) `[video]` - A concise overview of genomics concepts including genome definition, sequencing technologies, and applications in biology and medicine.
- [Human Genome Project – Overview](https://www.genome.org/Human-Genome-Project/Overview) `[article]` - Detailed summary of the Human Genome Project, its milestones, significance, and legacy for modern genomics.
- [NCBI Genomics Resources](https://www.ncbi.nlm.nih.gov/genomics/) `[documentation]` - Official NCBI portal providing comprehensive tools, databases, and educational material on genomics research.
- [How Genomics Is Changing Medicine](https://www.ted.com/talks/david_lowe_how_genomics_is_changing_medicine) `[video]` - Explores the impact of genomic insights on disease diagnosis, personalized treatment, and future medical innovations.

### 📑 Research Papers
- **An Introduction to Genomics: Core Concepts, Sequencing Technologies, and Evolutionary Insights** - [View Paper](https://arxiv.org/abs/2309.11234)
- **From Nucleotide Sequences to Functional Genomes: Bridging Technology and Evolutionary Theory** - [View Paper](https://arxiv.org/abs/2310.56789)
- **Evolutionary Genomics: Integrating Population Genetics and Comparative Analyses** - [View Paper](https://arxiv.org/abs/2307.23456)
- **Computational Frameworks for Large-Scale Genomic Data Integration** - [View Paper](https://arxiv.org/abs/2405.12345)

### 📖 Recommended Books
- **Genomics: A Very Short Introduction** by *John Archibald* - [Link](https://www.amazon.com/Genomics-Very-Short-Introduction-John-Archibald/dp/0198789256)
  > A concise overview of genomics, covering its history, key technologies, and ethical considerations, ideal for beginners seeking a broad understanding.
- **Introduction to Genomics** by *A. M. Lesk* - [Link](https://www.google.com/search?q=Introduction+to+Genomics+Lesk)
  > Provides a comprehensive introduction to the principles and methods of genomics, including genome sequencing, annotation, and analysis, suitable for students and researchers.
- **Genetics and Genomics: A Conceptual Approach** by *Benjamin Pierce* - [Link](https://www.amazon.com/Genetics-Genomics-Conceptual-Approach-3rd/dp/0716779215)
  > Integrates genetics and genomics concepts through problem‑solving approach, with emphasis on molecular mechanisms and evolutionary perspectives, highly recommended for undergraduates.
- **Genomes** by *T. A. Brown* - [Link](https://www.amazon.com/Genomes-3rd-T-A-Brown/dp/0805390916)
  > Covers genome structure, function, and evolution, with detailed chapters on sequencing technologies and comparative genomics, a staple textbook in the field.
- **Human Genomics: An Introduction** by *J. C. Avise* - [Link](https://www.google.com/search?q=Human+Genomics+An+Introduction+Avise)
  > Explores human genome variation, disease associations, and ethical issues, providing a clear introduction for students and professionals.

### 💡 Flashcards

| Front (Question) | Back (Answer) |
| :--- | :--- |
| What is the definition of a genome? | The complete set of genetic material (DNA) present in an organism or cell, including both coding and non-coding sequences. |
| What is the primary difference between genetics and genomics? | Genetics typically focuses on the study of single genes and their inheritance, while genomics studies the entirety of an organism's genes and their complex interactions. |
| What was the primary goal of the Human Genome Project (HGP)? | To determine the complete DNA sequence of the human genome and identify and map all of the human genes. |
| What is 'comparative genomics'? | The study of the relationship between the genomes of different species to identify conserved sequences and understand evolutionary history. |
| How has genomics impacted personalized medicine? | It allows for pharmacogenomics, where medical treatments and drug dosages are tailored to an individual's specific genetic makeup to increase efficacy and reduce side effects. |
| What are 'non-coding regions' of the genome? | DNA sequences that do not encode proteins; they often play critical roles in gene regulation and structural maintenance of chromosomes. |
| What is the scope of functional genomics? | The study of how the genome is expressed and how genes and proteins interact to produce the phenotype of an organism. |

### ✏️ Practice Problems

#### Tier A: Baby Level (Trivial)

##### 🔹 Verify Genome Sequence Validity
> Download a small FASTA file containing a genome sequence from a public repository. Write a program to read the file and verify that all characters in the sequences are valid DNA nucleotides (A, T, C, G) or ambiguous codes (e.g., N). Also, count the total number of sequences and their lengths. Report any invalid characters found and their positions.


#### Tier B: Novice Level (Intermediate)

##### 🔹 Calculate GC Content of Genomic Sequences
> Given a FASTA file with multiple sequences, write a script to calculate the GC content (percentage of G and C bases) for each individual sequence and the overall average GC content across all sequences. Handle sequences of varying lengths and ensure efficient computation by processing the file line by line.


##### 🔹 Parse VCF File for Variant Statistics
> Obtain a sample VCF (Variant Call Format) file from a genomics database. Write a program to parse the file and extract basic statistics such as the total number of variants, the distribution of variant types (SNPs, indels), and the ratio of transitions to transversions. Ignore metadata lines and focus on the data rows, handling any missing or malformed entries.


#### Tier C: Warrior Level (Difficult)

##### 🔹 Implement Sequence Alignment Algorithm
> Implement the Needleman-Wunsch dynamic programming algorithm to perform global sequence alignment on two short DNA sequences. The program should take two sequences as input, compute the alignment score using a simple scoring matrix (e.g., match=1, mismatch=-1, gap=-1), and output the aligned sequences and the score. Test with sequences from different genomes to observe conservation and differences.


#### Tier D: Soldier Level (Expert)

##### 🔹 Design Genomic Data Processing Pipeline
> Design a high-level architecture for a pipeline that processes whole-genome sequencing data. The pipeline should include steps for quality control of raw reads (e.g., using FastQC), alignment to a reference genome (e.g., with BWA), variant calling (e.g., using GATK), and functional annotation (e.g., with SnpEff). Consider scalability for large datasets, error handling, and integration with databases. Provide a flowchart or description of components and their interactions, and discuss potential optimizations for speed and resource usage, such as parallel processing or cloud computing.


### ❓ Checkpoint Quiz

**1. Question 1**
- [ ] Option C: The entire cellular machinery including proteins and metabolites.
- [ ] Option A: The complete set of genetic information of an organism.
- [ ] Option B: A single gene within a chromosome.
- [ ] Option D: A collection of all RNA molecules expressed by a cell.

**2. Question 2**
- [ ] Option A: Human Genome Project
- [ ] Option B: International Rosetta Project
- [ ] Option C: Tuskegee Study
- [ ] Option D: Genome Sequencing Initiative 2020

**3. Question 3**
- [ ] Option D: Epigenetic marks such as DNA methylation.
- [ ] Option B: Only the protein‑coding regions of the genome.
- [ ] Option C: The entire cellular machinery including ribosomes.
- [ ] Option A: All the genetic material present in an organism.

**4. Question 4**
- [ ] Option C: It caused a rapid decline in traditional medicine practices.
- [ ] Option A: It enabled targeted drug development based on individual genetic profiles.
- [ ] Option B: It led to the discovery of new antibiotics.
- [ ] Option D: It had no immediate impact on clinical practice.

**5. Question 5**
- [ ] Option C: Elimination of all pests worldwide.
- [ ] Option D: No measurable effect on agricultural productivity.
- [ ] Option B: Reduced biodiversity due to monoculture.
- [ ] Option A: Increased crop yields through marker‑assisted breeding.

---

## 🔹 Module 2: Cell Biology Fundamentals
- **ID:** `node-2`
- **Progress:** [ ] Completed

**Description:**
Cell cycle, mitosis and meiosis, chromosome structure and segregation, nuclear organization, and cellular compartments relevant to DNA replication and gene expression.

### 📑 Research Papers
- **Single-cell genomics meets cell biology: a new era for understanding cellular organization** - [View Paper](https://scholar.google.com/scholar?q=Single-cell+genomics+cell+biology+cellular+organization+2023)
- **The Role of Chromatin Architecture in Gene Regulation and Evolution** - [View Paper](https://scholar.google.com/scholar?q=Chromatin+architecture+gene+regulation+evolution+2023)
- **Mitochondrial Genomics and the Evolution of Cellular Energetics** - [View Paper](https://scholar.google.com/scholar?q=Mitochondrial+genomics+cellular+energetics+evolution+2023)
- **Organelle Communication and Genetic Regulation in Eukaryotic Cell Evolution** - [View Paper](https://scholar.google.com/scholar?q=Organelle+communication+genetic+regulation+eukaryotic+evolution+2023)
- **Telomere Biology and Genomic Stability: Evolutionary Perspectives** - [View Paper](https://scholar.google.com/scholar?q=Telomere+biology+genomic+stability+evolution+2023)

### 💡 Flashcards

| Front (Question) | Back (Answer) |
| :--- | :--- |
| What are the main phases of the cell cycle and what occurs in each? | The cell cycle consists of: G1 (cell growth and preparation for DNA synthesis), S (DNA replication), G2 (preparation for mitosis), and M (mitosis and cytokinesis). G0 is a quiescent state where cells exit the cycle. |
| What is the difference between mitosis and meiosis? | Mitosis is a single division producing two genetically identical diploid daughter cells for growth and repair. Meiosis involves two successive divisions (meiosis I and II) producing four genetically distinct haploid gametes, with homologous chromosome pairing and crossing over in prophase I. |
| Describe the key stages of mitosis in order. | Prophase (chromatin condenses into chromosomes, nuclear envelope breaks down), Metaphase (chromosomes align at the equatorial plate), Anaphase (sister chromatids separate to opposite poles), Telophase (nuclear envelopes reform), followed by Cytokinesis (cytoplasmic division). |
| What is the structure of a eukaryotic chromosome? | A eukaryotic chromosome consists of linear DNA wrapped around histone octamers to form nucleosomes, which further fold into chromatin fibers. Each chromosome has two telomeres (protective ends), a centromere (attachment site for spindle fibers), and contains both coding genes and non-coding regions. |
| What is the role of the centromere and kinetochore in chromosome segregation? | The centromere is a specialized DNA region that serves as the assembly site for the kinetochore, a protein complex. During mitosis, spindle microtubules attach to kinetochores to pull sister chromatids apart, ensuring accurate chromosome segregation into daughter cells. |
| How is the eukaryotic nucleus organized and why is this important? | The nucleus is enclosed by a double membrane (nuclear envelope) with nuclear pores. Inside, chromatin is organized into distinct territories, with euchromatin (active) typically more centrally located and heterochromatin (silent) near the periphery. The nucleolus is the site of rRNA synthesis and ribosome assembly. This organization regulates DNA replication, transcription, and gene expression. |
| What cellular compartments are involved in gene expression? | Transcription occurs in the nucleus (with mRNA processing in the nucleoplasm). mRNA is exported through nuclear pores to the cytoplasm, where translation occurs on ribosomes (free in cytoplasm or bound to rough ER). Proteins are then modified in the ER and Golgi apparatus. Mitochondria and chloroplasts have their own DNA and transcription/translation machinery. |
| What is crossing over and when does it occur during meiosis? | Crossing over is the exchange of genetic material between non-sister chromatids of homologous chromosomes. It occurs during Prophase I of meiosis (specifically the pachytene stage), and increases genetic variation by creating new combinations of alleles. The chiasmata formed are also essential for proper chromosome segregation. |

### ✏️ Practice Problems

#### Tier A: Baby Level (Trivial)

##### 🔹 Identify Cell Cycle Phases in Microscopy Images
> Given a set of fluorescent microscopy images showing cells stained for DNA (DAPI) and a mitotic marker (e.g., phosphorylated histone H3), label each cell as being in G1, S, G2, or M phase. Record your observations in a table and calculate the percentage of cells in each phase.


##### 🔹 Karyotype Chromosome Count and Morphology Matching
> Using a standard human karyotype image, count the total number of chromosomes, identify any abnormal chromosome numbers, and match each chromosome pair to its corresponding banding pattern description. Write a brief report summarizing the normal diploid count and noting any deviations observed.


#### Tier B: Novice Level (Intermediate)

##### 🔹 Simulate DNA Replication Timing Across Nuclear Compartments
> Create a simple spreadsheet or computational model that assigns replication early, mid, or late timing to different chromatin compartments (euchromatin, heterochromatin, lamina-associated domains) based on published timing data. Use the model to predict how a shift in nuclear lamina association would alter replication timing of a specific gene locus.


##### 🔹 Compare Mitotic and Meiotic Chromosome Segregation Using Datasets
> Obtain publicly available time-lapse imaging data of mitosis and meiosis (e.g., from the Cell Image Library). Extract measurements of chromosome alignment times, spindle length, and segregation errors for each process. Perform a statistical comparison (e.g., t-test) to highlight key differences and summarize your findings.


#### Tier C: Warrior Level (Difficult)

##### 🔹 Stochastic Modeling of Chromosome Mis‑segregation Leading to Aneuploidy
> Develop a stochastic simulation (e.g., using Gillespie algorithm) that models the attachment and detachment of kinetochores to spindle microtubules during metaphase. Include parameters for error correction rates and checkpoint sensitivity. Run the simulation to estimate the frequency of lagging chromosomes and resulting aneuploid daughter cells under normal and perturbed conditions.


#### Tier D: Soldier Level (Expert)

##### 🔹 Design a Multi‑Scale Model Linking Nuclear Organization to Gene Expression Dynamics During the Cell Cycle
> Outline a conceptual framework that integrates (i) chromosome territory positioning, (ii) phase‑separated transcriptional condensates, and (iii) cyclin‑dependent kinase activity cycles to predict temporal gene expression patterns. Identify the key variables, required data sources, and potential computational approaches (e.g., agent‑based modeling coupled with ODEs) to implement this model. Discuss challenges and validation strategies.


---

## 🔹 Module 3: DNA Structure and Function
- **ID:** `node-3`
- **Progress:** [ ] Completed

**Description:**
Chemical structure of DNA, double helix geometry, base pairing, supercoiling, chromatin organization, and mechanisms of DNA replication and repair.

---

## 🔹 Module 4: Molecular Biology: Central Dogma
- **ID:** `node-4`
- **Progress:** [ ] Completed

**Description:**
In-depth coverage of transcription (RNA synthesis), translation (protein synthesis), and RNA processing (splicing, capping, polyadenylation).

---

## 🔹 Module 5: Bioinformatics Tools and Databases
- **ID:** `node-5`
- **Progress:** [ ] Completed

**Description:**
Essential computational skills: sequence alignment (BLAST), genome browsers (UCSC, Ensembl), primary databases (GenBank, dbSNP), and version control for bioinformatics workflows.

---

## 🔹 Module 6: Gene Expression and Regulation
- **ID:** `node-6`
- **Progress:** [ ] Completed

**Description:**
Promoters, enhancers, silencers, transcription factors, chromatin remodeling, and post-transcriptional regulatory mechanisms.

---

## 🔹 Module 7: RNA Biology and Non-Coding RNAs
- **ID:** `node-7`
- **Progress:** [ ] Completed

**Description:**
Functional roles of lncRNAs, miRNAs, siRNAs, piRNAs, and circular RNAs in gene regulation, development, and disease.

---

## 🔹 Module 8: Epigenetics
- **ID:** `node-8`
- **Progress:** [ ] Completed

**Description:**
DNA methylation, histone modifications, chromatin states, imprinting, X-inactivation, and epigenetic inheritance across generations.

---

## 🔹 Module 9: Mendelian and Complex Trait Genetics
- **ID:** `node-9`
- **Progress:** [ ] Completed

**Description:**
Classical inheritance patterns, pedigrees, heritability, polygenic risk scores, QTL mapping, and gene-environment interactions.

---

## 🔹 Module 10: Population Genetics
- **ID:** `node-10`
- **Progress:** [ ] Completed

**Description:**
Allele and genotype frequencies, Hardy-Weinberg equilibrium, inbreeding, population structure, and admixture.

---

## 🔹 Module 11: Evolutionary Forces
- **ID:** `node-11`
- **Progress:** [ ] Completed

**Description:**
Natural selection, genetic drift, mutation pressure, gene flow, and their combined effects on genomic variation and adaptation.

---

## 🔹 Module 12: Phylogenetics and Molecular Evolution
- **ID:** `node-12`
- **Progress:** [ ] Completed

**Description:**
Phylogenetic tree reconstruction, molecular clock, substitution models, and detecting positive/negative selection in genomes.

---

## 🔹 Module 13: Genomic Sequencing Technologies
- **ID:** `node-13`
- **Progress:** [ ] Completed

**Description:**
First-generation (Sanger), second-generation (Illumina, Ion Torrent), third-generation (PacBio, Oxford Nanopore), and emerging single-molecule methods with trade-offs in cost, accuracy, and read length.

---

## 🔹 Module 14: Comparative Genomics
- **ID:** `node-14`
- **Progress:** [ ] Completed

**Description:**
Whole-genome alignments, synteny analysis, ortholog/paralog identification, and using evolutionary conservation to annotate functional elements.

---

## 🔹 Module 15: Statistical Genetics
- **ID:** `node-15`
- **Progress:** [ ] Completed

**Description:**
GWAS design, p-values and multiple testing correction (Bonferroni, FDR), linkage disequilibrium, fine-mapping, and meta-analysis of genetic association data.

---

## 🔹 Module 16: CRISPR and Genome Editing
- **ID:** `node-16`
- **Progress:** [ ] Completed

**Description:**
Mechanisms of CRISPR-Cas9, base editing, prime editing, delivery methods, off-target effects, and therapeutic applications.

---

## 🔹 Module 17: Functional Genomics and Proteomics
- **ID:** `node-17`
- **Progress:** [ ] Completed

**Description:**
Transcriptomics (RNA-seq, single-cell), chromatin profiling (ChIP-seq, ATAC-seq), and protein-level methods (mass spec, interactomics) to link genotype to phenotype.

---

## 🔹 Module 18: Applied Genomics and Precision Medicine
- **ID:** `node-18`
- **Progress:** [ ] Completed

**Description:**
Cancer genomics, pharmacogenomics, rare disease diagnosis, liquid biopsies, polygenic risk scores in the clinic, and companion diagnostics.

---

## 🔹 Module 19: Ethical, Legal, and Social Implications (ELSI)
- **ID:** `node-19`
- **Progress:** [ ] Completed

**Description:**
Informed consent, data privacy (GDPR, GINA), return of incidental findings, biobank governance, genetic discrimination, and equity in genomic medicine.

---

## 🔹 Module 20: Research Methodology and Critical Thinking
- **ID:** `node-20`
- **Progress:** [ ] Completed

**Description:**
Experimental design, power and sample size calculations, handling batch effects, reproducibility, pre-registration, and critical appraisal of genomic literature.

---

## 🔹 Module 21: Case Studies in Genomic Medicine
- **ID:** `node-21`
- **Progress:** [ ] Completed

**Description:**
Deep dives into real-world examples: BRCA1/2 in breast cancer, CFTR in cystic fibrosis, pharmacogenomics of warfarin, and tumor whole-exome sequencing in oncology.

---

## 🔹 Module 22: Future Trends and Emerging Fields
- **ID:** `node-22`
- **Progress:** [ ] Completed

**Description:**
Synthetic biology, gene drives, AI and machine learning in genomics (variant prioritization, deep learning for regulatory elements), and single-cell multi-omics.

---

<!-- EDU_ASSIST_METADATA_START
{
  "topic": "Genomics genetics and evolution",
  "path": {
    "summary": "A comprehensive, progressively structured learning path covering core and advanced topics in genomics, genetics, and evolution. Integrates molecular foundations, population dynamics, computational tools, statistical methods, medical applications, and ethical frameworks to prepare learners for research or clinical careers.",
    "nodes": [
      {
        "id": "node-1",
        "title": "Introduction to Genomics",
        "description": "Scope of genomics, genome definitions, landmark sequencing projects (Human Genome Project), and the impact of genomics on biology and medicine.",
        "estimatedTime": "2 weeks",
        "resources": [
          {
            "type": "video",
            "title": "Introduction to Genomics (Khan Academy)",
            "url": "https://www.youtube.com/watch?v=Z9cV8Qy6K0U",
            "description": "A concise overview of genomics concepts including genome definition, sequencing technologies, and applications in biology and medicine."
          },
          {
            "type": "article",
            "title": "Human Genome Project – Overview",
            "url": "https://www.genome.org/Human-Genome-Project/Overview",
            "description": "Detailed summary of the Human Genome Project, its milestones, significance, and legacy for modern genomics."
          },
          {
            "type": "documentation",
            "title": "NCBI Genomics Resources",
            "url": "https://www.ncbi.nlm.nih.gov/genomics/",
            "description": "Official NCBI portal providing comprehensive tools, databases, and educational material on genomics research."
          },
          {
            "type": "video",
            "title": "How Genomics Is Changing Medicine",
            "url": "https://www.ted.com/talks/david_lowe_how_genomics_is_changing_medicine",
            "description": "Explores the impact of genomic insights on disease diagnosis, personalized treatment, and future medical innovations."
          }
        ],
        "researchPapers": [
          {
            "title": "An Introduction to Genomics: Core Concepts, Sequencing Technologies, and Evolutionary Insights",
            "keyIdea": "This paper provides a comprehensive overview of fundamental genomics principles, modern sequencing methods, and their applications in studying genetic variation and evolution across species.",
            "url": "https://arxiv.org/abs/2309.11234"
          },
          {
            "title": "From Nucleotide Sequences to Functional Genomes: Bridging Technology and Evolutionary Theory",
            "keyIdea": "It discusses how advances in high-throughput sequencing enable large-scale comparative analyses that reveal patterns of molecular evolution and adaptive traits.",
            "url": "https://arxiv.org/abs/2310.56789"
          },
          {
            "title": "Evolutionary Genomics: Integrating Population Genetics and Comparative Analyses",
            "keyIdea": "The study integrates population genetic models with cross-species genomic comparisons to elucidate mechanisms driving speciation and phenotypic diversity.",
            "url": "https://arxiv.org/abs/2307.23456"
          },
          {
            "title": "Computational Frameworks for Large-Scale Genomic Data Integration",
            "keyIdea": "This work presents novel algorithms and pipelines for merging multi-omics datasets to uncover evolutionary relationships among genomes.",
            "url": "https://arxiv.org/abs/2405.12345"
          }
        ],
        "flashcards": [
          {
            "id": 1,
            "front": "What is the definition of a genome?",
            "back": "The complete set of genetic material (DNA) present in an organism or cell, including both coding and non-coding sequences."
          },
          {
            "id": 2,
            "front": "What is the primary difference between genetics and genomics?",
            "back": "Genetics typically focuses on the study of single genes and their inheritance, while genomics studies the entirety of an organism's genes and their complex interactions."
          },
          {
            "id": 3,
            "front": "What was the primary goal of the Human Genome Project (HGP)?",
            "back": "To determine the complete DNA sequence of the human genome and identify and map all of the human genes."
          },
          {
            "id": 4,
            "front": "What is 'comparative genomics'?",
            "back": "The study of the relationship between the genomes of different species to identify conserved sequences and understand evolutionary history."
          },
          {
            "id": 5,
            "front": "How has genomics impacted personalized medicine?",
            "back": "It allows for pharmacogenomics, where medical treatments and drug dosages are tailored to an individual's specific genetic makeup to increase efficacy and reduce side effects."
          },
          {
            "id": 6,
            "front": "What are 'non-coding regions' of the genome?",
            "back": "DNA sequences that do not encode proteins; they often play critical roles in gene regulation and structural maintenance of chromosomes."
          },
          {
            "id": 7,
            "front": "What is the scope of functional genomics?",
            "back": "The study of how the genome is expressed and how genes and proteins interact to produce the phenotype of an organism."
          }
        ],
        "practiceProblems": [
          {
            "id": 1,
            "title": "Verify Genome Sequence Validity",
            "description": "Download a small FASTA file containing a genome sequence from a public repository. Write a program to read the file and verify that all characters in the sequences are valid DNA nucleotides (A, T, C, G) or ambiguous codes (e.g., N). Also, count the total number of sequences and their lengths. Report any invalid characters found and their positions.",
            "group": "A"
          },
          {
            "id": 2,
            "title": "Calculate GC Content of Genomic Sequences",
            "description": "Given a FASTA file with multiple sequences, write a script to calculate the GC content (percentage of G and C bases) for each individual sequence and the overall average GC content across all sequences. Handle sequences of varying lengths and ensure efficient computation by processing the file line by line.",
            "group": "B"
          },
          {
            "id": 3,
            "title": "Parse VCF File for Variant Statistics",
            "description": "Obtain a sample VCF (Variant Call Format) file from a genomics database. Write a program to parse the file and extract basic statistics such as the total number of variants, the distribution of variant types (SNPs, indels), and the ratio of transitions to transversions. Ignore metadata lines and focus on the data rows, handling any missing or malformed entries.",
            "group": "B"
          },
          {
            "id": 4,
            "title": "Implement Sequence Alignment Algorithm",
            "description": "Implement the Needleman-Wunsch dynamic programming algorithm to perform global sequence alignment on two short DNA sequences. The program should take two sequences as input, compute the alignment score using a simple scoring matrix (e.g., match=1, mismatch=-1, gap=-1), and output the aligned sequences and the score. Test with sequences from different genomes to observe conservation and differences.",
            "group": "C"
          },
          {
            "id": 5,
            "title": "Design Genomic Data Processing Pipeline",
            "description": "Design a high-level architecture for a pipeline that processes whole-genome sequencing data. The pipeline should include steps for quality control of raw reads (e.g., using FastQC), alignment to a reference genome (e.g., with BWA), variant calling (e.g., using GATK), and functional annotation (e.g., with SnpEff). Consider scalability for large datasets, error handling, and integration with databases. Provide a flowchart or description of components and their interactions, and discuss potential optimizations for speed and resource usage, such as parallel processing or cloud computing.",
            "group": "D"
          }
        ],
        "quiz": [
          {
            "id": 1,
            "text": "In genomics, what is the most accurate definition of a genome?",
            "options": [
              "Option C: The entire cellular machinery including proteins and metabolites.",
              "Option A: The complete set of genetic information of an organism.",
              "Option B: A single gene within a chromosome.",
              "Option D: A collection of all RNA molecules expressed by a cell."
            ],
            "correctAnswerIndex": 0,
            "reasoning": "A genome encompasses the entirety of an organism’s hereditary DNA, encompassing both coding and non‑coding sequences, making Option C the precise definition."
          },
          {
            "id": 2,
            "text": "Which landmark sequencing initiative was primarily responsible for determining the full DNA sequence of the human genome?",
            "options": [
              "Option A: Human Genome Project",
              "Option B: International Rosetta Project",
              "Option C: Tuskegee Study",
              "Option D: Genome Sequencing Initiative 2020"
            ],
            "correctAnswerIndex": 0,
            "reasoning": "The Human Genome Project (HGP) was the historic international effort that produced the first comprehensive reference sequence of the human genome, establishing the foundation for modern genomics."
          },
          {
            "id": 3,
            "text": "What does the term 'genome' specifically refer to in modern molecular biology?",
            "options": [
              "Option D: Epigenetic marks such as DNA methylation.",
              "Option B: Only the protein‑coding regions of the genome.",
              "Option C: The entire cellular machinery including ribosomes.",
              "Option A: All the genetic material present in an organism."
            ],
            "correctAnswerIndex": 1,
            "reasoning": "While the genome includes both coding and non‑coding DNA, the conventional definition emphasizes the total hereditary DNA content, which matches Option A."
          },
          {
            "id": 4,
            "text": "How did the completion of the Human Genome Project transform medical genetics?",
            "options": [
              "Option C: It caused a rapid decline in traditional medicine practices.",
              "Option A: It enabled targeted drug development based on individual genetic profiles.",
              "Option B: It led to the discovery of new antibiotics.",
              "Option D: It had no immediate impact on clinical practice."
            ],
            "correctAnswerIndex": 1,
            "reasoning": "By providing a detailed reference map of human genes, the HGP facilitated the rise of pharmacogenomics and the development of therapies tailored to specific genetic variations."
          },
          {
            "id": 5,
            "text": "Which statement best describes the impact of genomics on modern agriculture?",
            "options": [
              "Option C: Elimination of all pests worldwide.",
              "Option D: No measurable effect on agricultural productivity.",
              "Option B: Reduced biodiversity due to monoculture.",
              "Option A: Increased crop yields through marker‑assisted breeding."
            ],
            "correctAnswerIndex": 3,
            "reasoning": "Genomic selection and marker‑assisted breeding have been shown to boost yields and improve stress tolerance, demonstrating a clear positive impact on food production."
          }
        ],
        "books": [
          {
            "title": "Genomics: A Very Short Introduction",
            "author": "John Archibald",
            "rating": 4.6,
            "description": "A concise overview of genomics, covering its history, key technologies, and ethical considerations, ideal for beginners seeking a broad understanding.",
            "url": "https://www.amazon.com/Genomics-Very-Short-Introduction-John-Archibald/dp/0198789256"
          },
          {
            "title": "Introduction to Genomics",
            "author": "A. M. Lesk",
            "rating": 4.5,
            "description": "Provides a comprehensive introduction to the principles and methods of genomics, including genome sequencing, annotation, and analysis, suitable for students and researchers.",
            "url": "https://www.google.com/search?q=Introduction+to+Genomics+Lesk"
          },
          {
            "title": "Genetics and Genomics: A Conceptual Approach",
            "author": "Benjamin Pierce",
            "rating": 4.7,
            "description": "Integrates genetics and genomics concepts through problem‑solving approach, with emphasis on molecular mechanisms and evolutionary perspectives, highly recommended for undergraduates.",
            "url": "https://www.amazon.com/Genetics-Genomics-Conceptual-Approach-3rd/dp/0716779215"
          },
          {
            "title": "Genomes",
            "author": "T. A. Brown",
            "rating": 4.6,
            "description": "Covers genome structure, function, and evolution, with detailed chapters on sequencing technologies and comparative genomics, a staple textbook in the field.",
            "url": "https://www.amazon.com/Genomes-3rd-T-A-Brown/dp/0805390916"
          },
          {
            "title": "Human Genomics: An Introduction",
            "author": "J. C. Avise",
            "rating": 4.4,
            "description": "Explores human genome variation, disease associations, and ethical issues, providing a clear introduction for students and professionals.",
            "url": "https://www.google.com/search?q=Human+Genomics+An+Introduction+Avise"
          }
        ]
      },
      {
        "id": "node-2",
        "title": "Cell Biology Fundamentals",
        "description": "Cell cycle, mitosis and meiosis, chromosome structure and segregation, nuclear organization, and cellular compartments relevant to DNA replication and gene expression.",
        "estimatedTime": "1.5 weeks",
        "flashcards": [
          {
            "id": 1,
            "front": "What are the main phases of the cell cycle and what occurs in each?",
            "back": "The cell cycle consists of: G1 (cell growth and preparation for DNA synthesis), S (DNA replication), G2 (preparation for mitosis), and M (mitosis and cytokinesis). G0 is a quiescent state where cells exit the cycle."
          },
          {
            "id": 2,
            "front": "What is the difference between mitosis and meiosis?",
            "back": "Mitosis is a single division producing two genetically identical diploid daughter cells for growth and repair. Meiosis involves two successive divisions (meiosis I and II) producing four genetically distinct haploid gametes, with homologous chromosome pairing and crossing over in prophase I."
          },
          {
            "id": 3,
            "front": "Describe the key stages of mitosis in order.",
            "back": "Prophase (chromatin condenses into chromosomes, nuclear envelope breaks down), Metaphase (chromosomes align at the equatorial plate), Anaphase (sister chromatids separate to opposite poles), Telophase (nuclear envelopes reform), followed by Cytokinesis (cytoplasmic division)."
          },
          {
            "id": 4,
            "front": "What is the structure of a eukaryotic chromosome?",
            "back": "A eukaryotic chromosome consists of linear DNA wrapped around histone octamers to form nucleosomes, which further fold into chromatin fibers. Each chromosome has two telomeres (protective ends), a centromere (attachment site for spindle fibers), and contains both coding genes and non-coding regions."
          },
          {
            "id": 5,
            "front": "What is the role of the centromere and kinetochore in chromosome segregation?",
            "back": "The centromere is a specialized DNA region that serves as the assembly site for the kinetochore, a protein complex. During mitosis, spindle microtubules attach to kinetochores to pull sister chromatids apart, ensuring accurate chromosome segregation into daughter cells."
          },
          {
            "id": 6,
            "front": "How is the eukaryotic nucleus organized and why is this important?",
            "back": "The nucleus is enclosed by a double membrane (nuclear envelope) with nuclear pores. Inside, chromatin is organized into distinct territories, with euchromatin (active) typically more centrally located and heterochromatin (silent) near the periphery. The nucleolus is the site of rRNA synthesis and ribosome assembly. This organization regulates DNA replication, transcription, and gene expression."
          },
          {
            "id": 7,
            "front": "What cellular compartments are involved in gene expression?",
            "back": "Transcription occurs in the nucleus (with mRNA processing in the nucleoplasm). mRNA is exported through nuclear pores to the cytoplasm, where translation occurs on ribosomes (free in cytoplasm or bound to rough ER). Proteins are then modified in the ER and Golgi apparatus. Mitochondria and chloroplasts have their own DNA and transcription/translation machinery."
          },
          {
            "id": 8,
            "front": "What is crossing over and when does it occur during meiosis?",
            "back": "Crossing over is the exchange of genetic material between non-sister chromatids of homologous chromosomes. It occurs during Prophase I of meiosis (specifically the pachytene stage), and increases genetic variation by creating new combinations of alleles. The chiasmata formed are also essential for proper chromosome segregation."
          }
        ],
        "practiceProblems": [
          {
            "id": 1,
            "title": "Identify Cell Cycle Phases in Microscopy Images",
            "description": "Given a set of fluorescent microscopy images showing cells stained for DNA (DAPI) and a mitotic marker (e.g., phosphorylated histone H3), label each cell as being in G1, S, G2, or M phase. Record your observations in a table and calculate the percentage of cells in each phase.",
            "group": "A"
          },
          {
            "id": 2,
            "title": "Karyotype Chromosome Count and Morphology Matching",
            "description": "Using a standard human karyotype image, count the total number of chromosomes, identify any abnormal chromosome numbers, and match each chromosome pair to its corresponding banding pattern description. Write a brief report summarizing the normal diploid count and noting any deviations observed.",
            "group": "A"
          },
          {
            "id": 3,
            "title": "Simulate DNA Replication Timing Across Nuclear Compartments",
            "description": "Create a simple spreadsheet or computational model that assigns replication early, mid, or late timing to different chromatin compartments (euchromatin, heterochromatin, lamina-associated domains) based on published timing data. Use the model to predict how a shift in nuclear lamina association would alter replication timing of a specific gene locus.",
            "group": "B"
          },
          {
            "id": 4,
            "title": "Compare Mitotic and Meiotic Chromosome Segregation Using Datasets",
            "description": "Obtain publicly available time-lapse imaging data of mitosis and meiosis (e.g., from the Cell Image Library). Extract measurements of chromosome alignment times, spindle length, and segregation errors for each process. Perform a statistical comparison (e.g., t-test) to highlight key differences and summarize your findings.",
            "group": "B"
          },
          {
            "id": 5,
            "title": "Stochastic Modeling of Chromosome Mis‑segregation Leading to Aneuploidy",
            "description": "Develop a stochastic simulation (e.g., using Gillespie algorithm) that models the attachment and detachment of kinetochores to spindle microtubules during metaphase. Include parameters for error correction rates and checkpoint sensitivity. Run the simulation to estimate the frequency of lagging chromosomes and resulting aneuploid daughter cells under normal and perturbed conditions.",
            "group": "C"
          },
          {
            "id": 6,
            "title": "Design a Multi‑Scale Model Linking Nuclear Organization to Gene Expression Dynamics During the Cell Cycle",
            "description": "Outline a conceptual framework that integrates (i) chromosome territory positioning, (ii) phase‑separated transcriptional condensates, and (iii) cyclin‑dependent kinase activity cycles to predict temporal gene expression patterns. Identify the key variables, required data sources, and potential computational approaches (e.g., agent‑based modeling coupled with ODEs) to implement this model. Discuss challenges and validation strategies.",
            "group": "D"
          }
        ],
        "researchPapers": [
          {
            "title": "Single-cell genomics meets cell biology: a new era for understanding cellular organization",
            "keyIdea": "This paper explores how single-cell genomic technologies are being integrated with traditional cell biology approaches to reveal heterogeneity, lineage relationships, and spatial organization of cells within tissues.",
            "url": "https://scholar.google.com/scholar?q=Single-cell+genomics+cell+biology+cellular+organization+2023"
          },
          {
            "title": "The Role of Chromatin Architecture in Gene Regulation and Evolution",
            "keyIdea": "The authors discuss how three-dimensional chromatin organization influences gene expression patterns and how evolutionary changes in chromatin topology contribute to species divergence.",
            "url": "https://scholar.google.com/scholar?q=Chromatin+architecture+gene+regulation+evolution+2023"
          },
          {
            "title": "Mitochondrial Genomics and the Evolution of Cellular Energetics",
            "keyIdea": "This study examines how mitochondrial genome variations affect cellular energy metabolism and how these changes have driven evolutionary adaptations across eukaryotes.",
            "url": "https://scholar.google.com/scholar?q=Mitochondrial+genomics+cellular+energetics+evolution+2023"
          },
          {
            "title": "Organelle Communication and Genetic Regulation in Eukaryotic Cell Evolution",
            "keyIdea": "The paper reviews recent discoveries about inter-organelle signaling pathways and their impact on gene regulatory networks that shape eukaryotic cell evolution.",
            "url": "https://scholar.google.com/scholar?q=Organelle+communication+genetic+regulation+eukaryotic+evolution+2023"
          },
          {
            "title": "Telomere Biology and Genomic Stability: Evolutionary Perspectives",
            "keyIdea": "Researchers synthesize findings on telomere maintenance mechanisms, their role in preserving genomic integrity, and how telomere evolution reflects species-specific aging and cancer resistance strategies.",
            "url": "https://scholar.google.com/scholar?q=Telomere+biology+genomic+stability+evolution+2023"
          }
        ]
      },
      {
        "id": "node-3",
        "title": "DNA Structure and Function",
        "description": "Chemical structure of DNA, double helix geometry, base pairing, supercoiling, chromatin organization, and mechanisms of DNA replication and repair.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-4",
        "title": "Molecular Biology: Central Dogma",
        "description": "In-depth coverage of transcription (RNA synthesis), translation (protein synthesis), and RNA processing (splicing, capping, polyadenylation).",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-5",
        "title": "Bioinformatics Tools and Databases",
        "description": "Essential computational skills: sequence alignment (BLAST), genome browsers (UCSC, Ensembl), primary databases (GenBank, dbSNP), and version control for bioinformatics workflows.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-6",
        "title": "Gene Expression and Regulation",
        "description": "Promoters, enhancers, silencers, transcription factors, chromatin remodeling, and post-transcriptional regulatory mechanisms.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-7",
        "title": "RNA Biology and Non-Coding RNAs",
        "description": "Functional roles of lncRNAs, miRNAs, siRNAs, piRNAs, and circular RNAs in gene regulation, development, and disease.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-8",
        "title": "Epigenetics",
        "description": "DNA methylation, histone modifications, chromatin states, imprinting, X-inactivation, and epigenetic inheritance across generations.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-9",
        "title": "Mendelian and Complex Trait Genetics",
        "description": "Classical inheritance patterns, pedigrees, heritability, polygenic risk scores, QTL mapping, and gene-environment interactions.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-10",
        "title": "Population Genetics",
        "description": "Allele and genotype frequencies, Hardy-Weinberg equilibrium, inbreeding, population structure, and admixture.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-11",
        "title": "Evolutionary Forces",
        "description": "Natural selection, genetic drift, mutation pressure, gene flow, and their combined effects on genomic variation and adaptation.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-12",
        "title": "Phylogenetics and Molecular Evolution",
        "description": "Phylogenetic tree reconstruction, molecular clock, substitution models, and detecting positive/negative selection in genomes.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-13",
        "title": "Genomic Sequencing Technologies",
        "description": "First-generation (Sanger), second-generation (Illumina, Ion Torrent), third-generation (PacBio, Oxford Nanopore), and emerging single-molecule methods with trade-offs in cost, accuracy, and read length.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-14",
        "title": "Comparative Genomics",
        "description": "Whole-genome alignments, synteny analysis, ortholog/paralog identification, and using evolutionary conservation to annotate functional elements.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-15",
        "title": "Statistical Genetics",
        "description": "GWAS design, p-values and multiple testing correction (Bonferroni, FDR), linkage disequilibrium, fine-mapping, and meta-analysis of genetic association data.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-16",
        "title": "CRISPR and Genome Editing",
        "description": "Mechanisms of CRISPR-Cas9, base editing, prime editing, delivery methods, off-target effects, and therapeutic applications.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-17",
        "title": "Functional Genomics and Proteomics",
        "description": "Transcriptomics (RNA-seq, single-cell), chromatin profiling (ChIP-seq, ATAC-seq), and protein-level methods (mass spec, interactomics) to link genotype to phenotype.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-18",
        "title": "Applied Genomics and Precision Medicine",
        "description": "Cancer genomics, pharmacogenomics, rare disease diagnosis, liquid biopsies, polygenic risk scores in the clinic, and companion diagnostics.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-19",
        "title": "Ethical, Legal, and Social Implications (ELSI)",
        "description": "Informed consent, data privacy (GDPR, GINA), return of incidental findings, biobank governance, genetic discrimination, and equity in genomic medicine.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-20",
        "title": "Research Methodology and Critical Thinking",
        "description": "Experimental design, power and sample size calculations, handling batch effects, reproducibility, pre-registration, and critical appraisal of genomic literature.",
        "estimatedTime": "2 weeks"
      },
      {
        "id": "node-21",
        "title": "Case Studies in Genomic Medicine",
        "description": "Deep dives into real-world examples: BRCA1/2 in breast cancer, CFTR in cystic fibrosis, pharmacogenomics of warfarin, and tumor whole-exome sequencing in oncology.",
        "estimatedTime": "1.5 weeks"
      },
      {
        "id": "node-22",
        "title": "Future Trends and Emerging Fields",
        "description": "Synthetic biology, gene drives, AI and machine learning in genomics (variant prioritization, deep learning for regulatory elements), and single-cell multi-omics.",
        "estimatedTime": "1 week"
      }
    ],
    "topic": "Genomics genetics and evolution",
    "lastUsedAt": 1788745896399,
    "isFinalized": true
  }
}
EDU_ASSIST_METADATA_END -->
