---
layout: home
---

**Name:** Kevin Zhu  
**Email:** UCSD_EMAIL@ucsd.edu

**Section:** DSC 180A D13, Analysis of High Dimensional Neural Data  
**Mentor:** Mikio Aoi

**What is the most interesting topic covered in your domain this quarter?**  
Representational geometry was the most interesting topic for me. Before this quarter, I thought of the brain one neuron at a time, but RSA and CKA showed me that the pattern across a whole population can matter more than any single neuron. Our decoding results backed this up: the best single unit decoded grating orientation at around 0.6 accuracy, while the full population reached 0.99. Kriegeskorte & Wei's idea that many different sets of tuning curves can produce the same geometry also changed how I think about comparing brain regions.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
I would like to study how the representation of grating orientation changes as you move up the mouse visual hierarchy, from V1 to higher areas like VISal. Specifically, I want to test whether geometry changes in a consistent way between regions, and whether those changes follow single-unit tuning or happen even when tuning gets weaker. I would use the MNIST network as a check first, since we know its ground truth, before applying the same analysis to the Allen Neuropixels data across many sessions instead of just one or two.

**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**  
I would switch from standard MNIST to rotated MNIST, as the project intended. Rotation angle is a circular variable like grating orientation, so it would make the network a much closer match to the Allen data. I would also verify our summaries on held-out data and repeat the analysis over several trained networks, since our current results come from a single network and a single random seed.

**What other techniques would you be interested in using in your project?**  
I would like to try shape metrics like Procrustes and CCA-based distances across more than two regions, since they give a proper distance between representations. I am also interested in methods that model activity over time, such as GPFA, because our Q1 work summed spikes over each whole trial and ignored timing. Finally, I would like to look at topological methods, since the lecture on topology versus geometry suggested that two representations can be shaped alike even when their distances differ.
