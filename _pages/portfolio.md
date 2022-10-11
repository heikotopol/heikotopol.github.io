---
layout: archive
title: ""
permalink: /portfolio/
author_profile: true
---



## Mechanoregulated Redemodeling of Fibrous Tissue

My research deals with the mathematical modeling of biological tissues.
Biological soft tissues are complex structures, which are composed of  multiple components with different functions and properties. 
In the framework of my research I considered tissue models that consist of a mixture of a _ground substance material_ and embedded _collagenous fibers_.
The macroscopic properties of the material result from the elastic properties of the constituents, the geometry of the considered problem, the arrangement of the fibers in the ground substance, and the interplay of the constitutents.

* **Strain-stabilization of collagen to enzymatic degradation:**
In the framework of my research I considered tissue models that consist of a mixture of a _ground substance material_ and embedded _collagenous fibers_.
Motivated by experiments that have observed the strain stabilization of collagen to enzymatic degradation  (see the review article by [Topol et al. (2021d)](https://doi.org/10.1115/1.4052752)),
my work focuses on  fiber models that are applicable to collagenous tissues, which undergo _continuous mechano-sensitive remodeling processes_.
[Topol et al. (2014)](https://doi.org/10.1093/imamat/hxu027) illustrate the complexity of fiber density development for relatively simple deformation scenarios.
The relationship between stress and deformation has then been explored for uniaxial ([Topol et al. (2015)](https://doi.org/10.1007/s10665-014-9771-9)) and biaxial deformation problems ([Topol et al. (2017)](https://doi.org/10.1007/s11043-016-9315-y)).
A study applied the remodeling model to pressurized thick-walled tubes applicable to the modeling of blood vessels ([Topol et al. (2019)](https://doi.org/10.1016/j.euromechsol.2019.103800)).
![Degradation](/images/PMAN3.png)

* **Swelling-induced remodeling processes:** 
In soft biological tissue, swelling is a typical process that affects collagen fiber remodeling. The modeling framework is in the context of large (finite) deformation continuum mechanics in order to address situations in which the swelling causes the tissue to exhibit significant volume change.
I applied the theory of swellable materials to the fiber remodeling theory.
In [Topol et al. (2018)](https://doi.org/10.1007/s10237-018-1043-6), my collaborators and I presented a hyperelastic modeling framework of the combined effects of tissue swelling and
deformation-related collagen renewal in soft fibrous tissue.
 We also had the goal to apply the swellable material models in finite element studies, which simulate the development of cervical tissue during different stages of pregnancy.
The numerical calculations were carried out in an in-house MatLab code,
which had been continuously extended  with the complexity of the investigated problem ([Gou et al. (2020)](https://doi.org/10.1115/1.4045810)).


* **Bounded fiber lifespans:**
In the previously mentioned articles on modeling collagen remodeling, the theoretical upper collagen lifespan was unbounded.
[Topol et al. (2021a)](https://doi.org/10.1016/j.jmbbm.2020.104154) limit this theoretical upper bound of the fiber lifespan to the finite limit, and it has been shown that the presented model can sufficiently describe observations from experiments on strain stabilization.
The follow-up work by [Topol et al. (2021b)](https://doi.org/10.1016/j.mechrescom.2021.103740) elaborates on the interplay between different phenomena in the approach, attainment, and abatement of fiber density minima and maxima. In particular, that article shows how the deferral of stress considerations enables an appreciation of how the collagen density is governed by all of the following: the amount of the overall material deformation, the fiber pre-stretch, and the competing time scales at which the various processes of fiber creation and stretch mediated dissolution act at the microscale.


## Experimental Biomechanics & Mechanobiology

(under construction)


##  Bifurcation of pressurized cylinders

Abdominal aortic aneurysms are responsible for a large number of deaths in industrialized countries.
This motivates many researchers to develop models that capture the formation, development, and rupture of aneurysms.
The geometry, mechanical properties, and numerous biochemical processes play an important role in the formation of dilatations in arteries.
My work studies instabilities in loaded and inflated cylinders with the application to the formation and propagation of aneurysms in arterial wall tissue.


* **Swelling of Isotropic and Fibrous Materials:**
The initiation and propagation of bulging in fiber-reinforced swellable Mooney-Rivlin membranes have been studied by
[Topol et al. (2021c)](https://doi.org/10.1007/s10665-021-10123-5). Further bifurcation modes - prismatic and bending bifurcation - of fiber-reinforced elastic and swellable membranes have been treated by [Al-Chlaihawi et al. (2021)](https://doi.org/10.1177/10812865211058767) and [Topol et al. (2023)](https://doi.org/10.22055/JACM.2022.40949.3677).
<!---
![Degradation](/images/Fig1turnedaNEW.png)
-->

* **Different Natural Configurations and Arrangement of the Constituents**: The natural configuration of the constitutens may differ, for example, because the fiber may posses a certain pre-stretched, or because the fiber are limp and they need to be extended until they fully bear tensile forces. The assumption of perfectly parallel fibers is an idealization, which is applied in various modeling work. If this idealization cannot be applied, then techiques such the _angular integration method_ or _structure tensor_ based methods are used in the modeling. The effect of fiber pre-stretch and fiber dispersion on the initiaion of bulging has been studied in [Topol et al. (2022b)](https://doi.org/10.1007/s10665-021-10123-5).

<!---
-->

## Transport properties of composites

My work on the mechanical behavior of composites deals with wave propagation and heat transfer in anisotropic media.
This research applied different methods such as the _Floquet-Bloch approach_, the _plane wave expansion method_, the _asymptotic homogenization method_, and the _transfer-matrix method_ in order to understand the properties of composites ([Andrianov et al. (2011)](https://doi.org/10.1002/zamm.201000176), [Andrianov et al. (2017a)](https://doi.org/10.1007/s00707-016-1765-4), [Andrianov et al. (2017b)](https://doi.org/10.1016/j.ijheatmasstransfer.2017.03.124), [Andrianov et al. (2018)](https://doi.org/10.1016/j.wavemoti.2017.12.007)).
![Dispersion](/images/RealNEW.png)


## Stress distribution in loaded composites
In composites, an important method to determine the mechanical properties of the material is the pull-out tests of fibers from the matrix. 
The quality of bonding between two constituents has a crucial role in the functionality of the material.
There are numerous factors that lead to imperfect bonding such as cracks, corrosion, or degradation.
Methods that help to understand the development of the mechanical properties with ongoing damage processes guarantee an efficient use of composites.
There are different techniques at account for imperfect bonding between constituents ([Andrianov et al. (2011)](https://doi.org/10.1007/s00419-008-0265-y), [Andrianov et al. (2018)](https://doi.org/10.1016/j.wavemoti.2017.12.007), [Andrianov et al. (2020)](https://doi.org/10.1007/s00707-020-02634-6)).
* **Spring Layer Model:**  A popular model is denoted as the _spring-layer model_, in which springs simulate the bonding conditions between the fibers and the matrix. In this case, bonding is models as a condition in the inter<ins>**f**</ins>ace 
* **Artificial Interphase Layer:** An alternative for modeling imperfect bonding is to introduce one or multiple _artificial inter<ins>**ph**</ins>ase layers_ between two constituents. These layers are taken to be thin in comparison to the thickness of the fibers. The geometry and the elastic properties of the modeling layer define the bonding quality between the fibers and the matrix.



