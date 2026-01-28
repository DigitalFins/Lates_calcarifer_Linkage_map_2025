---

# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Code for: Barramundi Linkage Map by Hintzsche et al. 2026
---

Code and supplementary materials for the manuscript ***Genetic linkage map of the Australian barramundi (Lates calcarifer) reveals potential to leverage extreme sex-specific recombination and sequential hermaphrodism for ultimate breeding program control***,
by Jessica Hintzsche, Lorenzo Vincenzo Bertola, David B. Jones, Christie Warburton, Owen Powell, Elizabeth M. Ross, Paul Harrison, Holly Cate, Dean R. Jerry, Ben J. Hayes, Kyall R. Zenger, currently available as a preprint at [https://doi.org/10.21203/rs.3.rs-8400904/v1](https://doi.org/10.21203/rs.3.rs-8400904/v1).


# Decide a graphical abstract, add to home, insert between ()
![ReplaceWithGraphicalAbstract]()

## Structure

In this supplementary material, we cover all the code for data processing and analyses. The code is organised in a step-wise manner that begins with how the input files for Lep-MAP3 were created and then goes into how Lep-MAP3 was used to filter, sort, and then order the markers on chromosomes. I then have a script that pulls all of the highest likelihood runs of each chromosome for each sex into a single map.

### Data preparation

1. [Creating LepMAP3 input files](Github_1.Establishing_family_files.html)
2. [Lep-MAP3 Filtering](Github_2.Lep-MAP3_Filtering_data.html)

### Creating the maps
3. [Lep-MAP3 Separate into chromosomes](Github_3.Lep-MAP3_Separate_chromosomes.html)
4. [Lep-MAP3 Order markers](Github_4.Lep-MAP3_order_markers.html)
5. [Building the maps](Github_5.Building_the_maps.html)

### R and packages version summary

3. [Version summary](example_knitted.html)

Thanks for your interest in our paper, whether it comes from a love for barramundi, aquaculture, or genetics.

For further details on any of the code, please contact me at: [email me](mailto:j.hintzsche@uq.edu.au)!
