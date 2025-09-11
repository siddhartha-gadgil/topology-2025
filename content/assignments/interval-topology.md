---
title: "Interval Topology"
date: 2025-09-17
draft: false
---

Let `$(A, \leq)$` be a **totally ordered** set. For `$p, q\in A$`, we define the open intervals `$(p, q)$`, `$(-\infty, p)$` and `$(p, \infty)$` as `$(p, q) = \{x\in A : p < x, x < q\}$`, `$(-\infty, p) = \{x\in A : x < p\}$`, and `$(p, \infty) = \{x\in A : p < x\},$` where in the first case we assume `$p < q$`.

1. Show that if `$A$` has at least two elements, the collection of subsets of `$A$` given by `$\{(p, q): p,q \in A, p <q \}\cup \{(-\infty, p): p\in A\}\cup \{(p, \infty): p \in A\}$` forms a base for a topology on `$A$`. We call this the *interval topology*.
2. Suppose `$A$` and `$B$` are totally ordered sets with at least two elements and `$f: A \to B$` is a strictly increasing surjective function. Show the `$f$` is continuous with respect to the interval topologies on `$A$` and `$B$`.
3. Let `$A$` be a totally ordered set and `$B \subset A$` be a subset with at least two elements. We consider the total order on `$B$` obtained by restricting the order on `$A$`. **Prove or disprove:** The interval topology on `$B$` is the subspace topology with respect to the interval topology on `$A$`.
