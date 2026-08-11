
# Recent Research Activities 

---

My recent research is driven by the ambition to contribute to the predictive understanding of materials by bridging atomistic mechanisms with macroscopic behavior. The main line is to understand how local atomic order governs transport properties, collective dynamics, phase transformations and crystal nucleation and glass formation of various materials from the liquid. This is done by combining first-principles simulations, large-scale molecular dynamics and neutron and X-ray scattering experiments to reveal the microscopic origins of diffusion, viscosity and dynamical heterogeneity. To overcome the limitations of conventional atomistic simulations, machine-learning interatomic potentials and active learning strategies are specifically designed for complex liquid-state phenomena, enabling quantitative studies of nucleation, glass formation and microstructure evolution over unprecedented spatial and temporal scales. One of the goals is now to embed these methodological advances within open, reproducible computational workflows and data-driven research infrastructures, with the broader objective of strengthening the connections between statistical physics, materials science and artificial intelligence.

---

## Atomistic Simulations of Crystal Nucleation

---

Over the past two decades, advances in atomistic simulations have profoundly transformed our understanding of crystal nucleation in metals and alloys. Rather than being viewed as a purely stochastic process described solely by classical nucleation theory, crystallization is now recognized as emerging from the structural fluctuations inherent to undercooled liquids. Increasing evidence indicates that local structural precursors develop prior to nucleation and either facilitate or inhibit the formation of stable crystalline embryos. Nucleation thus results from a subtle competition between crystal-like ordering and topologically incompatible motifs, including icosahedral and Frank–Kasper polyhedral arrangements, which introduce geometrical frustration and may suppress crystallization in favor of glass formation [1]. This modern picture establishes a direct connection between local atomic order, liquid dynamics, thermodynamic stability, and crystallization kinetics, providing a unified framework for understanding—and ultimately predicting—the solidification behavior of metallic systems [2,3].

[1] A. Pasturel, N. Jakse, npj Comput Mater 3, 33 (2017). [DOI](https://doi.org/10.1038/s41524-017-0034-y)

[2] S. Becker, E. Devijver, R. Molinier, N. Jakse, Physical Review B, 102(10), 104205 (2020). [DOI](https://doi.org/10.1103/PhysRevB.102.104205)

[3] B. Shang, N. Jakse, P. Guan, W. Wang,  and J.-l. Barrat, Acta Materialia 246, 118668 (2023). [DOI](https://doi.org/10.1016/j.actamat.2022.118668).

---

## Liquid Dynamics 

---

### Revealing atomic diffusion in liquid alloys through a combination of atomistic simulation and experiments

---

Performed in collaboration with the DLR (German Aerospace Center) within the MATHEUS sounding rocket programme, this study combines microgravity experiments, neutron scattering, and atomistic simulations to quantify interdiffusion in liquid Al–Cu alloys. By exploiting one of the world’s few platforms for fully automated materials experiments in prolonged microgravity, it delivers benchmark diffusion data free from buoyancy-induced convection, providing new insight into mass transport in liquid metals [4]. A search for a universal diffusion-entropy law  reminiscent of a profound structure diffusion relation is currently investigated [5,6]. 

[4] E. Sondermann, N. Jakse, K. Binder, A. Mielke, D. Heuskin,  F. Kargl, and A. Meyer, Phys. Rev. B 99, 24204 (2019). [DOI](https://doi.org/10.1103/PhysRevB.99.024204)

[5] F. Demmel and N. Jakse, Physical Review B 111, L081104 (2025). [DOI](https://doi.org/10.1103/PhysRevB.111.L081104)

[6] F. Demmel, L. Hennet, and N. Jakse, Sci. Rep. 11, 11815 (2021). [DOI](https://doi.org/10.1038/s41598-021-91062-0)

---

### Collective dynamics: First direct evidence of non-acoustic collective modes in a monatomic liquid under extreme conditions

Combining ab initio simulations, machine-learning interatomic potentials, and the Generalized Collective Modes theory, this study uncovers a previously unknown branch of propagating excitations arising from the relative motion between atoms and their local coordination cages. The results redefine our understanding of collective dynamics in simple liquids beyond the conventional hydrodynamic picture.
 
[7] T. Bryk, G. Ruocco, J.-F. Wax, and N. Jakse Commun. Phys. (Nature) 9, 187 (2026). [DOI](https://doi.org/10.1038/s42005-026-02602-x)

---

## Machine Learning for Computational Materials Science

---

### Machine learning interatomic potentials for liquid structure and crystal nucleation

A major research activity focuses on the development of machine learning interatomic potentials (MLIPs) specifically designed for liquid and undercooled materials. Unlike conventional approaches primarily optimized for crystalline phases, our strategy targets an accurate description of the atomic structure and dynamics of liquids over a wide range of thermodynamic conditions. Particular attention is paid to thermodynamic states relevant to transport phenomena, structural relaxation, supercooling and the early stages of crystallization. These MLIPs enable simulations involving millions of atoms over nanosecond time scales while retaining near first-principles accuracy. This computational efficiency opens the way to quantitative investigations of diffusion, viscosity, collective dynamics, dynamic heterogeneity and nucleation mechanisms that remain inaccessible to direct *ab initio* simulations.

<p align="center">
<img width="1143" height="482" alt="MLIP-github" src="https://github.com/user-attachments/assets/f14e66e5-2de6-41f1-86e8-87e70c51e688" />
    <em>General workflow for MLIP construction. </em>
</p>
 
These developments provide the computational foundation for studying crystal nucleation, phase selection and microstructure formation in pure metallic systems [8,9] and alloys [10,11].

<p align="center">
<img width="1188" height="627" alt="Bizot-2-Github" src="https://github.com/user-attachments/assets/81c3e0f1-50c6-4c02-990b-a608c8ff51c6" />
<em> Combining large-scale atomistic simulations with state-of-the-art machine-learned interatomic potentials, this study reveals the microscopic mechanisms governing phase selection during eutectic solidification. The results establish machine-learning molecular dynamics as a powerful tool for investigating nucleation phenomena in technologically important alloys. With permission to reuse from Ref. 11 by American Physical Society.</em>
</p>

[8] N. Jakse, J. Sandberg, L. F. Granz, A. Saliou, P. Jarry, E. Devijver, T. Voigtmann, J. Horbach,  and A. Meyer, Journal of Physics:  Condensed Matter 35, 035402 (2023). [DOI](https://doi.org/10.1088/1361-648X/ac9d7d)

[9] J. Sandberg, T. Voigtmann, E. Devijver,  and N. Jakse, Machine Learning:  Science and Technology 5, 025043 (2024). [DOI](https://doi.org/10.1088/2632-2153/ad450e)

[10] J. Sandberg, T. Voigtmann, E. Devijver,  and N. Jakse, The Journal of Chemical Physics 163 (2025). [DOI](https://doi.org/10.1063/5.0299431)

[11] Q. Bizot and N. Jakse, Physical Review Materials 9, 123404 (2025). [DOI](https://doi.org/10.1103/jwmw-3lds)

### Active Learning for Materials Discovery

By identifying the most informative quantum-mechanical training data, this study shows that accurate prediction of MOF properties can be achieved with a fraction of the computational effort required by conventional approaches. The work establishes active learning as a powerful framework for developing data-efficient machine-learning models and enabling high-throughput discovery of advanced porous materials [12, 13].

<p align="center">
<img width="1092" height="538" alt="Active_learning_Github" src="https://github.com/user-attachments/assets/fd4e793f-15b8-43f5-b1cc-90d28023f564" />
  <em>Active Learning workflow applied to spin-crossover MOF discovery. Permission to reuse from Ref. 13 by the American Chemical Society.</em>
</p>

[12] A. Jose, J. P. A. de Mendonça, E. Devijver, N. Jakse, V. Monbet, and R. Poloni, Data Mining and Knowledge Discovery 38, 420 (2024). [DOI](https://doi.org/10.1007/s10618-023-00951-7)

[13] A. Jose, E. Devijver, N. Jakse,  and R. Poloni, Journal of the American Chemical Society 146, 6134 (2024). [DOI](https://doi.org/10.1021/jacs.3c13687)

### Unsupervised topological learning 

By integrating topological data analysis with unsupervised learning, this study demonstrates that the onset of crystallization can be detected directly from atomistic configurations without prior knowledge of the underlying crystal structure. The proposed framework based on persistence homology within the Topolical Data Analysis offers a general, interpretable, and transferable strategy for studying phase transitions and rare-event phenomena across a wide range of materials [14,15].

<p align="center">
<img width="1501" height="436" alt="Unsupervised_topological learning_Github" src="https://github.com/user-attachments/assets/5dda1992-a23d-4c6b-9fc2-b822dc95520c" />
  <em>Unsupervised topological Learning workflow [15].</em>
</p>

[14] S. Becker, E. Devijver, R. Molinier,  and N. Jakse, Physical Review E 105, 045304 (2022). [DOI](https://doi.org/10.1103/PhysRevE.105.045304)

[15] S. Becker, E. Devijver, R. Molinier,  and N. Jakse, Scientific Reports 12, 3195 (2022). [DOI](https://doi.org/10.1038/s41598-022-06963-5).

### Machine learning for density functional theory: application to transition-metal chemistry 

Combining artificial neural networks with density functional theory, this study delivers significantly improved predictions of adiabatic energy differences in transition-metal complexes while retaining the efficiency of DFT calculations [9]. The approach demonstrates how data-driven models can overcome intrinsic limitations of conventional exchange-correlation functionals, opening new opportunities for computational materials design and molecular discovery, as well as a more reliable baseline for training machine learning interatomic potentials.  

<p align="center">
<img width="1360" height="452" alt="DFT-ML-Github" src="https://github.com/user-attachments/assets/5b27bd20-c8dc-4a8e-b5dd-30c55a3096cb" />
     <em>Machine Learning workflow for training DFT functionals. Permission to reuse from Ref. 16 by the American Chemical Society.</em>
</p>

[16] J. P. Almeida  de Mendonça, L. A. Mariano, E. Devijver, N. Jakse,  and R. Poloni, Journal of Chemical Theory and Computation19, 7555 (2023). [DOI](https://pubs.acs.org/action/showCitFormats?doi=10.1021/acs.jctc.3c00600&ref=pdf)

---

## Enabling reproducible computational materials science across heterogeneous computing platforms

This study introduces a container-based ecosystem that makes complex materials science codes and workflows portable, reproducible, and interoperable from personal computers to Europe’s largest supercomputers. By addressing one of the major challenges of computational research—software reproducibility—it lays the foundations for FAIR, scalable, and collaborative digital materials science [17].

[17] D. Bissuel, L. Orveillon, B. Arrondeau, J.P., Almeida de Mendonça, J. Daubin, ... and N. Jakse, Reproducible container solutions for codes and workflows in materials science. Advanced Engineering Materials, e202503185 (2026). [DOI](https://doi.org/10.1002/adem.202503185)

---
---

**License**

The documentation and figures in this repository are distributed under the
**Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

© 2026 Noël Jakse

---
