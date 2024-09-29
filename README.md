# Latex Template for submission to the Fully3D conference

Recommended template for submission to the 18th International Meeting on
Fully 3D Image Reconstruction in Radiology and Nuclear Medicine.

LaTex_Template_for_Fully3D_2025_submission.pdf is a rendered preview generated from the latex template.

**Submission rules**
- Submission must be in **PDF format** only.
- Use a **two-column format**.
- The font size for the main text should be **11**, while the
abstract and references can use font size **9**.
- Submission is limited to a **maximum of 4 pages**, in-
cluding all content (**strict limit**).
- Additionally, prepare a **short abstract** (maximum 150
words) for entry into the online submission system. This
abstract will be used for the program only and will not
be part of the review process nor the final proceedings.

## How to build the LaTex template

You can manually build the latex template by executing
```
pdflatex fully3d_template.tex
bibtex   fully3d_template.aux
pdflatex fully3d_template.tex
pdflatex fully3d_template.tex
```

Alternatively, run the build chain including pdflatex and bibtex of your favorite LaTex editor, or use the online LaTeX editor overleaf (https://www.overleaf.com/).
