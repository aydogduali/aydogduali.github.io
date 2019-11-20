---
layout: post
title: FESOM/DART interface is out!
category: blog
tags: [english, outreach]
---
## FESOM/DART interface is out!

Data Assimilation Research Testbed (DART) now has an interface to a triangular mesh ocean
circulation model, FESOM. We have already published our collaborative work between CMCC and NCAR,
[here](https://doi.org/10.5194/npg-25-537-2018). Now, the interface between FESOM and DART is out
under Manhattan release of DART. The interface initially developed under Lanai release and relevant
modifications for Manhattan release are done during my visit at NCAR in August 2019. We used FESOM
v1.4 for the development. It shouldn't be difficult use the interface in more recent versions of
FESOM and modify it for other triangular mesh ocean models.

You can reach the code and documentation under the github repository of DART, [here](https://github.com/NCAR/DART/tree/master/models/FESOM).

Below is a supplementary video for the article showing the RMS of difference in salinity an
assimilation-free experiment (top) and an experiment assimilating synthetic ferrybox observations
(bottom) against the nature run between Jan 1, 2009 and Jan 8, 2009

![](/pics/INO_FB001_2009_SAL.gif){:height="714px" width="640px"}

Let us know if you are interested how to use the FESOM/DART interface.


