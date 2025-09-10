---
title: "Metrics"
date: 2025-09-03
draft: false
---

We define the _SNCF_ metric `$d_{SNCF}$` on $\R^2$. We use polar coordinates on `$\R^2$`, with `$O$` as the origin and coordinates `$(r, \theta)$` with `$r > 0$` and `$\theta\in [0, 2\pi)$` for points in `$\R^2\setminus\{O\}$`. The metric is defined by:

* `$\circ$` `$d_{SNCF}(O,O) =0$`.
* `$\circ$` `$d_{SNCF}(O, (r, \theta)) = d_{SNCF}((r, \theta), O) = r$`.
* `$\circ$` `$d_{SNCF}((r_1, \theta_1), (r_2, \theta_2)) = \begin{cases}
      |r_2 - r_1|,\ \textrm{if $\theta_1 = \theta_2$,} \\
      r_2 + r_1,\ \textrm{ if $\theta_1 \neq \theta_2$,}
    \end{cases}$`

Let `$d_E$` denote the usual Euclidean metric on `$\R^2$`.

1. Prove that `$d_{SNCF}$` is a metric.
2. __Prove or disprove:__ If a set `$U\subset \R^2$` is open in the topology corresponding to `$d_{SNCF}$`, then `$U$` is open in the topology corresponding to `$d_E$`.
3. __Prove or disprove:__ If a set `$U\subset \R^2$` is open in the topology corresponding to `$d_E$`, then `$U$` is open in the topology corresponding to `$d_{SNCF}$`.
