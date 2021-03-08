A LaTeX Thesis Template and Style for ENCS Graduate Students from Concordia University
---

* Version: v3.0
* Last updated:	Mars 07, 2021
* Author: Van Tuan Tran
* Original Author: Suo Tan
* Ptidej Lab
* Concordia University
* Montreal, QC, CA

# 1. Introduction
This thesis template has been created to make it easy to prepare your thesis using LaTeX while adhering to the [Concordia University Thesis Specifications posted online](https://www.concordia.ca/artsci/english/programs/graduate/english-ma/thesis-deadlines-formatting.html#format). The official thesis examples are provided here as a PDF file: http://www.concordia.ca/content/dam/concordia/offices/sgs/docs/handbooks/thesispreparationguide.pdf. Please refer to the last few pages for the thesis example.

# 2. Feature Screenshots

1. Title Page

![Title Page](/figures/TitlePage.png)

2. Signature Page

![Signature Page](/figures/SignaturePage.png)

3. Abstract Page

![Abstract Page](/figures/PhDAbstract.png)

4. Degree Configuration

![Degree Configuration](/figures/DegreeInformation.png)

# 3. Requirements
In order to run it properly, you must have the following available
* MikTex 2.9
* A LaTeX editor, e.g., TeXstudio, Texmaker, TeXnic, or TeXworks. I use vscode
* The template `ConcordiaThesis.tex` and the style file `ConcordiaU.sty`.
* Internet connection if you are running it at your first time. You may need to download necessary package(s).

# 4. Troubleshooting

The template has been tested with TeXstudio, TeXworks, CTex, and TeXnic under MikTex 2.9, with UTF-8 encoding. If you notice anything in the Thesis Specifications that does not match the templates, please let me know. I will make my effort to keep it up to date.

# 5. FAQ
> Q: Why I am getting question marks `?` for the citations, and references are not shown anymore?

A: Please
1. Make sure your bibliography file (.bib) is in the folder and each item is configured correctly (pay attention to `,` and `}`.
2. Run in this sequence: `pdfLaTex` -->  `bibTex` --> `pdfLaTex`.  It may help.

# 6. Original Contact
* Suo Tan - [tandysony@gmail.com](tandysony@gmail.com)
