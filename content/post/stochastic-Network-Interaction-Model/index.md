---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Stochastic Network Interaction Model"
subtitle: ""
summary: ""
authors: []
tags: 
- github 
- Stochastic models  
- Food webs
- Ecological Networks
- Old posts


categories: []
date: 2017-07-31
lastmod: 2020-02-08T09:31:00-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "TopLeft"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [ "UNGS2019"]
---

# SNIM

This is a C++11 implementation of a stochastic multispecies model. The model has multiple applications to investigate the relationship between ecological interactions (competition, predation) and diversity. It involves a discrete definition of individuals belonging to a given set of species. The dynamics are essentially probabilistic at the microscopic scale, but it leads to recognizable macroscopic patterns both in space and time. The model in is actual version is spatially implicit but a spatially explicit version is planned (never did it). You can find the source code at: <https://github.com/lsaravia/snim>


A more complete definition of the model can be found in:  

1. Sole, R. V, Alonso, D. & Mckane, A. (2002). Self-organized instability in complex ecosystems. Philos. Trans. R. Soc. Lond. B. Biol. Sci., 357, 667–681 <https://royalsocietypublishing.org/doi/10.1098/rstb.2001.0992>


And check this presentation to see an application of the model <https://www.doi.org/10.13140/RG.2.2.17020.33929>.