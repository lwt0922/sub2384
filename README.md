# icml2026-rebuttal-submission2384
# Supplemental Figures for Submission 2384 Rebuttal
## 📌 Part 1: Responses to Reviewer y83s

### Figure R1: The "Double Curse" Test ($N=1000, D=2000, K=10$)
*Referenced in response to Q1 (L1). Demonstrates our Aggregation method's robust $\mathcal{O}(1)$ performance in extreme high-dimensional sparse regimes where up to 99.5% of input dimensions are pure noise, overcoming the distance metric collapse that plagues Pairwise matching.*
![Figure R1](figure_r1.png)

### Figure R2: Robustness to Proxy/Noisy Confounders ($K=10$)
*Referenced in response to Q2. Illustrates that our Aggregation strategy matches the strong resilience of complex Pairwise/One-vs-All constraints against unobserved/noisy confounding, but achieves this without the prohibitive $\mathcal{O}(K^2)$ combinatorial bottleneck.*
![Figure R2](figure_r2.png)

### Figure R3: Mechanism Heterogeneity Stress Test
*Referenced in response to L2. Explicitly maps the boundary conditions of our shared manifold hypothesis. It confirms that our shared models excel when a structural foundation exists ($\eta < 1$), but correctly highlights that cross-family extrapolation degrades when causal mechanisms become fundamentally disjoint ($\eta = 1$).*
![Figure R3](figure_r3.png)

---

## 📌 Part 2: Responses to Reviewer H8X7
### Table R1: Empirical Comparison with Traditional Baselines
*Referenced in response to Reviewer H8X7 (Q1). Traditional methods degrade severely in high-dimensional, multi-treatment regimes.*

| Method | Medium-Scale ($K=4$) | Large-Scale ($K=20$) |
| :--- | :--- | :--- |
| KNN Matching | 2.612 | 16.844 |
| IPW (Multinomial) | 1.012 | 2.478 |
| Base Model (Unadjusted) | 0.796 | 1.029 |
| **Ours (Aggregation, $\alpha^*$)** | **0.722** | **0.989** |

### Figure A: Empirical Proof of Convergence (Gradient Descent vs. Grid Search)
*Referenced in response to Q2. Proves that our 1D Grid Search precisely locates the global optimum $\alpha^*=0.50$.*
![Figure A](Figure_R1.jpg)

### Figure B: Strict Optimal $\alpha^*$ Comparison at Extreme Scale (K=100)
*Referenced in response to Q4. Demonstrates the severe vulnerability of pairwise constraints and the superiority of our Aggregation method.*
![Figure B](Figure_R2.jpg)

### Figure C: The Corrected True Geodesic Interpolation
*Referenced in response to Q4. The corrected geodesic path perfectly passes through the origin and flawlessly intersects all intermediate topological nodes.*
![Figure C](Figure_R3.jpg)






