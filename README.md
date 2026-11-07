# The irrationality exponent of small-height binary lacunary series is 2

Ruiyi Zhang

## Main result

Let N >= 2 be an integer and let (lambda_j) be a sequence of nonzero rational numbers with
log H(lambda_j) = o(2^j), where H(u/v) = max(|u|, v) for u/v in lowest terms with v > 0. Then

    x = sum_{j >= 0} lambda_j N^(-2^j)

is irrational and has irrationality exponent mu(x) = 2. The height condition cannot be weakened to
log H(lambda_j) <= C 2^j for any constant C > 0.

## Method

The proof uses Padé approximants to the tails sum_{r >= 0} lambda_{k+r} z^(2^r). The two Hankel determinant
families they need satisfy parity recursions, so they are nonzero for all nonzero weights. After the finite prefix of
the series is cleared, the approximants of order n give integer linear forms with height N^((n+1/2) 2^k) and error
N^(-(n+1/2) 2^k), up to factors e^(o(2^k)). Only finitely many orders are used for each target exponent.

## Contents

- `main.pdf`: the manuscript (12 pages).
- `source/main.tex`: LaTeX source (amsart; no other files are needed).
- `SHA256SUMS`: SHA-256 checksums of the files above.

## Build

    cd source
    pdflatex main.tex && pdflatex main.tex && pdflatex main.tex

Built with TeX Live 2026.
