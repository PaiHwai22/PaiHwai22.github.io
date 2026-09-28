# github.io
Pai Hwai's MDS Portfolio

## Build Instructions

Clone the repository:

```bash
git clone https://github.com/PaiHwai22/PaiHwai22.github.io.git
cd PaiHwai22.github.io
```

Install the Python environment:

```bash
uv sync
```

Restore the R environment:

```bash
R
```

Then inside R:

```r
renv::restore()
q()
```

Render the website from the repository root:

```bash
uv run quarto render
```

The rendered website will be created in the `docs/` folder.