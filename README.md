# Phylogenies: how and why to track them in artificial life

[![conference](https://img.shields.io/badge/Tutorial-2024_Artificial_Life_Conference-ff69b4)](https://2024.alife.org/index.html)

Phylogenies (i.e., ancestry trees) group extant organisms by ancestral relatedness to render the history of hierarchical lineage branching events within an evolving system.
These relationships reveal the evolutionary trajectories of populations through a genotypic or phenotypic space.
As such, phylogenies open a direct window through which to observe ecology, differential selection, genetic potentiation, emergence of complex traits, and other evolutionary dynamics in artificial life (ALife) systems.
In evolutionary biology, phylogenies are often estimated from the fossil record, phenotypic traits, and extant genetic information.
Although substantially limited in precision, such phylogenies have profoundly advanced our understanding of the evolution of life on Earth.
In digital systems, we often have the ability to create perfect (or near perfect) phylogenies that reveal the step-by-step process by which evolution unfolds.
However, phylogeny tracking and phylogeny-based analyses are not yet commonplace in ALife.
Fortunately, a number of software tools have recently become available to facilitate such analyses, such as [Phylotrackpy](https://phylotrackpy.readthedocs.io/en/latest/), [DEAP](https://deap.readthedocs.io/en/master/api/tools.html?highlight=history#deap.tools.History), [Empirical](https://empirical.readthedocs.io/en/latest/), [MABE](https://github.com/Hintzelab/MABE), and [hstrat](https://hstrat.readthedocs.io/en/latest/?badge=latest).

Biologists have developed many sophisticated and powerful phylogeny-based analysis techniques.
For example, existing work uses properties of tree topology to infer characteristics of the evolutionary processes acting on a population.
With an understanding of the differences between biology and artificial life, these approaches can be imported into ALife systems.
For example, phylodiversity metrics can be used to detect diversity-maintaining ecological interactions and ongoing generation of significant evolutionary innovations.

## Tutorial outline (tentative)

In addition to introducing phylogenies and their use cases in an artificial life context, we will help participants through the process of incorporating phylogeny tracking into an artificial life system using existing phylogeny tracking software.
We encourage participants to bring their own artificial life system to "hack on", but we will also provide example notebooks (that implement simple example ALife systems) for participants to use.

Outline:

- Intro to phylogenies and lineages
- What can phylogenies do for you?
- Guided coding challenges (incorporating phylogeny tracking into an ALife system + saving and analyzing phylogeny data)
- Discuss potential for those interested in collaborating on a workshop report

## When & Where

This tutorial session is organized as part of the [2024 Conference on Artificial Life](https://2024.alife.org/index.html), held July 22-26 in Copenhagen, Denmark.

Time and room assignment can be found in the conference program: <https://2024.alife.org/program.html>.

### For online participants

We can chat in Meeting Room Sigma (the room's zoom doesn't make for great interaction): <https://discord.com/channels/1123220946686316654/1263957778423349380>

## Workshop report

If a critical mass of participants are interested, we will organize a workshop report reviewing how Phylogenies are currently used by participants' ALife systems as well as open questions / future challenges for phylogenetic analysis in ALife.

## Organizers

- [Emily Dolson](https://cse.msu.edu/~dolsonem/), *Assistant Professor*, Michigan State University
- [Matthew Andres Moreno](https://mmore500.com/), *Postdoctoral Fellow*, University of Michigan
- [Alexander Lalejini](https://lalejini.com/), *Assistant Professor*, Grand Valley State University
- [Jack Garbus](https://jarbus.net/), *Graduate student*, Brandeis University

## Resources

- [Slides](https://github.com/amlalejini/alife-2024-phylo-tutorial/blob/main/2023-alife-phylo-tutorial-slides.pdf)
- Sample of ALife papers that use/review phylogenetic analysis: [papers.md](https://github.com/amlalejini/alife-2024-phylo-tutorial/blob/main/papers.md)
- List of useful software packages for tracking phylogenies in ALife systems: [software.md](https://github.com/amlalejini/alife-2024-phylo-tutorial/blob/main/software.md)

