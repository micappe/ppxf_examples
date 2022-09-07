pPXF Jupyter Examples
=====================

**pPXF: Full Spectrum Fitting with Photometry for Stars and Galaxies**

.. image:: http://www-astro.physics.ox.ac.uk/~cappellari/software/ppxf_logo.svg
    :target: https://www-astro.physics.ox.ac.uk/~cappellari/software/#ppxf
    :width: 100
.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/micappe/ppxf_examples/main
.. image:: https://img.shields.io/pypi/v/ppxf.svg
    :target: https://pypi.org/project/ppxf/
.. image:: https://img.shields.io/badge/arXiv-1607.08538-orange.svg
    :target: https://arxiv.org/abs/1607.08538
.. image:: https://img.shields.io/badge/DOI-10.1093/mnras/stw3020-green.svg
    :target: https://doi.org/10.1093/mnras/stw3020

Usage examples in `Jupyter Notebook <https://jupyter.org/>`_ for the procedure
``pPXF`` originally described in `Cappellari & Emsellem (2004) <http://adsabs.harvard.edu/abs/2004PASP..116..138C>`_,
substantially upgraded in `Cappellari (2017) <http://adsabs.harvard.edu/abs/2017MNRAS.466..798C>`_
and with the inclusion of photometry and linear constraints in
`Cappellari (2022) <https://ui.adsabs.harvard.edu/abs/2022arXiv220814974C>`_.


``pPXF`` extracts the galaxy stellar and gas kinematics, stellar population and
gas emission by fitting a set of templates to an observed spectrum, or to a
combination of a spectrum and photometry (SED), via full-spectrum fitting.

One can run the Jupyter notebooks without installing anything by clicking on the
binder button above. Just note that the code will run much faster on your
local computer.

Documentation
-------------

Read the ``pPXF`` documentation `HERE <https://pypi.org/project/ppxf/>`_

Attribution
-----------

If you use this software for your research, please cite at least
`Cappellari (2022) <https://ui.adsabs.harvard.edu/abs/2022arXiv220814974C>`_,
or additionally some of the ``pPXF`` papers above. The BibTeX entry for the
paper is::

    @ARTICLE{Cappellari2022,
        author = {{Cappellari}, M.},
        title = "{Full spectrum fitting with photometry in ppxf: non-parametric
            star formation history, metallicity and the quenching boundary from
            3200 LEGA-C galaxies at redshift $z\approx0.8$}",
        journal = {MNRAS submitted},
        eprint = {2208.14974},
        year = 2022,
        doi = {10.48550/arXiv.2208.14974}
    }

