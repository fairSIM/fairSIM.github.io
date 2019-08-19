---
layout: default
---

Structured Illumination Microscopy (SIM) provides a fast and gentle super-resolution approach for
fluorescence microscopy. The *fairSIM project* aims to provide a range of free and open-source
tools for scientists working with SIM.

## The fairSIM ImageJ / FIJI plugin

We provide an open-source implementation of the reconstruction algorithms used for SIM.
It runs as a plugin to the popular image processing software [ImageJ](https://imagej.net/)
and the [FIJI](https://fiji.sc/) package.   

* The latest ready-to-use JAR file of the plugin can be found [here](https://github.com/fairSIM/fairSIM/releases/latest)
* All releases, which might include current beta versions, are [here](https://github.com/fairSIM/fairSIM/releases/)
* The source code is found in our main repository on [github](https://www.github.com/fairSIM/fairSIM)
* There's also a [quickstart manual](https://github.com/fairSIM/fairSIM-documentation/releases/) for the plugin  
* [Screencast videos](./screencasts/) showing how to reconstruct SIM data

If you use fairSIM for your research or education, please cite our *associated publication*:
> M. Müller, V. Mönkemöller, S. Hennig, W. Hübner, T. Huser 
> _Open-source image reconstruction of super-resolution structured illumination
> microscopy data in ImageJ_, Nature Communications, 
> [doi:10.1038/ncomms10980](https://doi.org/10.1038/ncomms10980)

## Current developments

* Various recent development (2016--2019) are summarized in [this talk](https://zenodo.org/record/2649890) from April 2019, given at the 'Focus on Microscopy' conference.  
* Support for _full 3D reconstruction_ is in _beta_. The current implementation can be found
in the [develop-3D-SIM](https://www.github.com/fairSIM/fairSIM/tree/develop-3D-SIM) branch, but 
there are known bugs compromising axial resolution.
* A tightly integrated combination of SLM-based video-rate SIM imaging and fairSIM reconstruction is
coming up.  


## Reference / test datasets

A number of SIM raw data sets can be found in [this repository](https://github.com/fairSIM/test-datasets). They include data from commercial instruments (Delta Vision OMX v4, Zeiss Elyra) and home-build
systems. You can _reprocude all reconstruction_ 
from our [original publication](https://doi.org/10.1038/ncomms10980). 


* [OMX LSEC Membrane 680nm](https://github.com/fairSIM/test-datasets/releases/download/OMXv4-Bielefeld/OMX_LSEC_Membrane_680nm.tif)
* [OMX 200nm-Tetraspecks 680nm](https://github.com/fairSIM/test-datasets/releases/download/OMXv4-Bielefeld/OMX_Tetraspeck200_680nm.tif)
* [OMX U2OS Actin 525nm](https://github.com/fairSIM/test-datasets/releases/download/OMXv4-Bielefeld/OMX_U2OS_Actin_525nm.tif)
* [OMX U2OS Mitotracker 600nm](https://github.com/fairSIM/test-datasets/releases/download/OMXv4-Bielefeld/OMX_U2OS_Mitotracker_600nm.tif)
* [OMX U2OS Tubulin 525nm](https://github.com/fairSIM/test-datasets/releases/download/OMXv4-Bielefeld/OMX_U2OS_Tubulin_525nm.tif)
* [SLM-SIM 200nm-Tetraspeck 680nm](https://github.com/fairSIM/test-datasets/releases/download/SLM-SIM-Bielefeld/SLM-SIM_Tetraspeck200_680nm.tif)
* [TIRF-SIM Tubulin 525nm](https://github.com/fairSIM/test-datasets/releases/download/TIRF-SIM-Georgia/TIRF_Tubulin_525nm.tif)
* [Zeiss Actin 515nm (512x512 px crop)](https://github.com/fairSIM/test-datasets/releases/download/ZeissElyraS1-Wuerzburg/Zeiss_Actin_525nm_crop.tif)
* [Zeiss Actin 515nm](https://github.com/fairSIM/test-datasets/releases/download/ZeissElyraS1-Wuerzburg/Zeiss_Actin_525nm_large.tif)
* [Zeiss Mito 620nm (512x512 px crop)](https://github.com/fairSIM/test-datasets/releases/download/ZeissElyraS1-Wuerzburg/Zeiss_Mito_600nm_crop.tif)
* [Zeiss Mito 620nm](https://github.com/fairSIM/test-datasets/releases/download/ZeissElyraS1-Wuerzburg/Zeiss_Mito_600nm_large.tif)


The reconstruction can be run both using _estimated_ and experimentally determined transfers
functions. Both [parameter files](https://github.com/fairSIM/test-datasets/tree/master/parameters) and
[optical transfer functions](https://github.com/fairSIM/test-datasets/releases/download/Parameters-v1.0/OMX-OTFs.zip) are provided to test this feature.
 

# Contact & Development

The maintainer and lead developer of the fairSIM project is _Marcel Müller_

* [web](https://www.mueller-physics.org): www.mueller-physics.org
* [e-mail](mailto:muellerphysics@gmail.com): muellerphysics@gmail.com
* [Twitter](https://twitter.com/mueller_physics): @mueller_physics
* [ORCID](https://orcid.org/0000-0002-2264-3643): 0000-0002-2264-3643
* [google scholar](https://scholar.google.com/citations?user=N29z1_wAAAAJ)
* [LinkedIn](http://www.linkedin.com/in/mueller-physics): mueller-physics
* [ResearchGate](https://www.researchgate.net/profile/Marcel_Mueller10)
