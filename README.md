In this work, I developed a Python-based computational framework to analyze and visualize NMR relaxation data that were originally processed using Mathematica.

This transition from Mathematica to Python significantly improved the reproducibility, scalability, and automation of NMR relaxation data analysis.

Python-readable formats and automated the data extraction, cleaning, sorting, and visualization processes using libraries such as pandas, NumPy, and Matplotlib.

The datasets containing residue-wise ¹⁵N R₁ρ relaxation rates were converted, visualized, and validated using Python, enhancing accuracy, reproducibility, and computational efficiency in protein dynamics analysis.

In NMR spectroscopy, R₁ρ relaxation measurements are used to probe microsecond-to-millisecond timescale motions in proteins. The relaxation rate constant gives information about conformational exchange, flexibility, and local structural dynamics.

Low R₁ρ values (e.g., ~4–6 s⁻¹): indicate rigid, well-structured regions of the protein.

High R₁ρ values (e.g., ~20–30 s⁻¹): indicate flexible, dynamic regions experiencing conformational exchange.

The plot illustrates the variation of R₁ρ relaxation rates across protein residues. Peaks represent flexible or conformationally dynamic regions, while troughs correspond to rigid, structured segments. The pattern highlights residue-specific internal motions, providing insights into the protein’s backbone dynamics and potential sites of conformational exchange.

Across all datasets, the statistical parameters such as mean, median, standard deviation, and range describe the overall distribution and variability of R₁ρ relaxation rates among protein residues.

The mean relaxation rate represents the average dynamic behavior of residues, indicating the general level of internal motion within the protein backbone.

The median (50th percentile) provides a robust measure of the central tendency, showing the typical relaxation rate unaffected by extreme values.

The standard deviation reflects how widely the relaxation rates vary across residues — a larger value indicates greater dynamic heterogeneity.

The minimum and maximum values define the range of molecular motions, from highly rigid (low R₁ρ) to flexible or exchanging regions (high R₁ρ).

Together, these statistics summarize the overall conformational flexibility and stability patterns observed in all the datasets, highlighting regions of structural order and dynamic motion within the protein.
