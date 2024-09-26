# 3D Module Integration in Growing Optimizer for Drug Discovery

## Project Overview

This repository contains the report and presentation from an internship project focused on incorporating a 3D module into a growing optimizer for drug discovery applications. The project explored various approaches to enhance molecular structure generation, ranging from basic centroid predictions to full molecular conformations.

## Key Objectives

1. Review state-of-the-art techniques in 3D structure generation and equivariant neural networks
2. Develop and implement 3D modules compatible with the existing growing optimizer
3. Benchmark models and conduct ablation studies to evaluate performance

## Main Achievements

### Centroid Prediction
- Implemented an EGNN model that significantly outperformed the MLP baseline
- Maintained 2D capabilities of the growing optimizer while adding 3D predictions
- Conducted ablation studies confirming the benefits of autoregressive generation and Uni-Mol embedding

### Full Conformation Generation
- Developed a FLAG-inspired module showing promise, despite some limitations
- Explored refinement approaches and identified areas for improvement

## Challenges and Future Directions

1. Optimize the 3D centroid module for processing larger batches
2. Address issues with atom positioning in the FLAG-inspired module
3. Investigate the integration of diffusion models or Flow Matching for improved 3D conformation generation
4. Explore ways to distill 3D information into the 2D module

## Repository Contents

- `report.pdf`: Detailed internship report
- `presentation.pdf`: Slides from the internship presentation
- `code/`: (If applicable) Implementation of key models and experiments

## Conclusion

This internship project has laid a solid foundation for integrating 3D modules within the growing optimizer for drug discovery. While significant advancements were made, particularly in centroid prediction, there remain exciting opportunities for further research and development in full molecular conformation generation.

## Acknowledgements

Special thanks to Iktos for providing the opportunity and resources for this internship project.

---

For more information about Iktos and their work in AI-driven drug discovery, please visit [https://www.iktos.ai/](https://www.iktos.ai/)
