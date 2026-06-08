# Resume Workspace

This folder contains a LaTeX resume template and supporting files for tailoring it to a job description.

## Files

- `resume.tex` — editable LaTeX resume source.
- `resume.pdf` — compiled resume output.
- `JD.txt` — paste the target job description here before tailoring.
- `SKILL.md` — workflow instructions for tailoring the resume.
- `README.md` — this usage guide.

## Usage

1. Paste the target job description into `JD.txt`.
2. Edit `resume.tex` with accurate, role-specific content.
3. Compile the PDF:

   ```bash
   pdflatex -interaction=nonstopmode -halt-on-error resume.tex
   ```

4. Review `resume.pdf` before sending it to employers.
