# Go Basics Cheat Sheet

A 2-page A4 cheat sheet for Python and C/C++ coders starting their first Go project.

It summarises a ~30 minute Go basics presentation I gave to peers at 42 Belgium.

## Contents

| File | Description |
|---|---|
| `go_essentials.pdf` | Ready to read or print |
| `go_essentials.tex` | LaTeX source |

## Topics covered

- **Intro:** what Go is, strengths and weaknesses, running code, packages and imports
- **Basics:** naming and visibility, variables and zero values, numbers, enums, strings and runes, slices, maps, errors
- **Go quirks:** loops, `switch`, pointers, `defer`, small things that won't compile
- **Functions:** signatures, multiple returns and the error convention
- **Structs and methods:** structs, value vs pointer receivers, `NewX` functions

Python and C++98 equivalents are included where useful.

## Building from source

Requires a LaTeX distribution (e.g. TeX Live) or Overleaf.

```bash
pdflatex go_cheatsheet.tex
```

## AI Usage

AI was used to help with the layout and formatting for the cheatsheet while practicing LaTeX syntax.

## License

[CC BY 4.0](LICENSE). Free to share and adapt, as long as credit is given.

Shane Petersen
