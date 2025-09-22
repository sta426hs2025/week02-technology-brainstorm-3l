[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/aKWLU3-A)

People in the group: esonar, seanxie7, TrucTBui, GonCas12

# Topic: Single-cell ATAC-seq

*Source: Gemini. Prompt: write a short summary of how Single-cell ATAC-seq works. Utilize bullet points. Keep the content compact.*

Single-cell ATAC-seq (Assay for Transposase-Accessible Chromatin with sequencing) is a technique that maps **open chromatin regions** in individual cells, providing insights into gene regulation.

Here's a compact summary of how it works:

* **Cell Isolation & Permeabilization:** Individual cells are separated, and their membranes are gently opened to allow access to the nucleus.
* **Tagmentation:** The **Tn5 transposase** enzyme cuts DNA in accessible chromatin regions and inserts sequencing adapters.
* **Single-Cell Barcoding:** Each cell's DNA fragments are tagged with a unique barcode, enabling individual cell analysis.
* **Sequencing & Analysis:** Barcoded fragments are sequenced, and the reads are mapped to a reference genome to identify regions of open chromatin (peaks) in each cell.

This method helps researchers:
* Identify diverse **cell types and states**.
* Infer **transcription factor activity**.
* Understand **gene regulation** during cellular processes.

<img width="1597" height="271" alt="image" src="https://github.com/user-attachments/assets/7ebc4e05-16f0-4158-b4cb-acb9f0d7ca1f" />
Figure 1. Schematic representation of the single-cell ATAC-seq (scATAC-seq) workflow. From https://www.illumina.com/content/dam/illumina-marketing/documents/applications/ngs-library-prep/ForAllYouSeqMethods.pdf
