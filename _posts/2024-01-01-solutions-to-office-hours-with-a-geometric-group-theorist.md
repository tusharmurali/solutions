---
layout: post
title: "Solutions to *Office Hours with a Geometric Group Theorist*"
tags: group-theory
author:
- Tushar Muralidharan
modified_date: 2024-01-20
---

This is a compilation of my solutions to *Office Hours with a Geometric Group Theorist*, edited by Matt Clay and Dan Margalit. All errors are my own.

## Part 1: Groups and Spaces

### Office Hour 1: Groups

##### Exercise 1

To be formalized:

Crossings always originate from adjacent numbers unless one of the numbers was previously modified by a swap. However, we only consider the numbers up to previous swapping, so the statement holds at every level. Therefore, every permutation can be obtained by adjacent transpositions.

<!-- Consider $\sigma \in S_n$. Let $\sigma_1$ be the transposition corresponding to the highest crossing in the diagram of $\sigma$ (where all the crossings occur at different heights).

Must prove that every permutation can be obtained by adjacent transpositions -->

<!-- Make a diagram of an arbitrary permutation where all the crossings occur at different heights. The uppermost crossing must be one between the lines of adjacent numbers. If a (line corresponding to a) number has not been affected by the first permutation, then it may only cross with an adjacent number. If a number has been affected by the first, then

Something is preserved after each crossing -->
<!-- We prove the statement by induction on the number of crossings in the diagram of an arbitrary permutation (where all the crossings occur at different heights). Diagrams with only 1 crossing correspond precisely to the transpositions $(i \; i+1)$. Assume that any diagram with the  -->