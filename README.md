# Combinatorial Optimisation for Urban Logistics Network Efficiency

**Domain:** Vehicle Routing Problem · Metaheuristics · Operational Decision Support  
**Application:** FMCG retail distribution network (Ofogh Koorosh)

---

## Problem

NP-hard vehicle routing optimisation for a large-scale urban FMCG 
distribution network, where solution quality and computational tractability 
must be balanced at operational scale.

## Algorithm — Three-Stage Architecture

**Stage 1 — Sweep Algorithm**  
Initial route construction by geographic clustering of delivery points. 
Generates a feasible starting solution efficiently.

**Stage 2 — Tabu Search**  
Global exploration with diversification control. Escapes local optima 
by maintaining a tabu list of recently visited configurations.

**Stage 3 — 2-Opt Local Search**  
Route refinement through systematic edge-swap improvement. 
Converges to high-quality solutions from the Tabu Search output.

## Results

Systematic analysis of computational time vs. solution quality trade-offs 
demonstrated tractability at operational scale across the full distribution 
network. Route efficiency improvements validated against benchmark routes.

## Implementation
```
Language : Python
Libraries: NumPy · Pandas · Matplotlib
```
