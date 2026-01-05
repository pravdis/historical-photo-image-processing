# Historical Photo Image Processing (Assignment 2)

The project applies classical image processing techniques (denoising, edge detection, and segmentation) to a severely degraded historical photograph from circa 1880. The emphasis is on exploratory analysis, methodological limitations, and interpretability rather than full image restoration.

---

## Repository Structure

- `analysis.ipynb` — main Jupyter notebook (all analysis and figure generation)
- `data/`
  - `image.png` — original historical photograph (input)
- `figures/` — figures exported for inclusion in the report (outputs)
- `README.md`

---

## Reproducibility: How the Analysis Was Run

All figures and results reported in the written submission were generated using `analysis.ipynb`.

The notebook is self-contained and can be executed top-to-bottom to reproduce the analysis.

---

## Software Environment

- **Python version:** 3.11.7  
- **Execution environment:** VS Code with Jupyter Notebook support  
- **Operating system:** macOS Sequoia 15.0  

---

## Hardware

- **Machine:** MacBook Air (M2, 2022)
- **Processor:** Apple M2
- **Memory:** 8 GB RAM
- **GPU:** Not used  

---

## Dependencies

The analysis relies on standard scientific Python libraries:

- numpy
- matplotlib
- opencv-python
- scikit-image
- scipy

All libraries were installed via `pip`. No non-standard or proprietary packages were used.

---

## Execution Instructions

1. Open the repository in VS Code  
2. Ensure Python **3.11.7** is selected as the interpreter  
3. Open `analysis.ipynb`
4. Run all cells sequentially from top to bottom

- Full notebook runtime: **< 1 minute**
- No random seed is required (all operations are deterministic)

---

## Image Source and Attribution

The historical photograph analysed in this project is credited as follows:

**Friedrich Carl von Schneidlin** (c. 1880)  
*Upper suburb of Svätý Jur*  
Photograph  
Museum of the City of Bratislava  
Provided for non-commercial academic use.

The image is used strictly for educational and analytical purposes.

---


