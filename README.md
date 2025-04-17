ArIES Explainable Research Assessment Challenge
Overview
This repository contains a complete solution for the ArIES Explainable Research Assessment Challenge. The goal is to automate the evaluation of research papers for publishability and provide concise, explainable justifications for each decision. The solution processes all PDFs in the provided "Papers" folder, classifies each as "Publishable" or "Non-Publishable," and generates a human-readable rationale for the classification.

Repository Structure
text
.
├── ERAC_SUBMISSION.ipynb     # Main Jupyter notebook with the solution
├── Papers/                   # Folder containing input research paper PDFs
├── results.csv               # Output file with classifications and justifications
└── README.md                 # This file
How to Use
Setup

Open ERAC_SUBMISSION.ipynb in Google Colab or Jupyter Notebook.

Ensure the required Python packages are installed (pymupdf, transformers, pandas, etc.).

Place all research paper PDFs in the Papers/ directory.

Running the Notebook

Run all cells in the notebook.

The notebook will:

Extract and process each PDF.

Classify each paper as "Publishable" or "Non-Publishable."

Generate a concise justification for each classification.

Output

Results are saved in results.csv with the following columns:

Filename

Publishability

Justification

Sample Output
Filename	Publishability	Justification
paper15.pdf	Non-Publishable	This paper was classified as Non-Publishable because...
paper06.pdf	Publishable	This paper was classified as Publishable because...
paper07.pdf	Non-Publishable	This paper was classified as Non-Publishable because...
paper03.pdf	Non-Publishable	This paper was classified as Non-Publishable because...
paper02.pdf	Publishable	This paper was classified as Publishable because...
