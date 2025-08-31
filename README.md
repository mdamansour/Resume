# Professional ATS-Friendly Resume in LaTeX

This repository contains a professional, ATS-friendly resume template written in LaTeX. It is designed for electrical engineering graduates or similar technical professionals, emphasizing clean formatting, readability, and compatibility with Applicant Tracking Systems (ATS). The template compiles to a PDF that maintains a structured layout while ensuring key information is easily parseable by automated systems.

## Features
- **ATS-Compatible**: Uses standard fonts, simple structure, and avoids tables/graphics that could confuse ATS parsers. Hyperlinks are included but formatted to not disrupt text flow.
- **Modern Design**: Clean, two-column layout with color accents for sections, skills, and contact info.
- **Customizable**: Easily editable LaTeX source file (`Resume.tex`) for personal details, experiences, skills, and projects.
- **Included Sections**: Professional summary, education, experience (internships), academic projects, technical skills, languages, certifications, soft skills, and hobbies.
- **Dependencies**: Relies on common LaTeX packages like `geometry`, `hyperref`, `fontawesome5`, and others (see preamble in `Resume.tex`).
- **Profile Image**: Supports an optional profile photo (replace `profile.jpg` with your own image).

## Preview
The compiled PDF (`Resume.pdf`) is included in the repository for reference. It showcases a sample resume for Mohammed Amansour, an Electrical Engineering graduate.

## How to Use
1. **Clone the Repository**:
   ```
   git clone https://github.com/mdamansour/Resume.git
   ```
2. **Install LaTeX**: Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX). Required packages are standard and should be available by default.
3. **Customize**:
   - Edit `Resume.tex` with your personal information.
   - Replace `profile.jpg` if you want to include a photo (optional; remove the `\includegraphics` line if not needed).
4. **Compile**:
   Run the following command in the repository directory:
   ```
   pdflatex Resume.tex
   ```
   This will generate `Resume.pdf`. You may need to run it twice for hyperlinks and references to resolve properly.
5. **Tips for ATS Optimization**:
   - Use keywords from job descriptions in your content.
   - Avoid complex tables or columns in the LaTeX code (this template uses minipages for layout).
   - Test the PDF with online ATS simulators.

## Requirements
- LaTeX compiler (e.g., pdflatex).
- Basic LaTeX packages: `article`, `geometry`, `enumitem`, `multicol`, `parskip`, `xcolor`, `fontenc`, `helvet`, `graphicx`, `hyperref`, `fontawesome5`.

No additional installations are needed beyond a standard LaTeX setup.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
- GitHub: [mdamansour](https://github.com/mdamansour)
- LinkedIn: [linkedin.com/in/mdamansour](https://linkedin.com/in/mdamansour)
- Website: [amansour.me](https://amansour.me)
- Email: m@amansour.me

Feel free to fork this repository and adapt it for your own use! If you have suggestions or improvements, open an issue or pull request.