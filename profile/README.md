# ElectroMagnetic Simulation in Geophysics

**emsig** are open-source codes to simulate electromagnetic data. Their main targets are geophysical applications (exploration and monitoring, engineering, environmental), but they are by no means limited to that. Currently there are two main codes, **empymod** and **emg3d**. The former is a 3D code for layered media, the latter is a low-memory multigrid solver for 3D media. Both are written in **Python** and released under the permissive Apache-2.0 license. The main website is [emsig.xyz](https://emsig.xyz).


## 💻 Main code repositories

- ▶️ [empymod](https://github.com/emsig/empymod): Full 3D electromagnetic modeller for 1D VTI media
- ▶️ [emg3d](https://github.com/emsig/emg3d): A multigrid solver for 3D electromagnetic diffusion
- ▶️ [libdlf](https://github.com/emsig/libdlf): Library of Digital Linear Filters


## 📖 Introduction to Controlled-Source Electromagnetic Methods

The following repo contains notebooks to reproduce with **empymod** all numerical examples of the book
- **Introduction to Controlled-Source Electromagnetic Methods: Detecting Subsurface Fluids**  
  *Ziolkowski and Slob, 2019* (Cambridge University Press; ISBN: [9781107058620](https://www.cambridge.org/9781107058620))  
  ▶️ [csem-ziolkowski-and-slob](https://github.com/emsig/csem-ziolkowski-and-slob)  


## 📄 Publications

The repo ▶️ [publications](https://github.com/emsig/publications) contains a list of publications related to the codes. The following a list with the repos for the most important articles, all fully reproducible:

- **Towards an open-source landscape for 3-D CSEM modelling**  
  *Werthmüller, D., R. Rochlitz, O. Castillo-Reyes, and L. Heagy*, 2021 ([10.1093/gji/ggab238](https://doi.org/10.1093/gji/ggab238))  
  ▶️ [3d-csem-open-source-landscape](https://github.com/emsig/3d-csem-open-source-landscape)

- **Fast Fourier transform of electromagnetic data for computationally expensive kernels**  
  *Werthmüller, D., W.A. Mulder, and E.C. Slob*, 2021 ([10.1093/gji/ggab171](https://doi.org/10.1093/gji/ggab171))  
  ▶️ [article-TDEM](https://github.com/emsig/article-TDEM)

- **A tool for designing digital filters for the Hankel and Fourier transforms in potential, diffusive, and wavefield modeling**  
  *Werthmüller, D., K. Key, and E. Slob*, 2019 ([10.1190/geo2018-0069.1](https://doi.org/10.1190/geo2018-0069.1))  
  ▶️ [article-fdesign](https://github.com/emsig/article-fdesign)

- **An open-source full 3D electromagnetic modeler for 1D VTI media in Python: empymod**  
  *Werthmüller, D.*, 2017 ([10.1190/geo2016-0626.1](https://doi.org/10.1190/geo2016-0626.1))  
  ▶️ [article-geo2017](https://github.com/emsig/article-geo2017)
