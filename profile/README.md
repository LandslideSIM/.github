[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![email](https://img.shields.io/badge/contact-zenan.huo@unil.ch-purple)](mailto:zenan.huo@unil.ch)

Landslides, as a natural phenomenon, can lead to devastating outcomes, including loss of life and severe economic impacts. With growing populations, the expansion of residential and industrial areas into unstable hillsides has heightened the risk and frequency of landslides. 

We focus on simulating the post-failure motion of landslides, which typically involves large deformation challenges. Mesh-based numerical methods suffer from mesh distortion issues, but the Material Point Method (MPM), which couples Lagrangian and Eulerian perspectives, effectively overcomes this problem. For computational efficiency, we implement our algorithms using the Julia Language, designed for high-performance numerical computing. This organization includes actively developed packages and archives of code from previous papers.

- **MaterialPointSolver.jl** - A backend-agnostic MPM solver in Julia Language. It is suitable for rapid prototyping and allows a seamless transition to production environments to solve high-resolution models. Its efficiency, flexibility, and ease of use enhance the practicality of MPM in complex geotechnical engineering modeling.

- **MaterialPointGenerator.jl** - Help users to quickly generate MPM model from DEM files. The generated files through the use of simple modifications should be applied to other structured grid MPM programs.

- **MaterialPointVisualizer.jl** - Export MPM/other particle data to VTP files for visualization in ParaView. Surface reconstruction is also supported for further rendering of results ([splashsurf](https://github.com/InteractiveComputerGraphics/splashsurf)).

*More tools are on coming...*

## Acknowledgement 👏

This project is sponsored by [Risk Group | Université de Lausanne](https://wp.unil.ch/risk/) and [China Scholarship Council [中国国家留学基金管理委员会]](https://www.csc.edu.cn/).

<br>
<br>

<div align=center>
Risk Group | Universitvé de Lausanne<br>
</div>
