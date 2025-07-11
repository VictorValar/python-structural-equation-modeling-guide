# Confirmatory Factor Analysis (CFA) - Recommended Cut-off Criteria

This document summarizes the recommended cut-off values for key indices and measures in Confirmatory Factor Analysis (CFA), based on leading psychometric and SEM research.

---

## Model Fit Indices

### Chi-Square Test (χ²)
- **Goal**: Non-significant p-value -> good fit.
- **Caution**: Highly sensitive to sample size; large samples almost always reject the model.

---

### Root Mean Square Error of Approximation (RMSEA)
- **≤ 0.05** -> Close fit.
- **0.05 – 0.08** -> Reasonable fit.
- **0.08 – 0.10** -> Mediocre fit.
- **> 0.10** -> Poor fit.
- **90% Confidence Interval** should ideally include **0.05** in the lower bound.

**Key reference**: Hu & Bentler (1999).

---

### Standardized Root Mean Square Residual (SRMR)
- **≤ 0.08** -> Acceptable fit.
- **≤ 0.05** -> Excellent fit.

**Key reference**: Hu & Bentler (1999).

---

### Comparative Fit Index (CFI)
- **≥ 0.95** -> Good fit.
- **≥ 0.90** -> Acceptable fit.
- **< 0.90** -> Poor fit.

---

### Tucker-Lewis Index (TLI) / Non-Normed Fit Index (NNFI)
- **≥ 0.95** -> Good fit.
- **≥ 0.90** -> Acceptable fit.
- **< 0.90** -> Poor fit.

---

### Goodness-of-Fit Index (GFI)
- **≥ 0.90** -> Acceptable fit.
- **≥ 0.95** -> Good fit.
> **Note**: Some criticize GFI as outdated and sample size dependent.

---

### Adjusted Goodness-of-Fit Index (AGFI)
- **≥ 0.90** -> Acceptable fit.

---

## Parameter Estimates

### Standardized Factor Loadings (λ)
- **≥ 0.50** -> Minimum acceptable.
- **≥ 0.70** -> Ideal.

Loadings below 0.50 suggest weak relationships between indicators and factors.

---

## Validity and Reliability Measures

### Average Variance Extracted (AVE)
- **≥ 0.50** -> Convergent validity is adequate.
- **< 0.50** -> Problematic; suggests that error variance exceeds explained variance.

---

### Composite Reliability (CR)
- **≥ 0.70** -> Acceptable reliability.
- **≥ 0.80** -> Good reliability.

---

### Cronbach’s Alpha (α)
- **≥ 0.70** -> Acceptable internal consistency.
- **≥ 0.80** -> Good.
- **≥ 0.90** -> Excellent.

---

## Discriminant Validity

### Fornell-Larcker Criterion
- **AVE of each construct** should be **greater than the squared correlation** with any other construct:
  
  $
  \text{AVE}_i > (\phi_{ij})^2
  $ -> Ensures constructs are distinct.

---

### Heterotrait-Monotrait Ratio (HTMT)
- **≤ 0.85** -> Conservative threshold.
- **≤ 0.90** -> Lenient threshold.

**Key reference**: Henseler et al. (2015).

---

## Summary Table

| Measure | Recommended Cut-off |
|---------|---------------------|
| RMSEA | ≤ 0.05 (close fit), ≤ 0.08 (reasonable) |
| SRMR | ≤ 0.08 |
| CFI | ≥ 0.95 (good), ≥ 0.90 (acceptable) |
| TLI | ≥ 0.95 (good), ≥ 0.90 (acceptable) |
| GFI | ≥ 0.90 |
| Factor Loadings | ≥ 0.50 (acceptable), ≥ 0.70 (ideal) |
| AVE | ≥ 0.50 |
| CR | ≥ 0.70 |
| Cronbach’s α | ≥ 0.70 |
| HTMT | ≤ 0.85 (conservative), ≤ 0.90 (lenient) |

---

## References

- Hu, L., & Bentler, P. M. (1999). Cutoff criteria for fit indexes in covariance structure analysis. *Structural Equation Modeling*, 6(1), 1-55. [https://doi.org/10.1080/10705519909540118](https://doi.org/10.1080/10705519909540118)
  
- Fornell, C., & Larcker, D. F. (1981). Evaluating structural equation models with unobservable variables and measurement error. *Journal of Marketing Research*, 18(1), 39–50. [https://doi.org/10.2307/3151312](https://doi.org/10.2307/3151312)

- Henseler, J., Ringle, C. M., & Sarstedt, M. (2015). A new criterion for assessing discriminant validity in variance-based SEM. *Journal of the Academy of Marketing Science*, 43, 115-135. [https://doi.org/10.1007/s11747-014-0403-8](https://doi.org/10.1007/s11747-014-0403-8)
- MacCallum, R. C., Browne, M. W., & Sugawara, H. M. (1996). Power analysis and determination of sample size for covariance structure modeling. Psychological Methods, 1(2), 130–149. [https://doi.org/10.1037/1082-989X.1.2.130](https://doi.org/10.1037/1082-989X.1.2.130)

---