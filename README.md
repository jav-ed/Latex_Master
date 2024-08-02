# Flow Predictions Using Control-Oriented Cluster-Based Network Modeling

## About This Repository

This repository contains the complete LaTeX source, figures, and compiled [PDF](main.pdf) of my master thesis, submitted on 29.04.2022 to the Technische Universität Braunschweig, Institute of Fluid Mechanics, Germany.

![Tornado](2_Figures/0_Deco/Tornado.png)
## Thesis Overview

This master thesis focuses on developing a data-driven modeling technique for predicting the behavior of general dynamic systems, particularly aimed at complex fluid dynamics problems. The work contributes to the fields of fluid mechanics, machine learning, and computational modeling.

## Key Achievements

* Developed an improved version of control-oriented Cluster-based Network Modeling (CNMc) for predicting trajectories of general dynamical systems
* Removed key limitations of the previous CNMc version, enabling application to any general dynamical system regardless of dimensionality or trajectory shape
* Implemented 10 different dynamical systems by default to demonstrate CNMc's broad applicability
* Replaced computationally expensive Non-negative Matrix Factorization (NMF) with faster Singular Value Decomposition (SVD) for modal decomposition, reducing runtime from hours to seconds
* Wrote CNMc from scratch in a modular way to allow easy integration with existing code and straightforward replacement of algorithms
* Developed a flexible configuration system allowing all important parameters to be adjusted via a single settings file
* Implemented post-processing features including HTML plot generation with interactive capabilities for in-depth visual analysis
* Added functionality to execute multiple dynamical models sequentially and selectively enable/disable CNMc steps
* Demonstrated CNMc's ability to capture and predict behavior of complex nonlinear and chaotic dynamical systems
* Removed interpolation errors by replacing B-spline with linear interpolation, enabling appropriate visualization of predicted trajectories

## Repository Structure

- `1_Latex_Files/`: LaTeX source files
- `2_Figures/`: Figures and images used in the thesis
- `3_Bibtex/`: Bibliography files
- `main.tex`: The main LaTeX file for the thesis
- `main.pdf`: The compiled [PDF](main.pdf) of the thesis
- `license.md`: License information for this project
- `README.md`: This file, providing an overview of the repository

## Compilation Note

This project uses TikZ diagrams. To compile the thesis correctly, you need to replace the following line in the relevant .tex files: `\input{/home/jav/Progs/Virt_Env/writing/lib/python3.12/site-packages/pyxdsm/diagram_styles.tex`
with the actual path to the `diagram_styles.tex` file on your system.

For the initial build process, you may need to run the following sequence:

1. pdflatex
2. makeglossaries
3. pdflatex
4. pdflatex

## Important Notes

1. The PDF file (`main.pdf`) in the root directory is the original, unmodified version as submitted. Any mistakes found post-submission have not been corrected to maintain the integrity of the original work.
2. This repository can be used as a template for similar projects.
3. We all learn and grow. I acknowledge that mistakes were made in the past, and inshallah, I will continue to learn from future experiences.

## License

Please refer to the `license.md` file in this repository for detailed licensing information.

## Contact

For more information or to get in touch, please visit my website: [javedab.com](https://javedab.com)

## Note on README Creation

This README was created with the assistance of an AI large language model, specifically the Claude 3.5 Sonnet model. While the content accurately reflects the thesis and repository structure, the wording and organization were enhanced through AI collaboration.

---

Feel free to explore this repository and use it as a reference for your own work. If you have any questions or feedback, please don't hesitate to reach out through the contact information provided above.