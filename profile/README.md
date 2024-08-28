![1](./assets/banner.png)

Landslides, as a natural phenomenon, can lead to devastating outcomes, including loss of life and severe economic impacts. With growing populations, the expansion of residential and industrial areas into unstable hillsides has heightened the risk and frequency of landslides. 

We focus on simulating the post-failure motion of landslides, which typically involves large deformation challenges. Traditional mesh-based numerical methods often suffer from mesh distortion issues, but the Material Point Method (MPM), which couples Lagrangian and Eulerian perspectives, effectively overcomes this problem. For computational efficiency, we implement our algorithms using the Julia Language, designed for high-performance numerical computing. This organization includes actively developed packages and archives of code from previous papers.

- **MaterialPointSolver.jl** - A backend-agnostic MPM solver in Julia Language. It is suitable for rapid prototyping and allows seamless transition to production environments to solve high-resolution models. Its efficiency, flexibility, and ease of use enhance the practicality of MPM in complex geotechnical engineering modeling.

- **MaterialPointGenerator.jl** - Help users to quickly generate MPM model from DEM files. The generated files through the use of simple modifications should be applied to other structured grid MPM program.

*More tools is on coming...*

## Acknowledgement 👏

This project is sponserd by [Risk Group | Université de Lausanne](https://wp.unil.ch/risk/) and [China Scholarship Council [中国国家留学基金管理委员会]](https://www.csc.edu.cn/).

---

<div align=center>
2024 LandslideSIM <br>
Risk Group | Universitvé de Lausanne<br>
</div>
