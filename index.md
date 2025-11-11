---
layout: default
---
![Banner](assets/banner.jpg){: width="1500"}


### About
I’m **Florian Vincent**, a third-year PhD student working at the intersection of scientific machine learning (SciML) and computational mechanics. I’m supervised by [Filippo Masi](https://filippo-masi.github.io/), [Vincent Acary](https://tripop.inrialpes.fr/people/acary/) and [Jérôme Malick](https://membres-ljk.imag.fr/Jerome.Malick/) at Université Grenoble Alpes, France.
My background is in applied mathematics and numerical modelling, and I’m keen on combining data-driven methods with first-principles physics to build reliable models of materials and systems. I used to be an engineering student in Ensimag (Grenoble, France), and I came back to the city in 2022 for my PhD thesis.

See my [Google Scholar profile](https://scholar.google.com/citations?hl=fr&user=4XZI-C8AAAAJ) for publications.

### Research
My work focuses on bridging physics-based modelling and machine learning, with a special interest in constitutive modelling and learning frameworks that respect thermodynamics.

#### Thermodynamically consistent SciML

In particular, I explore how to **learn constitutive laws directly from data**, while enforcing the first and second laws of thermodynamics by construction -- ensuring that the models remain physically meaningful even when tackling complex inelastic or non-associated materials.
This is done through the use of Hemipotentials, which make a key ingredient to generalize the concept of a pseudo-potential of dissipation to non-associated material behaviours.

#### Distributionally Robust Optimisation

I also developed the open-source library [**SkWDRO**](https://skwdro.readthedocs.io/latest/) for Wasserstein distributionally robust optimisation. The library’s pre-print is available on ArXiv: [arXiv:2410.21231](https://arxiv.org/abs/2410.21231).
SkWDRO provides Python tools that integrate with PyTorch, enabling robust machine-learning models under distribution shifts.

#### Current topics

I’ve been picking growing interest in the larger field of **Scientific Machine Learning (SciML)** in general lately.
Most of my research relies on **Python** and **Julia**, and I love working across both ecosystems — using **PyTorch** and **JAX** in Python, and **Lux.jl** with **Reactant.jl** in Julia — to prototype and test new ideas.

A central ingredient in my work, as well as my current favorite topic to study, is **automatic differentiation**.
It plays a crucial role in **data-driven constitutive modeling**, where we often describe materials through **thermodynamic potential functions**.
By differentiating these potentials, we can directly obtain stress–strain relations or evolution equations for internal variables, while enforcing the first and second laws of thermodynamics by construction.
This makes autodiff not just a computational convenience, but an essential tool for expressing and discovering physically consistent models.


### Teaching
- [M2 SSD](https://formations.univ-grenoble-alpes.fr/fr/catalogue-2021/master-XB/master-mathematiques-et-applications-IAQKA8QE/parcours-statistique-et-sciences-des-donnees-ssd-IB9H3QIQ.html), Optimisation for operation research (w/ Anatoli Juditsky), practical sessions
- [M1 SSD](https://formations.univ-grenoble-alpes.fr/fr/catalogue-2021/master-XB/master-mathematiques-et-applications-IAQKA8QE/parcours-statistique-et-sciences-des-donnees-ssd-IB9H3QIQ.html), Data Sciences
- M1 Ensimag, Optimisation (w/ Hamza Ennaji), practical sessions
- L3 [Fourier institute](https://www-fourier.univ-grenoble-alpes.fr/fr), Numerical Methods (w/ Clément Jourdana)

### Conferences
- ROADEF
- SMAI MODE Days (poster session)
- COMPLAS

### Beyond Research
When I’m not immersed in stress–strain curves or SciML pipelines, I enjoy playing volleyball — it’s the perfect way to clear the head and recharge.

### Contact
- Email: florian (dot) vincent (at) univ-grenoble-alpes (dot) fr
- Office: 143, LJK Lab, IMAG Building, Grenoble

*NB: many thanks to [Waïss Azizian](https://wazizian.fr/) for helping me with this template.*
