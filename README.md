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

# 2. Configurations

You can change the constants of the document in `configs/Constants.tex`. These constants are:

```tex
\author{Your name here}
\title{A \LaTeX{} Thesis Template for ENCS Graduate Student from Concordia University}

% For master's degree only, will be ignored if PhD.  Default: Master of Applied Science
\mastersDegree{Master of Applied Science}

%##### BEGIN: FOR PhD ONLY #####
% or Ms., Mrs., Miss, etc. (only for PhD's)
\titleOfPhDAuthor{Mr.}
% Masters by default, if PhD, remove the comment
% \PhD
%#### END: FOR PhD Only #####

% program towards your degree. E.g., Mechanical Engineering, Quality System Engineering. Default: I.E.
\program{Industrial Engineering}

% your department. Default:  Mechanical and Industrial Engineering
\dept{Mechanical and Industrial Engineering}

% your department chair. default:  Martin D. Pugh, Chair of MIE (As of Oct 2015)
\chairOfDept{Martin D. Pugh}

% Dean of ENCS. Default:  Amir Asif, Dean of ENCS (As of Oct 2015)
\deanOfENCS{Amir Asif}

%%%% Your Final Examining Committee Members %%%
\chairOfCommittee{Name of the Chair}
\examinerExternalOfCommittee{Name of External Examiner}
\examinerFirstOfCommittee{Name of Examiner One}
\examinerSecondOfCommittee{Name of Examiner Two} % for PhD student
\principaladvisor{Name of Supervisor}

%%Following two lines are required if you have a co-supervisor
%\cosupervisor
%\myCoSupervisor{Name of Co-supervisor}
```

# 3. Feature Screenshots

1. Title Page

![Title Page](/figures/TitlePage.png)

2. Signature Page

![Signature Page](/figures/SignaturePage.png)

3. Abstract Page

![Abstract Page](/figures/PhDAbstract.png)

4. Degree Configuration

![Degree Configuration](/figures/DegreeInformation.png)

# 4. Requirements
In order to run it properly, you must have the following available
* MikTex 2.9
* A LaTeX editor, e.g., TeXstudio, Texmaker, TeXnic, or TeXworks. I use vscode
* The template `ConcordiaThesis.tex` and the style file `ConcordiaU.sty`.
* Internet connection if you are running it at your first time. You may need to download necessary package(s).

# 5. Troubleshooting

The template has been tested with TeXstudio, TeXworks, CTex, and TeXnic under MikTex 2.9, with UTF-8 encoding. If you notice anything in the Thesis Specifications that does not match the templates, please let me know. I will make my effort to keep it up to date.

# 6. FAQ
> Q: Why I am getting question marks `?` for the citations, and references are not shown anymore?

A: Please
1. Make sure your bibliography file (.bib) is in the folder and each item is configured correctly (pay attention to `,` and `}`.
2. Run in this sequence: `pdfLaTex` -->  `bibTex` --> `pdfLaTex`.  It may help.

# 7. Original Contact
* Suo Tan - [tandysony@gmail.com](tandysony@gmail.com)
