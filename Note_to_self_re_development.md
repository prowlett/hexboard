# Developer notes

Files uploaded to CTAN are:
- `hexboard.ins`
- `hexboard.dtx`
- `hexboard.pdf`
- `README.md`

Put these in a subdirectory `hexboard/` then zip this subdirectory for upload.

Don't edit `hexboard.sty` directly. Its source, and the source for `hexboard.pdf` are in `hexboard.dtx`. N.B. `hexboard.tex` does nothing but hold the documentation code that was eventually put in `hexboard.dtx`.

Make `hexboard.sty` by running `latex hexboard.ins`.

Then make `hexboard.pdf` by running `pdflatex hexboard.dtx`.

