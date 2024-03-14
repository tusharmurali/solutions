---
layout: post
title: "Solutions to *Groups, Graphs and Trees*"
tags: group-theory
author:
- Tushar Muralidharan
modified_date: 2024-01-20
---

This is a compilation of my solutions to *Groups, Graphs and Trees* by John Meier. All errors are my own.

## Chapter 1: Cayley's Theorems

### Exercise 1.10

- ($1 \Rightarrow 2$) Since trees are connected, there is a reduced edge path between any two vertices $v$ and $w$. We must show that this reduced edge path is unique. Suppose that $\{v,e_1,v_1,\ldots,v_{n-1},e_m,w\}$ and $\{v,e_1',v_1',\ldots,v_{n-1}',e_n',w\}$ are two distinct reduced edge paths between $v$ and $w$. Take the smallest $i$ such that either $e_i \neq e_i'$ or $v_i \neq v_i'$. Consider the subpaths $\{v_{i-1},e_i,v_i,\ldots,v_{m-1},e_m,w\}$ and $\{v_{i-1}',e_i',v_i',\ldots,v_{n-1}',e_n',w\}$. However, since $v_{i-1} = v_{i-1}'$, reversing one of these paths and then concatenating them produces a cycle, which is a contradiction. 
- ($2 \Rightarrow 3$) If removing an edge $e \in E(\Gamma)$ doesn't disconnect the graph, then if ${\rm E{\small NDS}}(e) = \{v,w\}$, there is a reduced edge path $\{v,e_1,v_1,\ldots,v_{n-1},e_n,w\}$ not involving $e$. However, the path ${v,e,w}$ is a reduced edge path, which is a contradiction.
- ($3 \Rightarrow 4$) Since the graph is connected, each vertex has valence at least one. First we will show that 

Clearly $\#V(\Gamma)$ sd. The condition in 3 implies that $\Gamma$ is simple, and that every edge $e$ is the only edge connecting th
- ($4 \Rightarrow 1$) 