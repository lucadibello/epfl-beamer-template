# EPFL Beamer Presentation Template

This repository provides a minimal and clean LaTeX Beamer template designed for EPFL students. It aims to offer a straightforward starting point for your presentations, incorporating the EPFL logo on every slide for official affiliation.

## Example Slides

#### First slide

<center>
<img src="./assets/example_title.png" alt="Example Title Slide" width="600">
</center>

#### Other example slides

<center>
<img src="./assets/example_simple_slide.png" alt="Example Title Slide" width="600">
</center>
<center>
<img src="./assets/example_other_simple_slide.png" alt="Example Title Slide" width="600">
</center>

## Features

- **Clean and Minimal Design**: Focuses on content presentation without distracting visual clutter.
- **EPFL Logo Integration**: The EPFL logo is consistently placed in the bottom-right corner of all slides, including the title page.
- **Standard LaTeX Packages**: Includes essential packages for mathematics, graphics, and good document practices.
- **Easy to Customize**: A modular structure with separate files for preamble and math commands.

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
   ```

2. **Place the EPFL Logo**: Ensure you have the `epfl.png` logo file in a `figures/` subdirectory:

   ```
   .
   ├── main.tex
   ├── preamble.tex
   ├── math_commands.tex
   └── figures/
       └── epfl.png
   ```

   (If you don't have the `epfl.png` file, you might need to obtain an official version from EPFL's visual identity resources.)

3. **Compile**: Use a LaTeX compiler (e.g., `pdflatex`) to build your presentation. Remember to compile at least twice for the table of contents and cross-references to resolve correctly.

   ```bash
   pdflatex main.tex
   pdflatex main.tex
   ```

## Included Files

- [`main.tex`](main.tex): The main document file where you define your presentation structure, title, author, and include frames.
- [`preamble.tex`](preamble.tex): Contains all LaTeX package inclusions and general Beamer settings for consistent styling.
- [`math_commands.tex`](math_commands.tex): A dedicated file for common mathematical macros and operators.
- `figures/epfl.png`: The placeholder for the EPFL logo used throughout the presentation.
