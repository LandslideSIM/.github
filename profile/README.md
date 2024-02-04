![](assets/banner.png)

The simulation of post-landslide propagation is a complex nonlinear problem involving a wide range of physical processes, such as rock breakage, soil deformation, fluid flow and multi-physical coupling. The organization stores relevant code, including numerical simulation tools, potential failure surface analysis, and post-processing.

- **MaterialPointSolver.jl** - For similar large deformation situations, the material point method that takes advantage of the Euler and Lagrange perspectives performs better. Materialpoint Solver.JL offers high-performance solutions that are backend independent. We have implemented an efficient version of MPM with Julia and have also flexibly extended it to multi-Gpus platforms. In addition to the built-in computational flow, we also allow users to implement their own computational flow or constitutive model at a fairly low cost.

- **MaterialPointGenerator.jl** - Help users to quickly generate from DEM file for MPM simulation material point, the generated files through the use of simple modifications should and can be applied to other structured grid MPM program.

- **SlopingLocalBaseLevel.jl** - SLBL is a method that can automatically find potential failure surfaces from DEM. We used Julia and Pluto.jl to implement a version suitable for teaching/demonstration purposes, but also to compute using code alone.

 - The organization also stores previously relevant work, as well as related "miscellaneous" content.




## Acknowledgement 👏

This project is sponserd by ‍ **Université de Lausanne**,  **Risk Group (ISTE)**, **Swiss Geocomputing Centre**, and  **China Scholarship Council [中国国家留学基金管理委员会]**.
Many thanks to Prof. Michel Jaboyedoff, Prof. Dr. Yury Podladchikov, Prof. Dr. Marc-Henre Dirron, Dr. Ludovic Rass, Dr. Wyser Emmaual, and Prof. Dr. Gang Mei for their help. ❤

---

<div align=center>
2021-2025 LandslideSIM <br>
Risk Group 🍷 <br>
Universitvé de Lausanne 🇨🇭<br>
</div>