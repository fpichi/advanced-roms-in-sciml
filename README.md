# advanced-roms-in-sciml
Material for the "Advanced reduced order models in scientific machine learning" course, Academic Year 2025-2026. Ph.D. course offered by SISSA.


This course aims to provide a wide overview on novel strategies combining ideas from Reduced Order Modeling (ROM) and Scientific Machine Learning (SciML). The main goal is to investigate the great potential and the possible limitations of state-of-the-art methodologies to efficiently retrieve solutions of parametrized PDEs for computational mechanics problems.
Designed for students and researchers with a background in numerical methods and machine learning, the course provides both lectures and hands-on practical sessions to developing efficient, data-driven models for complex physical systems. 

We begin with an introduction to scientific machine learning, covering key principles of neural network architectures such as feedforward (FFN) and convolutional neural networks (CNN), along with back-propagation and optimization techniques. Then, we investigate their usage in combination with Reduced Order Models, discussing the limitations and benefit of traditional projection-based ROMs and their novel extensions following the data-driven and non-intrusive paradigm.

Subsequent modules are devoted to more advanced machine learning architectures and more specific tasks. In particular, we focus on (i) complex geometries to address real-world applications, (ii) ad-hoc strategies to perform extrapolation and prediction for time-dependent problems, and (iii) operator learning to generalize the surrogate modelling setting in the infinite dimensional context. 

Specifically, we explore Graph Neural Networks (GNNs) and related strategies to embed geometrical bias and information in the learning phase to obtain more consistent and accurate results when dealing with complex and parametrized domains. 

Time-dependent problems are addressed via several methodologies, trying to capture with different assumptions the evolution of a dynamical system. Examples of techniques that will be discussed are Sparse Identification of Nonlinear Dynamics (SINDy), Neural Ordinary Differential Equations (NODEs), Latent Dynamics (LD), Dynamic Mode Decomposition (DMD), and Operator Inference (OpInf).

Finally, Neural Operator learning, introducing powerful new paradigms such as Deep Operator Networks (DeepONet) and Fourier Neural Operators (FNO) are presented as a way to learn mappings between function spaces.

We will employ several open source packages: [FEniCS](https://fenicsproject.org/download/archive/), [RBniCS](https://www.rbnicsproject.org/), [MLniCS](https://github.com/MLniCS/MLniCS), [GCA-ROM](https://github.com/fpichi/gca-rom), and [GFN](https://github.com/Oisin-M/GFN), allowing the students to generate new benchmarks to test different methodologies and investigate the properties of each technique. The tutorials will run on the cloud service provided by Google Colab, so that no local installation is required. 

Info and updates can be found at the GitHub page: https://github.com/fpichi/advanced-roms-in-sciml



| Day | Time | Type | Room | Topic |
|----------------------------------|----------------------------------|----------------------------------|----------------------------------|----------------------------------|
| Tue 9 June 2026 |  11-13  | Lecture  | 134 | **Introduction to Scientific Machine Learning** |
| Tue 9 June 2026 |  14-16  | Lecture | 134 | _FFN, CNN, backpropagation, optimization_ |
| Thu 11 June 2026 |  11-13  | Lecture  | 134 | **From projection based to data-driven ROMs** |
| Thu 11 June 2026 |  14-16  | Lecture | 134 | _RBniCS to MLniCS_ |
| Fri 19 June 2026 |  11-13  | Lecture  | 134 | **GNNs based architectures 1** |
| Fri 19 June 2026 |  14-16  | Lecture | 134 | _GCA-ROM, GFN, MeshGraphNet_ |
| Tue 23 June 2026 |  11-13  | Lecture  | 134 | **GNNs based architectures 2** |
| Tue 23 June 2026 |  14-16  | Lecture | 134 | _GCA-ROM, GFN, MeshGraphNet_|
| Thu 25 June 2026 |  11-13  | Lecture  | 134 | **Time-dependent problems and Neural Operators** |
| Thu 25 June 2026 |  14-16  | Lecture | 134 | _Sindy, NODEs, DMD, OpInf, DeepONet, FNO_ |
