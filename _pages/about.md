---
permalink: /
title: "Mahmoud Shaqfa - Science"
layout: home
author_profile: false
hero_text: "Postdoc fellow &mdash; Seminar for Applied Mathematics (SAM), D-MATH"
redirect_from: 
  - /about/
  - /about.html
---

# Welcome

**Mahmoud S. M. Shaqfa**

---

## About

I obtained my Bachelor's degree in Civil Engineering at the Islamic University of Gaza (IUG) in 2014.
Later, I received my Master's in Structural Engineering from the University of Pécs in 2017 (Hungary).
In 2018, I moved to Switzerland to pursue my Ph.D. at École Polytechnique Fédérale de Lausanne (EPFL), conducting research at the Earthquake Engineering and Structural Dynamics (EESD) Laboratory under the supervision of Prof. Katrin Beyer from 2018 to 2022.

After that, I briefly worked as a postdoctoral fellow at EESD for 4 months.
In 2023, after being awarded the prestigious PostDoc.Mobility grant from the Swiss National Science Foundation (SNSF), I moved to the USA to join the van Rees Laboratory (led by Prof. Wim van Rees at MIT).

From February to the end of September 2025, I worked with Prof. Josip Atalić as a scientist at the Croatian Centre for Earthquake Engineering at the University of Zagreb (UniZg).

Currently, I am a postdoc researcher at ETH Zürich (Switzerland) in the Department of Mathematics (D-MATH) at the Seminar for Applied Mathematics (SAM). This position is hosted in the groups of Prof. Ralf Hiptmair and Prof. Habib Ammari.

Soon, I will be joining a tenured Chargé de Recherche (CR) position at CNRS in the Laboratory of Microstructure Studies and Mechanics of Materials (LEM3), Metz, France. Read more in my [CNRS Competition 2026 post]({{ "/posts/2026/06/CNRS-Competition/" | relative_url }})

---

## Contact

- 📧 Email (personal): [msshaqfa@hotmail.com](mailto:msshaqfa@hotmail.com)
<!-- - 📧 Email (academic): [mshaqfa@mit.edu](mailto:mshaqfa@mit.edu) -->
- 📧 Email (academic): [mahmoud.shaqfa@math.ethz.ch](mailto:mahmoud.shaqfa@math.ethz.ch)

---

## Research Theses and Proposals

1. **M.Sc.**:
   [Design of reinforced concrete beams using metaheuristic algorithms](https://link.springer.com/article/10.1007/s00158-019-02252-4)
   *(Prof. Zoltan Orban, PTE, 2018)*

2. **Ph.D.**:
   [Geometrical treatise on the modelling of 3D particulate inclusion-matrix microstructures with an application to historical stone masonry walls](https://infoscience.epfl.ch/record/297175?ln=en&v=pdf)
   *(Prof. Katrin Beyer, EPFL, 2022)*

3. **PostDoc**:
   [Harmonic decomposition of the 3D morphology of surfaces for simulating the growth of soft shells and plates](https://data.snf.ch/grants/grant/211088)
   *(Prof. Wim M. van Rees, MIT, 2024)*

4. **PostDoc**:
   [Manifold harmonics for a high–fidelity spectral–Galerkin solver of shell–like engineering problems](https://data.snf.ch/grants/grant/235509)
   *(Prof. Ralf Hiptmair and Prof. Habib Ammari, SAM, D-MATH, ETH Zurich, 2025)*

---

## Research Works and Interests

During my academic career, I developed an interest in a variety of topics, all of which converge around geometry, shapes, topology, and optimization problems—often with an engineering flavor. These areas demand in-depth knowledge of numerical methods such as Galerkin approaches, Discrete Exterior Calculus, and spectral methods.

**Keywords**: Solid Mechanics, Fractal surfaces, Morphology, Computational geometry, Metaheuristics, Optimization, Fracture mechanics, Masonry structures, Rough contacts, CAD.

---

## Science Gallery

### Manifold harmonics (MH)
This ongoing work focuses on surface parametrization, with further results and details to be presented in due course.
<div style="display: flex; justify-content: center; gap: 20px; text-align: center;">
  <div>
    <img src="/GIFs/Beetle_harmonics.gif" alt="GIF 1" style="height: 300px; object-fit: cover;" />
    <p style="margin-top: 5px;">Harmonic basis (Eigen problem)</p>
  </div>
  <div>
    <img src="/GIFs/Beetle_rec.gif" alt="GIF 2" style="height: 300px; object-fit: cover;" />
    <p style="margin-top: 5px;">Harmonic reconstruction</p>
  </div>
</div>

### Spheroidal harmonics (SOH)
This is from our new paper [1] that generalizes the traditional **spherical** harmonics approach (SH).
<div style="display: flex; justify-content: center; gap: 20px; text-align: center;">
  <div>
    <img src="/GIFs/max_reconstruction_full.gif" alt="GIF 1" style="height: 350px; object-fit: cover;" />
    <p style="margin-top: 5px;">Surface reconstruction of Max Planck's head bust</p>
  </div>
</div>



### Remeshing microstructures of 2D contours

Remeshing of closed contours to generate and parameterize 2D microstructures. In the Figure below, the first two rows show how the contours morph from low to high frequencies (k) and how the number of segments (s) affects the reconstruction; the contours were expanded with a maximum 2<sup>7</sup> harmonics. The last row shows the corresponding FEM mesh for different frequencies and segments to control the mesh refinements.

<figure>
  <img src="https://github.com/eesd-epfl/PIC2FEM/raw/master/refinments_EPFL.svg" alt="Refinement process for PIC2FEM" width="60%">
  <figcaption style="text-align:center">Hierarchical remeshing of EPFL's logo for finite element meshing.</figcaption>
</figure>




### Uniform remeshing of surfaces and contours via the harmonic decomposition approaches

The reconstructed meshes via the harmonic approaches are neither optimal nor uniform. To have a high-quality mesh, we proposed a morphology-preserving meshing approach. This approach uses the analogy of the heat problem to diffuse the surface points equidistantly on the reconstructed surfaces/contours. This work is still under review, and a preprint will be soon available. The following are some of the obtained results:

<div style="display: flex; justify-content: center; gap: 20px; text-align: center;">
  <div>
    <img src="/GIFs/dolfin.gif" alt="GIF 1" style="height: 500px; object-fit: cover;" />
    <p style="margin-top: 5px;">Uniform sampling of the dolphin's 2D contour via the Elliptic Fourier approach</p>
  </div>
</div>


The following is a 3D example for remeshing the above reconstruction of Max Planck's head bust:

<div style="display: flex; justify-content: center; gap: 20px; text-align: center;">
  <div>
    <img src="/GIFs/remeshing_head_bust.gif" alt="GIF 1" style="height: 450px; object-fit: cover;" />
    <p style="margin-top: 5px;">Uniform sampling of 2-manifold (3D surface) via the SOH approach [1]</p>
  </div>
</div>



### Coming soon: `libharmonics`: A high-fidelity high-performance C++ library for harmonic decomposition and spectral Galerkin approaches

This library includes one-to-one Python bindings (API) for all the C++ functionalities implemented. `libharmonics` relies on OpenMP to parallelize some of the critical loops and FFTW3 to accelerate the decomposition processes (FFT).

Some of the supported features of the library are:

1. [Disk harmonics analysis](https://www.sciencedirect.com/science/article/pii/S002199912400826X).
2. [Spheroidal harmonics](https://doi.org/10.1016/j.conbuildmat.2024.138967).
3. [Hemispheroidal harmonics](https://doi.org/10.1016/j.cam.2024.116455).
4. [2D Elliptic harmonics](https://doi.org/10.5075/epfl-thesis-9738).
5. [Morphology-preserving remeshing approaches](https://doi.org/10.1016/j.powtec.2025.121991).
6. Spectral Galerkin approaches for linear and nonlinear elliptic problems (**new**).
7. Solid spherical harmonics expansions (**new**).
8. Solid shell spherical harmonics expansions (**new**).
9. Spectral Ritz solver with AutoDiff functionalities for shape-shifting problems (**new**).
10. Fully spectral Galerkin Boundary Element (BEM) method for embedded particles in a matrix (e.g., Helmholtz, diffusion, and Stokes/elasticity problem kernels) (**new**).
11. Supports adaptive or quasi-uniform quadrature rules, in addition to some traditional integration rules for spheres and disks (**new**).

`libharmonics` is an open-source library (GPLv3) and will be hosted on this repo: [https://github.com/msshaqfa/libharmonics-open](https://github.com/msshaqfa/libharmonics-open).

The current progress:
<div style="display: flex; justify-content: center; gap: 20px; text-align: center;">
  <div>
    <img src="/GIFs/libharmonics_gource.gif" alt="GIF 1" style="height: 450px; object-fit: cover;" />
    <p style="margin-top: 5px;">`libharmonics` progress history.</p>
  </div>
</div>


Main collaborators/groups working on adding new features:
1. ETH Zurich, Seminar for Applied Mathematics (SAM), Peiyang Yu (PhD student), [Prof. Ralf Hiptmair](https://people.math.ethz.ch/~hiptmair/Homepage/index.html).
2. CUHK, Department of Mathematics, [Prof. Gary P.T. Choi](https://www.math.cuhk.edu.hk/~ptchoi/) and his students.
3. EPFL, Lausanne, EESD laboratory, Ignat Lesiv (PhD student), [Prof. Katrin Beyer](https://www.epfl.ch/labs/eesd/).


---
## References

[1] Mahmoud Shaqfa and Wim M. van Rees.
*Spheroidal harmonics for generalizing the morphological decomposition of closed parametric surfaces*.
**Construction and Building Materials**, Vol. 454, 2024, Article 138967.
[https://doi.org/10.1016/j.conbuildmat.2024.138967](https://doi.org/10.1016/j.conbuildmat.2024.138967)


