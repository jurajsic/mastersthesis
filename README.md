Here you can find LaTeX source of my [master's thesis](https://is.muni.cz/th/prexv/).
It uses the [fithesis](https://github.com/Witiko/fithesis) document class and [latexmk](https://ctan.org/pkg/latexmk) for generating the thesis.
Just execute `latexmk thesis.tex` to generate the pdf file of the thesis.
Furthermore, in `figures/graphcreator/` you can find the `csv` data and the tex file `main.tex` which I used to generate the plot figures in the thesis.

## Errata
There are some mistakes in the thesis which were found after the submition (thanks goes to Christoph Scholl for noticing them) which are:
- end of p. 21: it should be `depends on the subformula s'(\Phi') in v;, we have v'(s'(\psi_1)) = 1` instead of `depends on the subformula s'(\Phi') in v, we have v(s'(\psi_1)) = 1` (added two single quotation marks),
- page 22, line 15: `v(s'(\psi_2[y'/y]))` instead of `v(s(\psi_2[y'/y]))`,
- page 22, line 20: `depends on s'(\Phi') in v'` instead of `depends on s'(\Phi') in v`.

These mistakes are corrected in this repository.
