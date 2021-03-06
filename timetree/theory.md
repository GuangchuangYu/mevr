# Theory

## Introduction

- Many viruses are *measurably evolving*
- This means that if we have sequences sampled over time we can:
  - Root the tree without an outgroup
  - Estimate the rate of evolution
  - Transform the tree into units of time

## Strict and relaxed molecular clocks

- Like many organisms, viruses do not evolve at a constant rate
- The evolutionary rate changes, such that the same branch length may not imply the same amount of time
- Methods need to either tolerate or model this rate variation

## Approaches to obtaining 'time trees'

- Take an unconstrained tree and transform it to follow a clock
  - phytime
  - chronos
  - Least Squares Dating
- Generate a phylogeny from the sequence data directly, which assumes a molecular clock
  - sUPGMA
  - TREBLE
  - Bayesian inference
    - BEAST
    - MrBayes
