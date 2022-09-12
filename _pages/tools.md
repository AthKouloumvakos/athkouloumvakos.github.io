---
title: "Developed Tools"
permalink: /tools/
author_profile: true

toc: true
toc_label: "Python Tools list"
toc_sticky: true
toc_icon: "list"  # corresponding Font Awesome icon name (without fa prefix)

---

## PyThea

![image-left]({{ site.url }}{{ site.baseurl }}/assets/images/pythea_icon_small.png){: .align-left} 

{: .text-justify}
PyThea is a newly developed open-source Python software package that provides tools to reconstruct coronal mass ejections (CMEs) and shocks waves in three dimensions, using multi-spacecraft remote-sensing observations. This package has been fully built in Python, with extensive use of libraries available within this language ecosystem. PyThea package provides a web application that can be used to reconstruct CMEs and shock waves. The application automatically retrieves and processes remote-sensing observations, and visualizes the imaging data that can be used for the analysis. The package provides three widely used geometrical models for the reconstruction of CMEs and shocks, namely, the graduated cylindrical shell (GCS) and an ellipsoid/spheroid model. It also provides tools to process the final fittings and calculate the kinematics. The final fitting products can also be exported and reused at any time. The source code of PyThea package can be found in [GitHub](https://github.com/AthKouloumvakos/PyThea) and [Zenodo](https://zenodo.org/record/7042194#.Yx9-RC2B3FY) under the GNU General Public License v3.0.

## Heliospheric Disturbance Propagation model and tool (HDPmt)

{: .text-justify}
The Heliospheric Disturbance Propagation Model & Tool (HDPmt) is a simple geometrical model to describe the propagation and longitudinal extension of a disturbance in the heliosphere and a lightweight tool that can be used to visualize the model results and perform case studies. The application can be used to construct different scenarios by adjusting
the kinematical and geometric parameters of the geometrical model and provides three different modes for the user to explore the connection of the disturbance to the field lines and then to calculate the shock parameters at the connection points. The results of the model are visualized into publication-quality figures that can be downloaded as portable network graphic (PNG) files. The source code of HDPmt package can be found in [GitHub](https://github.com/AthKouloumvakos/HDPmt) under the GNU General Public License v3.0.