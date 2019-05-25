# A Template for Thesis at National Institute of Technology Tiruchirappalli
This repository contains LaTeX template for NIT Trichy's M.S. (By Research)/PhD Thesis. This template has been created considering latest guidelines. The first prepared thesis using this template was submitted and accepted by MS/PhD section in May 2019. This template can also be used by B.Tech./M.Tech. students for their thesis preparation.

# Software Used
**A.** TeXMaker

**B.** MikTeX

# Usage Instructions
**A.** In root folder: Thesis.tex is **master** document. The master documents calls other documents, such as Chapters, Title and auxilary pages, abbreviations, etc.

**B.** Insert new chapters in chapters folder. Samples are included.

**C.** Basic knowlegde of LaTeX is required.

# Special Guidelines for generating Abbreviations and Nomenclatures
**A.** Download and Install ActivePerl using link: https://www.activestate.com/products/activeperl/downloads/

**B.** Open TeXMaker, goto **User>>User Commands>>Edit User Commands>>** then fill
Menu Item: *makeglossaries*
Command: *makeglossaries %*
Save this. Upon saving, makeglossaries shall appear as a custom command similar to pdflatex or bibtex etc.

**C.** During compilation, **run pdflatex>>makeglossaries>>pdflatex>>pdflatex**

# Final Compilation

**pdflatex>>makeglossaries>>bibtex>>pdflatex>>pdflatex**

Sometimes, few references do not appear as they should be. In such case, the bbl file can be edited to format references. This step should be the very last step of thesis preparation. After editing, run *pdflatex* command one last time.

*End of Document*
