---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "What Determines Food Web Structure?"
subtitle: ""
summary: ""
authors: [Tomas I. Marina, admin]
tags: [github, Stochastic models, Food webs, Ecological Networks ]
categories: []
date: 2022-02-10
lastmod: 2022-02-10T15:12:09-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["ungs2019"]
---

In nature species interact among each other in many ways. The most
common and studied interaction is that between a predator and its prey.
A food web can be defined as a network of interactions that describes
who eats whom in a certain ecosystem and at a certain time of the year.
In any ecosystem, in a terrestrial, freshwater or marine environment,
the so-called food web is comprised by lots of species (hundreds) and
interactions (thousands), showing a complex network of predator-prey
interactions.

In a recent paper in the Journal of Animal Ecology, we studied the
assembly process of food webs, that means how the complex network of
interactions is formed and which are the principal factors that drive
such processes. To put it in simple words, our research question was the
following: what determines the structure of a food web?

![Florida Keys Mangrove Island. CC BY-SA 3.0,
https://en.wikipedia.org/w/index.php?curid=11746362](Red_mangrove-everglades_natl_park.jpg)

Due to previous investigations of colleagues we now know that the
structure of a food web is the result of community assembly, which is a
repeated process of species arrival, colonisation and local extinction.
This implies that there are two major components that determine the
structure of a food web: 1) the composition of species from where
individuals migrate to new habitats, referred to as the regional pool or
metaweb; and 2) a selective process that determines which species can
arrive and persist in the new habitat. We also know that the first to
colonise new habitats are species with a broad diet (i.e. great variety
of prey). Thus, predator-prey interactions are established during the
assembly process that begins the formation of a network of interactions:
the food web "in progress". Added to this, the characteristics of the
habitat (substrate, climatic conditions) and the dispersal capability of
the species are important factors that also control the assembly process
of the food web, determining which species might be able to persist in
time.

![Long Pond Lake at Adirondacks Region. By Original uploader was Mwanner
at en.wikipediaLater version(s) were uploaded by XcepticZP at
en.wikipedia. - Transferred from en.wikipedia, CC BY-SA 3.0,
https://commons.wikimedia.org/w/index.php?curid=4044745](Long_Pond_lake.jpg)

The structure of a food web is ultimately constrained by the species and
potential interactions that exist in the regional pool, that is, the
metaweb. Such metaweb is shaped by evolutionary and biogeographical
processes that imply large spatial and temporal scales, containing many
habitats and communities. Each of the local communities can have
different food web structures, in terms of species and interactions
among them. Some theorists conceive of assembly as a non-Darwinian
selection process, whereby species and particular structures that
destabilise the food web will be lost and stabilising structures will
persist. Therefore, we should expect those stabilising structures to be
over-represented in local food webs compared to the metaweb.


To test the hypothesis that the selective processes are responsible for
food web structure, we created an assembly model, where species migrate
from a regional pool and persist in a theoretical local food web given
at least one prey item available. The model considers
colonisation-extinction and secondary extinctions (i.e. if a species
arrives and none of its prey are present) events constrained by network
structure that is represented by predator-prey interactions. Thus, the
model does not include local selective processes and habitat constraints
that are thought to control the assembly process. Then we compared the
theoretical local food webs created from the assembly model with real
food webs. We hypothesised that, if local processes like stability
determine the food web structure, then we should observe a consistent
difference in the network structural characteristics between real food
webs and those assembled from the model. To test our hypothesis we
compiled 58 real food webs from a variety of regions and ecosystems: 2
marine food webs from Antarctica, 50 freshwater ones from the
Adirondacks region and 6 from an Arthropod community in six islands of
the Florida Keys.

![Schematic diagram of the assembly model: species migrate from the
metaweb to a local food web carrying their potential interactions.
Predators become extinct if none of its prey are
present](MetaWebAssemblyModelFigure.png)

Contrary to our expectations, we found that most structural
characteristics didn't differ between the real and modeled food webs. We
particularly compared properties related to stability, such as
modularity and the frequency of three-species motifs, and habitat
filtering and dispersal limitation, such as topological roles that
characterise how many interactions a species has within their module
and/or between modules (i.e. modules are formed by a group of species
that share more interactions compared to other species). This suggests
that evolutionary and biogeographical processes that are established in
the metaweb are more important and might drive the studied structural
characteristics in a food web than local processes such as habitat
filtering and dispersal limitations. In particular, our study forces us
to re-think the way we approach the study of food web structure. The
network properties that we as ecologists commonly use to shed light on
this aspect might be a by-product of the assembly process already driven
at the metaweb spatial and temporal scales.

More info:
[Check the complete publication here]({{< relref "publication/saravia-2019" >}})

