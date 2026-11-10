---
layout: home
---

**Name:** Kevin Zhu  
**Email:** kez016@ucsd.edu

**Section:** DSC 180A D13, Analysis of High Dimensional Neural Data  
**Mentor:** Mikio Aoi

**What is the most interesting topic covered in your domain this quarter?**  
Representational geometry was the most interesting topic for me. I've always enjoyed those abstract-type of math subjects(I'm even minoring in math). Specifically about the brain, rep. geo is really unique because in my mind, neurons occupy a 3 dimensional space but the true pattern behind them could be much higher dimensioned-and that's just so cool to me, that our brains somehow work in a higher dimension than we can actually comprehend. 

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
I would like to study how the representation of grating orientation changes as you move up the mouse visual hierarchy, from V1 to higher areas like VISal. Specifically, I want to test whether geometry changes in a consistent way between regions, and whether those changes follow single-unit tuning or happen even when tuning gets weaker. I would use the MNIST network as a check first, since we know its ground truth, before applying the same analysis to the Allen Neuropixels data across many sessions instead of just one or two.

**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**  
Right now, our Q1 Project only compares the MNIST network's layers to each other, so there really isn't any link to the brain. I would change this by showing the network the same drifting grating images the mice saw, then comparing each layer's RDM directly with the RDMs from VISp and VISal. That would let us test whether earlier layers match V1 better and later layers match VISal better, instead of just assuming it. I would also add Poisson-like noise to the network's activity before running the analysis, since real neurons are noisy and our current network isn't.

**What other techniques would you be interested in using in your project?**  
I think one of our current flaws in our approahces is that we are ignoring the time aspect when it comes to these analysis(eg. change over time). Thus, I am also interested in methods that model activity over time, such as GPFA(I remember this from DSC120), because our Q1 work summed spikes over each whole trial and ignored timing. Finally, I would like to look at topological methods, since the lecture on topology versus geometry suggested that two representations can be shaped alike even when their distances differ.
