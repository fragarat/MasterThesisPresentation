# Master Thesis Presentation

This repository contains the LaTeX source files for my Master's thesis presentation. It is designed to be compiled using XeLaTeX to support custom fonts and ensure compatibility with the university's style guidelines.

## Repository Structure

```text
MasterThesisPresentation/
├── chapters/ # Chapter content files
├── images/ # Images and figures
├── style/ # Custom style files (e.g., UU_beamer.sty)
├── MasterThesisPresentation_Francisco.pdf # Compiled PDF
├── ThesisPresentationCover.pdf # Cover slide PDF
├── code.py # Python code for data processing
├── main.tex # Main LaTeX file
├── preamble.tex # LaTeX preamble with settings
└── ref.bib # Bibliography file
```


## Compilation Instructions

1. **Requirements**: Ensure you have a LaTeX distribution installed that supports system fonts, such as [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/). You will also need **XeLaTeX** to compile this template with custom fonts.
2. **Necessary Files**: Place all repository files in the same directory.
3. **Compile**: Run the following command in your terminal:

   ```bash
   xelatex main.tex
   ```

## Customization

- **Fonts**: The template uses custom fonts. To use other fonts, modify the UU_beamer.sty file.
- **Content**: Edit Edit the chapters/ directory files to add or modify your presentation content.
- **Images**: Add or replace images in the images/ directory as needed..

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
