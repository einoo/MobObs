# RAOE: Reduced adaptive observation experiment

This document presents the open source code for the reduced adaptive observation experiment. 

Here can also be a supplementary to support the conclusions of the paper. 

`No, supplementary will be submitted along the manuscript. Here is mainly for the open source code and data`. 

## Lorenz-96 Model && SPEEDY-LETKF model

## Chapters Sections Directories

## Motivation

Assimilate at every 10 time step. 

I have examined the adaptive observations by 40-variable Lorenz-96 model: 
$$\frac{dx_i}{dt}=(x_{i+1}-x_{i-2})x_{i-1} - x_i + F,$$ 
where $F$ is the forcing and the variable $x_i$ is taken to be periodic: $x_{i+n} = x_{i}$.
In this study, we set $n=40$ and $F=8$.  The
nodes numbered from 1 to 20 lie over the ocean, and those from 21 to 40 lie over
the land (Fig. 1).

<p align="center" width="100%">
<img src="./fig/Lorenz96_40D.png" width="40%">
</p>
<p align="center" width="100%">
<em>Figure 1. An illustration on the 40-variable Lorenz-96 model </em>
</p>

All land sites receive observations very 6 hours; while there are no routine observations all over the ocean. 
The objective of this study is to find one fixed observation all over the ocean. 
The study can be extended to multiple fixed observation network over the global by an intermediate scale atmospheric general circulation model. 

## Background

## Literature review

## Experimental settings

## Results and discussions

## Summary
