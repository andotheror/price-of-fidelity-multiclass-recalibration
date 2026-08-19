# The Price of Fidelity: Minimax Multiclass Online Recalibration

## Abstract

An online recalibrator observes a multiclass probability forecast, issues a new forecast, and then observes the outcome. It must become calibrated without losing much Brier score relative to the original forecasts. A recent binary result establishes exponent three, up to logarithms, for calibration error $\varepsilon$ and average excess loss $\varepsilon^2$. For $K$ classes, existing algorithms give the upper exponent $K+1$, but no matching lower bound was known. We prove a sharper Pareto lower bound. For every fixed $K$, if average excess Brier loss is at most $\beta$, then an oblivious truthful instance forces expected canonical calibration at least 

$$c_K\min\\{1,(T\beta^{(K-1)/2})^{-1/2}\\}-C_K\sqrt{\beta}.$$

 Consequently, $(\varepsilon,\varepsilon^2)$ multiclass recalibration needs $\Omega_K(\varepsilon^{-(K+1)})$ rounds. Combined with recent upper bounds, this establishes the fixed-$K$ minimax horizon up to logarithmic factors. The proof introduces a dimension-matched martingale argument. A fractional Burkholder moment converts adaptive bin occupancies into fluctuation, while a $d$-dimensional lattice transport inequality shows that concentrating truthful hints into fewer forecast bins costs squared loss. The result holds for randomized learners and extends to losses that are strongly proper in Euclidean norm.

## Keywords

online calibration, recalibration, Brier score, multiclass, minimax lower bounds, martingale methods, proper losses

## Files

- `main.pdf`, `supplement.pdf`
- `main.tex`, `supplement.tex`
- `references.bib`
- `aistats2027.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `supplement.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
