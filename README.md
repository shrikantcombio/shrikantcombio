# Hi there, I'm Shri Kant 👋

[![Postdoc](https://img.shields.io/badge/Postdoc-Université%20Paris%20Cité%20%26%20Univ.%20of%20Reunion%2C%20France-purple.svg?style=flat-square)](https://u-paris.fr/)
[![PhD IIT Kharagpur](https://img.shields.io/badge/PhD-IIT%20Kharagpur-orange.svg?style=flat-square)](https://www.iitkgp.ac.in/)
[![CSB Lab](https://img.shields.io/badge/Lab-CSB%20Lab-1f883d.svg?style=flat-square)](http://www.csb.iitkgp.ac.in/)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0211--539X-green.svg?style=flat-square&logo=orcid)](https://orcid.org/0000-0003-0211-539X)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Citations-4285F4.svg?style=flat-square&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=shrikantcombio)
[![Website](https://img.shields.io/badge/Website-shrikant--kaushik.github.io-blue.svg?style=flat-square)](https://shrikant-kaushik.github.io)
[![Email](https://img.shields.io/badge/Email-shrikant92pharmacy%40gmail.com-blue.svg?style=flat-square&logo=gmail)](mailto:shrikant92pharmacy@gmail.com)

> **Postdoctoral Researcher** @ **Université Paris Cité & Université de La Réunion, France**  
> 🎓 **PhD in Computational Structural Biology** @ [**CSB Lab**](http://www.csb.iitkgp.ac.in/), [**Indian Institute of Technology Kharagpur**](https://www.iitkgp.ac.in/)  
> 📖 **PhD Thesis**: *"Conformational analysis of protein–RNA recognition"* (Advisor: [Prof. Ranjit P. Bahadur](http://www.csb.iitkgp.ac.in/))  
> 🎯 **Research Focus**: Protein–RNA recognition mechanisms, conformational selection & induced fit, RNA-binding protein rotamer libraries, RNA conformers, high-performance computing (HPC), and multi-microsecond molecular dynamics simulations.

---

## 🔬 Major PhD Research Contributions (Protein–RNA Recognition)

My doctoral research centered on deciphering the molecular principles, conformational transitions, and energetics governing protein–RNA recognition across four major contributions:

### 1. [PRDB v3.0: Protein–RNA Docking Benchmark & Binding Affinity](https://github.com/shrikantcombio/PRDBv3_dataset.git)

* **Overview**: Developed a non-redundant, high-resolution protein–RNA docking benchmark dataset (version 3.0) integrated with experimental binding affinity ($\Delta G / K_d$).
* **Significance**: Provides the structural biology community with a standardized gold standard to evaluate rigid-body and flexible docking algorithms, scoring functions, and interface energetics.
* **Publication**: *Proteins: Structure, Function, and Bioinformatics* (2025) | [DOI: 10.1002/prot.26825](https://doi.org/10.1002/prot.26825)
* **Repository**: [`shrikantcombio/PRDBv3_dataset`](https://github.com/shrikantcombio/PRDBv3_dataset.git)

### 2. [RBP-Specific Rotamer Libraries (BBD, BBI, and SSD)](https://github.com/shrikantcombio/RBPs_rotamer_lib.git)

* **Overview**: Built RNA-binding protein-specific **Backbone-Dependent (BBD)**, **Backbone-Independent (BBI)**, and **Secondary Structure-Dependent (SSD)** side-chain rotamer libraries.
* **Significance**: Characterized the side-chain conformational transitions that occur upon RNA binding, providing essential priors for accurate modeling of induced-fit side-chain adjustments in RBPs.
* **Status**: *Nucleic Acids Research* (2025, Submitted)
* **Repository**: [`shrikantcombio/RBPs_rotamer_lib`](https://github.com/shrikantcombio/RBPs_rotamer_lib.git)

### 3. [RNA diNucleotide Conformers Library for Protein–RNA Complexes](https://github.com/shrikantcombio/RBPs_RNA_conformers_lib.git)

* **Overview**: Curated a structural library of RNA dinucleotide conformers in both bound and unbound protein–RNA complexes.
* **Significance**: Systematically decoded RNA backbone flexibility ($\alpha, \beta, \gamma, \delta, \epsilon, \zeta$) and glycosidic ($\chi$) torsion angles, uncovering the conformational selection vs. induced-fit dynamics of RNA in macromolecular recognition.
* **Status**: *RNA Journal* (2025, Under Revision) | [BioRxiv: 10.64898/2026.05.14.725147](https://doi.org/10.64898/2026.05.14.725147)
* **Repository**: [`shrikantcombio/RBPs_RNA_conformers_lib`](https://github.com/shrikantcombio/RBPs_RNA_conformers_lib.git)

### 4. Molecular Dynamics of Non-Canonical RNA-Binding Domains

* **Overview**: Applied multi-microsecond all-atom Molecular Dynamics simulations (using GROMACS & AMBER on [IIT Kharagpur's](https://www.iitkgp.ac.in/) *Paramshakti* supercomputer) to investigate non-canonical RBP recognition.
* **Significance**: Unraveled mutually induced conformational changes in the Ubiquitin-Like Domain (ULD) of SF3A1 recognizing the stem-loop 4 (SL4) of U1 snRNA during early spliceosome assembly.
* **Status**: *Journal of Molecular Recognition* (2026, Under Revision) | [BioRxiv: 10.64898/2026.03.30.715355](https://doi.org/10.64898/2026.03.30.715355)

---

## 🛠️ Current Software & Webserver Development

Active computational platforms and toolkits currently under development:

| Platform / Tool | Description | Tech Stack |
| :--- | :--- | :--- |
| 🌐 [**NAPxplorer**](https://github.com/shrikantcombio/NAxplorer) | High-performance computational framework & interactive web platform for comprehensive interface profiling (14 interaction subtypes), semi-empirical quantum energetics (GFN2-xTB), surface morphometry, and 3D visualization of Protein–RNA/DNA/DRBP complexes. | `Python 3.10+`, `Flask 3.x`, `WTForms`, `Werkzeug`, `GFN2-xTB`, `PDBe Mol*`, `x3dna-dssr`, `REST API` |
| 👑 [**PRince v2.0**](https://github.com/shrikantcombio/PRince) | Next-generation webserver & ultra-fast C calculation engine for automated interface analysis (SASA, BSA, HBPLUS hydrogen bonding, water bridges) in Protein-RNA/DNA/Ligand complexes. | `C99`, `Python`, `NACCESS`, `HBPLUS`, `Bash` |
| 🧬 **DBTraj** | Specialized Molecular Dynamics trajectory analysis toolkit engineered for protein–RNA complexes: tracking interface persistence, conformational transitions, and dynamic interaction networks. | `Python`, `MDAnalysis`, `GROMACS`, `NumPy`, `Seaborn` |
| 📊 **TF-NRD Suite** | Structural bioinformatics pipeline for the Transcription Factors Non-Redundant Dataset (*JSB* under revision). | `Python`, `Pandas`, `Biopython`, `mmCIF` |

---

## 📚 Selected Publications & Preprints

1. **Kant S**, Chandran N, Mukherjee S, Maity A, Bahadur RP. (2025). **Protein-RNA Docking Benchmark v3.0 integrated with Binding Affinity.** *Proteins: Structure, Function, and Bioinformatics*. [DOI: 10.1002/prot.26825](https://doi.org/10.1002/prot.26825)
2. Mukherjee S\*, **Kant S\***, Bahadur RP. (2025). **Transition of side-chain conformations of RNA-binding proteins upon binding RNA.** *Nucleic Acids Research* (Submitted). (\*Joint first authors)
3. **Kant S**, Masipeddi S, Bahadur RP. (2025). **Deciphering conformational preferences of RNA in protein-RNA recognition.** *RNA Journal* (Under Revision). [BioRxiv: 10.64898/2026.05.14.725147](https://doi.org/10.64898/2026.05.14.725147)
4. **Kant S**. (2026). **Decoding Mutually Induced Conformational Changes in Non-Canonical Recognition of U1 SL4 snRNA by ULD of SF3A1 during Early Spliceosome Assembly.** *Journal of Molecular Recognition* (Under Revision). [BioRxiv: 10.64898/2026.03.30.715355](https://doi.org/10.64898/2026.03.30.715355)
5. Garai S\*, **Kant S\***, Bahadur RP. (2026). **TF-NRD: Transcription Factors non-Redundant Sequence and Structure Dataset.** *Journal of Structural Biology* (Accepted). [[Webserver](http://www.csb.iitkgp.ac.in/databases/TFNRDv1.0/tfnrd.html)]
6. Verma J, Jain D, Panda AP, **Kant S**, Kumar G, Ghosh AS. (2023). **Involvement of non-active site residues in the catalytic activity of NDM-4 Metallo beta-lactamase.** *The Protein Journal*. [DOI: 10.1007/s10930-023-10124-6](https://doi.org/10.1007/s10930-023-10124-6)
7. Agarwal A, **Kant S**, Bahadur RP. (2023). **Efficient mapping of RNA-binding residues using local sequence features in protein-RNA complexes.** *Proteins: Structure, Function, and Bioinformatics*. [DOI: 10.1002/prot.26528](https://doi.org/10.1002/prot.26528)
8. Agarwal A, Alagar S, **Kant S**, Bahadur RP. (2023). **Binding dynamics of tandem RNA recognition motifs (tRRMs) of HuR with mRNA.** *Journal of Biomolecular Structure and Dynamics*. [DOI: 10.1080/07391102.2022.2073270](https://doi.org/10.1080/07391102.2022.2073270)
9. Agarwal A, Singh K, **Kant S**, Bahadur RP. (2022). **Comparative analysis of machine learning classifiers for predicting protein-binding nucleotides in RNA sequences.** *Computational and Structural Biotechnology Journal*. [DOI: 10.1016/j.csbj.2022.06.036](https://doi.org/10.1016/j.csbj.2022.06.036)

---

## 💻 Computational Skills & Supercomputing (HPC)

* **Programming & Scripting**: Python, C, C++, R, Bash / Shell Scripting
* **Molecular Dynamics Simulations**: GROMACS, AMBER, VMD, trajectory analysis pipelines
* **Structural Bioinformatics & Modeling**: NACCESS, HBPLUS, x3dna-dssr, DSSP, US-align, TM-align, MMseqs2, MODELLER, PyMOL, ChimeraX
* **High-Performance Computing (HPC)**: Slurm workload manager, parallel job arrays, Paramshakti Supercomputer (National Supercomputing Mission, NSM)
* **Machine Learning & Data Science**: Scikit-learn, PyTorch, NumPy, Pandas, SciPy, Matplotlib, Seaborn
* **Web Development & Databases**: Django, HTML/CSS, PHP, MySQL, Apache, REST APIs
* **Environments**: Linux (Ubuntu, CentOS), Git, GitHub Actions, Docker

---

## 🏆 Honors, Awards & Fellowship

* **Postdoctoral Researcher** – Université Paris Cité & Université de La Réunion, France
* **Travel Grant** – 13th RNA India Meeting (2026), IISc Bengaluru
* **Travel Grant** – EMBL Conference: *The Expanding World of RBPs* (2025), Heidelberg, Germany
* **Fully Funded Fellow** – EMBO Workshop on Computational Structural Biology (2023), Heidelberg, Germany
* **Institute Research Fellowship** – [Indian Institute of Technology (IIT) Kharagpur](https://www.iitkgp.ac.in/) (2018–2024)
* **All India Rank (AIR) 4** – DBT Computational Biology Entrance Examination

---

## 📈 GitHub Statistics & Activity

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=shrikantcombio&show_icons=true&theme=nord&count_private=true" height="175" alt="Shri Kant, PhD's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shrikantcombio&layout=compact&theme=nord" height="175" alt="Top Languages" />
</p>

---

## 📫 Connect & Collaborate

* 🌐 **Personal Website**: [https://shrikant-kaushik.github.io](https://shrikant-kaushik.github.io)
* 🏛️ **Current Affiliation 1**: [Université Paris Cité](https://u-paris.fr/) & [Université de La Réunion](https://www.univ-reunion.fr/), France
* 🏛️ **Current Affiliation 2**: [National Centre for Biological Sciences (NCBS), TIFR, Bangalore](https://www.ncbs.res.in/)
* 🎓 **Alma Mater**: [CSB Lab](http://www.csb.iitkgp.ac.in/), [Indian Institute of Technology Kharagpur](https://www.iitkgp.ac.in/)
* 📬 **Email**: [shrikant92pharmacy@gmail.com](mailto:shrikant92pharmacy@gmail.com)
* 💼 **LinkedIn**: [Shri Kant, PhD](https://www.linkedin.com/in/shrikant-kaushik)
* 🐙 **GitHub Profile**: [@shrikantcombio](https://github.com/shrikantcombio)

---
<p align="center"><i>"Decoding the structural dynamics and energetics of biomolecular recognition through computation and algorithms."</i></p>
