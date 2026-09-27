# Real Analysis Notes

These are my notes on analysis, in five parts. Part I is undergraduate real analysis, from the real numbers and metric spaces up through the Riemann-Stieltjes and Lebesgue integrals. Parts II to V go on to complex analysis, measure theory and Hilbert spaces, Fourier analysis, and functional analysis.

The compiled book is [real-analysis-notes.pdf](real-analysis-notes.pdf), a little under 1,000 pages.

## Contents

**Part I. Foundations of analysis**

1. Preliminaries: sets, functions, induction, and cardinality
2. The real and complex number systems
3. Basic topology and metric spaces
4. Numerical sequences and series
5. Limits and continuity
6. Differentiation
7. The Riemann-Stieltjes integral
8. Sequences and series of functions
9. Some special functions
10. Functions of several variables
11. Integration of differential forms
12. The generalized Riemann integral
13. The Lebesgue theory

**Part II. Complex analysis**

14. Preliminaries to complex analysis
15. Cauchy's theorem and its applications
16. Meromorphic functions and the logarithm
17. The Fourier transform
18. Entire functions
19. The gamma and zeta functions
20. The zeta function and the prime number theorem
21. Conformal mappings
22. An introduction to elliptic functions
23. Applications of theta functions

**Part III. Measure theory, integration, and Hilbert spaces**

24. Measure theory
25. Integration theory
26. Differentiation and integration
27. Hilbert spaces: an introduction
28. Hilbert spaces: several examples
29. Abstract measure and integration theory
30. Hausdorff measure and fractals

**Part IV. Fourier analysis**

31. The genesis of Fourier analysis
32. Basic properties of Fourier series
33. Convergence of Fourier series
34. Some applications of Fourier series
35. The Fourier transform on R
36. The Fourier transform on R^d
37. Finite Fourier analysis
38. Dirichlet's theorem

**Part V. Functional analysis**

39. L^p spaces and Banach spaces
40. L^p spaces in harmonic analysis
41. Distributions: generalized functions
42. Applications of the Baire category theorem
43. Rudiments of probability theory
44. An introduction to Brownian motion
45. A glimpse into several complex variables

Each section states the definitions and theorems with full proofs and then goes through worked examples, around 1,300 of them over the whole book. There are a lot of pictures, especially in the complex analysis part (contours, branch cuts, conformal maps, surface plots). Sections end with exercises: problems from the standard textbooks, plus extra ones that go from routine to hard.

## Building the PDF

The book is `real-analysis-notes.tex`, and the macros and plot styles are in `preamble.tex`. You need a TeX Live that includes pgfplots and tikz-3dplot. Run pdflatex three times so the table of contents and the cross-references come out right:

```bash
pdflatex real-analysis-notes.tex
pdflatex real-analysis-notes.tex
pdflatex real-analysis-notes.tex
```
