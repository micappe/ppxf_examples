# pPXF Jupyter Examples

**pPXF: Full Spectrum Fitting with Photometry for Stars and Galaxies**

[<img src="https://users.physics.ox.ac.uk/~cappellari/images/ppxf-logo.svg" height="100">](https://users.physics.ox.ac.uk/~cappellari/software/#sec:ppxf)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/micappe/ppxf_examples/main)
[![PyPI version](https://img.shields.io/pypi/v/ppxf.svg)](https://pypi.org/project/ppxf/)
[![arXiv](https://img.shields.io/badge/arXiv-2208.14974-orange.svg)](https://arxiv.org/abs/2208.14974)
[![DOI](https://img.shields.io/badge/DOI-10.1093/mnras/stad2597-green.svg)](https://doi.org/10.1093/mnras/stad2597)

Usage examples in [Jupyter Notebook](https://jupyter.org/) for the procedure
`pPXF` originally described in [Cappellari & Emsellem (2004)](http://adsabs.harvard.edu/abs/2004PASP..116..138C),
substantially upgraded in [Cappellari (2017)](http://adsabs.harvard.edu/abs/2017MNRAS.466..798C)
and with the inclusion of photometry and linear constraints in
[Cappellari (2023)](https://ui.adsabs.harvard.edu/abs/2023MNRAS.526.3273C).

`pPXF` extracts the galaxy stellar and gas kinematics, stellar population and
gas emission by fitting a set of templates to an observed spectrum, or to a
combination of a spectrum and photometry (SED), via full-spectrum fitting.

One can run the Jupyter notebooks without installing anything by clicking on the
binder button above. Just note that the code will run much faster on your
local computer.

## Documentation

Read the full `pPXF` documentation [HERE](https://pypi.org/project/ppxf/)

## Attribution

If you use this software for your research, please cite at least
[Cappellari (2023)](https://ui.adsabs.harvard.edu/abs/2023MNRAS.526.3273C),
or additionally some of the `pPXF` papers given in the documentation. The BibTeX entry for the
paper is:

```bibtex
@ARTICLE{Cappellari2023,
    author = {{Cappellari}, M.},
    title = "{Full spectrum fitting with photometry in PPXF: stellar population
        versus dynamical masses, non-parametric star formation history and
        metallicity for 3200 LEGA-C galaxies at redshift $z\approx0.8$}",
    journal = {MNRAS},
    eprint = {2208.14974},
    year = 2023,
    volume = 526,
    pages = {3273-3300},
    doi = {10.1093/mnras/stad2597}
}
```
