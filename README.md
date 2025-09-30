# LaTeX Resume

This resume is structured using LaTeX to ensure consistent formatting and professional presentation. The project follows a modular approach with organized sections for easy maintenance and updates.

## Structure

The resume is organized into the following components:

### Main Files
- `resume.tex` - Main document that includes all sections
- `TLCresume.sty` - Custom LaTeX style template
- `_header.tex` - Document header configuration

### Sections Directory (`sections/`)
The content is modularized into separate `.tex` files for easy management:

- `activities.tex` - Awards, achievements, and notable activities
- `education.tex` - Educational background and qualifications  
- `experience.tex` - Professional work experience
- `objective.tex` - Professional summary and objectives
- `projects.tex` - Notable projects and contributions
- `relevant_publications.tex` - Academic publications and research
- `skills.tex` - Technical skills and competencies

## Building the Resume

To compile the LaTeX resume into a PDF:

```bash
pdflatex resume.tex
```

Or use `latexmk` for automatic compilation:

```bash
latexmk -pdf resume.tex
```

## Customization

To modify the resume content:

1. **Personal Information**: Edit `_header.tex`
2. **Work Experience**: Update `sections/experience.tex`
3. **Education**: Modify `sections/education.tex`
4. **Skills**: Update `sections/skills.tex`
5. **Projects**: Edit `sections/projects.tex`
6. **Activities & Awards**: Update `sections/activities.tex`

## Dependencies

Make sure you have a LaTeX distribution installed:
- **macOS**: MacTeX
- **Windows**: MiKTeX or TeX Live
- **Linux**: TeX Live

## Version Control

This project uses Git for version control, allowing you to:
- Track changes to resume content
- Maintain different versions for different positions
- Collaborate on improvements
- Keep a history of updates

## Output

The compiled resume generates:
- `resume.pdf` - The final formatted resume
- Supporting files (`resume.aux`, `resume.log`, etc.) - LaTeX compilation artifacts

---

## Credits

This template was adapted from [Angelo Menezes](https://github.com/angelomenezes)

