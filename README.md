# TopPageAssignmentTemplate
# 📄 LaTeX Assignment Cover Page Template

A professional, NBA/NAAC-compliant assignment cover page template designed for academic institutions in India. This template provides a clean, structured format for student assignment submissions with integrated faculty evaluation framework.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/KingsukMajumdar/TopPageAssignmentTemplate/graphs/commit-activity)

---

## ✨ Features

- **Professional Design**: Clean, academic layout with institutional branding
- **NBA/NAAC Compliant**: Structured format suitable for accreditation documentation
- **Faculty Evaluation Framework**: Built-in rubric with Poor/Average/Good/Excellent grading scale
- **FontAwesome Icons**: Modern iconography for better visual appeal
- **Single Page Layout**: Optimized to fit all content on one A4 page
- **Customizable**: Easy to modify for different institutions and courses
- **Border Design**: Professional 3pt border frame

---

## 📋 Preview

The template includes:
- ✅ College logo placement
- ✅ Institution name and affiliation
- ✅ Department details
- ✅ Academic session information
- ✅ Assignment number
- ✅ Paper name and code
- ✅ Student details (Name, Roll No., Branch, Semester, Batch)
- ✅ Date of submission
- ✅ Student signature section
- ✅ Faculty feedback and evaluation rubric
- ✅ Marks allocation section
- ✅ Faculty signature with designation

---

## 🚀 Quick Start

### Prerequisites

Ensure you have a LaTeX distribution installed:

**Linux (Debian/Ubuntu)**:
```bash
sudo apt-get install texlive-full
```

**Arch/Manjaro**:
```bash
sudo pacman -S texlive-most texlive-fontsextra
```

**macOS**:
```bash
brew install --cask mactex
```

**Windows**: Download and install [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/)

### Required Packages

- `inputenc` - UTF-8 encoding support
- `geometry` - Page margin control
- `graphicx` - Logo and image handling
- `fontawesome5` - Icon support
- `setspace` - Spacing control
- `tikz` - Border drawing
- `array` - Table formatting
- `tabularx` - Flexible table widths
- `multirow` - Advanced table cells
- `calligra` - Calligraphic fonts

---

## 📖 Usage

### 1. Clone the Repository

```bash
git clone https://github.com/KingsukMajumdar/TopPageAssignmentTemplate.git
cd TopPageAssignmentTemplate
```

### 2. Add Your College Logo

Replace the placeholder with your institution's logo:
- Save your logo as `BCREC_logo.png` or `BCREC_logo.jpg`
- Place it in the same directory as the `.tex` file

### 3. Customize the Template

Edit the following sections in the `.tex` file:

**Institution Details**:
```latex
{\Large \textbf{Dr. B. C. Roy Engineering College, Durgapur}} \\
{\footnotesize \textit{(Affiliated to Maulana Abul Kalam Azad University of Technology, West Bengal)}}
{\Large \textbf{Department of Electrical Engineering}}
```

**Academic Session & Assignment**:
```latex
{\large \textbf{Academic Session: 2025-26 (EVEN)}}
{\large \textbf{ASSIGNMENT NO: 02}}
```

**Course Details**:
```latex
{\Large \textbf{Power System Planning and Reliability}}
{\Large \textbf{Paper Code: PSM104}}
```

**Student Information**:
```latex
\large \faUser \hspace{0.2cm} \textbf{Name:} & \large \hspace{0.5cm} YOUR NAME HERE \\
\large \faIdCard \hspace{0.2cm} \textbf{Univ. Roll No:} & \large \hspace{0.5cm} 123456789 \\
```

**Faculty Details**:
```latex
& Kingsuk Majumdar Ph.D. (Engg)\\
& Asstt. Professor/ EE, BCREC
```

### 4. Compile the Document

**Using Command Line**:
```bash
pdflatex assignment_cover_page.tex
```

**Using TeXstudio/TeXmaker**:
- Open the `.tex` file
- Click on Build & View (F5)

**Using Overleaf**:
- Upload the `.tex` file and logo
- Click "Recompile"

---

## 🎨 Customization Options

### Changing Border Width
```latex
\draw[line width=3pt]  % Change 3pt to desired thickness
```

### Adjusting Margins
```latex
\usepackage[top=1in, bottom=1in, left=1in, right=1in]{geometry}
```

### Modifying Evaluation Scale
Edit the faculty feedback table:
```latex
\begin{tabular}{|c|c|c|c|}
    \hline
    \textbf{Poor} & \textbf{Average} & \textbf{Good} & \textbf{Excellent} \\
    \scriptsize (1-2) & \scriptsize (3-5) & \scriptsize (6-8) & \scriptsize (9-10) \\
    \hline
```

### Changing Date Format
```latex
\large \faCalendarCheck \hspace{0.2cm} \textbf{Date of Submission:} & \large \hspace{0.5cm} \today \\
```
Replace `\today` with a specific date: `15th January 2026`

---

## 📁 File Structure

```
assignment-cover-page/
├── assignment_cover_page.tex    # Main LaTeX template
├── BCREC_logo.png               # College logo (add your own)
├── README.md                     # This file
├── LICENSE                       # MIT License
└── examples/                     # Sample outputs
    └── sample_output.pdf
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this template:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍🏫 Author

**Kingsuk Majumdar, Ph.D. (Engg.)**  
Assistant Professor, Department of Electrical Engineering  
Dr. B. C. Roy Engineering College, Durgapur

- 🌐 Website: [Learn With Kingsuk](https://www.youtube.com/@LearnWithKingsuk)
- 💼 LinkedIn: [Kingsuk Majumdar](https://linkedin.com/in/kingsuk-majumdar)
- 🔬 ORCID: [0000-0001-7224-4862](https://orcid.org/0000-0001-7224-4862)

---

## 🏷️ Keywords

`latex` `assignment-template` `academic` `nba` `naac` `education` `india` `engineering` `template` `cover-page` `student` `faculty-evaluation`

---

## 📊 Usage Statistics

If you use this template, please consider:
- ⭐ Starring this repository
- 🍴 Forking for your institution
- 📢 Sharing with colleagues

---

## 🔗 Related Resources

- [LaTeX Project](https://www.latex-project.org/)
- [Overleaf Templates](https://www.overleaf.com/latex/templates)
- [CTAN - Comprehensive TeX Archive Network](https://www.ctan.org/)
- [NBA India](https://www.nbaind.org/)
- [NAAC](https://www.naac.gov.in/)

---

## 📞 Support

For issues, questions, or suggestions:
- Open an [Issue](https://github.com/KingsukMajumdar/assignment-cover-page/issues)
- Start a [Discussion](https://github.com/KingsukMajumdar/assignment-cover-page/discussions)

---

## 🙏 Acknowledgments

- FontAwesome team for the excellent icon library
- LaTeX community for continuous support and documentation
- Dr. B. C. Roy Engineering College for institutional support

---

<div align="center">

### Made with ❤️ for the Academic Community

**#LearnWithKingsuk** | **#LaTeX** | **#AcademicTemplates**

*"Excellence is not a destination; it is a continuous journey that never ends."*  
[![GitHub followers](https://img.shields.io/github/followers/KingsukMajumdar?style=social)](https://github.com/KingsukMajumdar)
[![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCo2Rho6ypq7IkxaKwByWQRA?style=social)](https://youtube.com/@LearnWithKingsuk)

</div>

---

**© 2026 Kingsuk Majumdar. All rights reserved.**
