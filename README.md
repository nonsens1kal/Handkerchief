# Handkerchief v0.1

These are the source files for Handkerchief, a set of large-scale LaTeX notes on
mathematics, structured after Evan Chen's
[An Infinitely Large Napkin](https://github.com/vEnhance/napkin).

## About

Handkerchief is a collection of mathematical notes covering real analysis,
abstract algebra, number theory, and combinatorics, with more to
come. Definitions and theorem statements are complete and precise, and proofs
are written out in full with explicit labeling and a clean logical flow.

## Download

You can download the most recent PDF from the releases page (link to be added).

## Code

The project can be compiled on a system supporting `latexmk` and `biber`, with a
sufficiently recent version of TeX Live. Simply run `latexmk`.

For continuous preview while writing, run `latexmk -pvc`. To compile a single
chapter, use `\includeonly` in `main.tex`.

Pull requests are welcome! You can also send corrections directly to me.
