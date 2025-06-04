# LaTeX Typography Guide

A collection of typography guidelines and conventions for writing documents in LaTeX. This guide combines established typographical practices with style preferences developed for my research group.

## Contents

The guide covers topics including:
- Mathematical text and environments
- Working with units
- Proper use of multiplication symbols
- Table formatting with decimal alignment
- Correct typesetting of constants (Euler's number, differential signs)
- Function names and mathematical operators
- Quotation marks and punctuation
- Automatic bracket sizing
- Chemical notation
- Kröger-Vink defect notation

## Files

- `latex_typography_guide.tex` - Main document source
- `lab_notes.sty` - Custom style package for formatting
- `kroger_vink.sty` - Package for Kröger-Vink notation
- `Bibliography.bib` - References
- `user_commands.tex` - Custom commands (if present)

## Building

To compile the document:

```bash
pdflatex latex_typography_guide.tex
bibtex latex_typography_guide
pdflatex latex_typography_guide.tex
pdflatex latex_typography_guide.tex
```

## Requirements

The document requires the following LaTeX packages:
- `tufte-handout` document class
- `siunitx` for units
- `mhchem` for chemical formulae
- `amsmath` for mathematical notation
- And various other standard packages

The `kroger_vink` package is included in this repository. It is also available separately at https://github.com/bjmorgan/kroger-vink

## Licence

This work is licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this material for any purpose, including commercially, as long as you provide appropriate attribution.

## Attribution

If you use or adapt this work, please provide attribution such as:

> "LaTeX Typography Guide" by Benjamin J. Morgan, licensed under CC BY 4.0. 
> Available at: https://github.com/bjmorgan/latex_typography_guide

## Contact

Benjamin J. Morgan  
Department of Chemistry, University of Bath
