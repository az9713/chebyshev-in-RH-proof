# From Chebyshev to the Riemann Hypothesis

This project accompanies an eight-page mathematical tutorial inspired by Dirac’s YouTube video [How Chebyshev’s Method Led to a Proof of the Riemann Hypothesis](https://www.youtube.com/watch?v=7TNj74KXtBA). The tutorial follows the explainer from Chebyshev’s integer-divisibility argument to the use of lattice indices in the Alpöge–Claude proof.

The [HTML companion](index.html) documents how the tutorial was made. It maps each of the seven video chapters to the corresponding PDF pages, identifies the four captured frames, and explains how the numerical examples and derivations were checked.

## What the tutorial covers

- The prime-power staircase and the explicit formula linking it to zeros of the Riemann zeta function
- Ramp smoothing and the exact linear correction involving the Euler–Mascheroni constant
- Landau’s one-sided argument and the extension from an eventual upper bound to bounds on windows of scales
- The binomial and factorial comparisons, the lattice-index inequality, and the role of theta lifts

The YouTube transcript supplied the chapter structure and examples. [Michael Rubinstein’s working guide, version 2](https://www.math.uwaterloo.ca/~mrubinst/alpoge_claude_grh/zeta-paper_v2.pdf) supplied the details of the window argument and the roadmap for the arithmetic bound. The guide takes its central arithmetic inequality from the Lean development. [Alpöge’s announcement](https://alpo.ge/remark.pdf) and the [independent Lean verification statement](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/) document the proof and its verification.

## Live HTML pages

- [From Chebyshev to the Riemann Hypothesis](https://az9713.github.io/chebyshev-in-RH-proof/tutorial.html) is the full tutorial with the derivations, four video frames, and two plots. [HTML source](tutorial.html)
- [How the Chebyshev tutorial was made](https://az9713.github.io/chebyshev-in-RH-proof/) documents the transcript, chapter mapping, frame capture, and mathematical checks. [HTML source](index.html)

Both HTML files can also be downloaded and opened in a browser.
