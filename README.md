# Datasets for VRU motion prediction

This repo works as a notebook to remind me TODOs while writing the literature review for "A survey for datasets used for VRU ^[vulnerable road user] motion/trajectory prediction". I also train myself using Markdown with the practice of this repo ([MDGuide](https://www.markdownguide.org/basic-syntax/)).


[toc]

## Introduction

All useful points received from literatures will be summarized here with themes. Todos are also listed in the themes. References required.

## Themes

### VRU tracking

Tracking is different from trajectory prediction, although some argued that trajectory prediction could be optional for tracking [<sup>1</sup>](#refer-anchor-1).
Tracking is the task of localizing objects as bounding boxes in image sequences and assigning them an identity-preserving unique ID.
Tracking datasets can be used for trajectory prediction tasks. In general, any datasets contains annotation for road users can be used for trajectory predicition tasks.

### Unimodal v.s. multimodal prediction

- **Unimodal methods** rely on learning the regularity of individual motion from past trajectories to predict future trajectories.

- **Multimodal methods** also examine the influence of environment information. [<sup>2</sup>](#refer-anchor-2)

### Road Safety Report

1. [WHO Global Status Report on Road Safety](https://www.who.int/publications/i/item/9789241565684)

    - [Report](./References/GlobalStatusReportRoadSafety-eng.pdf)

    - Last edition is released in 2018. Next edition is due at the end of 2023.

    - [Summary](https://www.who.int/publications/i/item/WHO-NMH-NVI-18.20) and [data visualization](https://extranet.who.int/roadsafety/death-on-the-roads/) on death on the roads

## Reminders for literature notes

1. Notes are made with Mendeley
2. Color representations:
    - <font style="background:yellow">good ideas</font>
    - <font style="background:lightgreen">good expressions</font>

## References

<div id="refer-anchor-1"></div>
 [1] "Quo Vadis: Is Trajectory Forecasting the Key Towards Long-Term Multi-Object Tracking?", [online], arXiv:2210/07681v2

<div id="refer-anchor-12"></div>
 [2] "Forecasting Human Trajectory from Scene History", [online], 	arXiv:2210.08732v1