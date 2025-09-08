# LaTeX Resume Templates

Professional LaTeX resume templates available in both English (US) and Portuguese (Brazil) formats. These templates are designed to create clean, modern, and ATS-friendly resumes.

## Features

- Bilingual Support: Templates available in English (US) and Portuguese (Brazil)
- ATS-Friendly: Clean formatting that works well with Applicant Tracking Systems
- Professional Design: Modern and minimalist layout
- Easy Customization: Well-commented LaTeX code for easy modification
- Multiple Sections: Support for experience, education, skills, projects, and more

## Repository Structure

```
templates/
├── en_us/
│   ├── resume.pdf # PDF preview for English template
│   └── resume.tex # Latex file for English template
└── pt_br/
    ├── curriculo.pdf # PDF preview for Portuguese (Brazil) template
    └── curriculo.tex # Latex file for Portuguese (Brazil) template
README.md

```

## Usage

### Method 1: Local Compilation

**Prerequisites:**

To use these templates locally, you'll need to:

1. Install a LaTeX Distribution: TeX Live (recommended) or MiKTeX
2. Clone the repository:
   ```bash
   git clone https://github.com/laporeon/latex-resume-templates.git
   cd latex-resume-templates
   ```
3. Choose template language
   - For English: `cd templates/en_us/`
   - For Portuguese: `cd templates/pt_br/`
4. Edit the template

   - Open `resume.tex` or `curriculo.text` in your preferred LaTeX editor.
   - Customize the content under each section (skills, experience, projects, education) according to your own details.
   - Modify the styling, fonts, or colors as needed.

5. Compile the document
   - Compile the LaTeX file (`resume.tex` or `curriculo.tex`) using your LaTeX distribution.
   - This will generate the PDF output (`resume.pdf`) with your updated resume.

### Method 2: Using Overleaf

1. Create a new project on [Overleaf](https://overleaf.com).
2. Upload the \*_.tex_ file you want to use (`resume.tex` or `curriculo.tex`)
3. Edit directly in Overleaf – the PDF will compile automatically

---

> **Note:** Remember to remove all placeholder content and replace it with your actual information before using these templates for job applications.

---

## Troubleshooting

### Common Issues

**Missing packages error:**
Install missing packages using your LaTeX distribution's package manager

**Font issues:**
Try compiling with xelatex instead of pdflatex for better font support

**Compilation errors:**

- Check for missing closing braces
- Verify all required packages are installed
- Ensure file encoding is UTF-8

## License

This project is licensed under the MIT License.
