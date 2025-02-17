.. _changes:

Changelog
=========

Version 0.3.0
-------------

Released on: 2022/03/28

DOI: https://doi.org/10.5281/zenodo.6390020

New data:

* Add the Sierra Negra volcano point cloud topography data (`#23 <https://github.com/fatiando/ensaio/pull/23>`__)
* Add the Osborne Mine aeromagnetic data (`#22 <https://github.com/fatiando/ensaio/pull/22>`__)

This release contains contributions from:

* Leonardo Uieda

Version 0.2.0
-------------

Released on: 2022/02/18

doi:`10.5281/zenodo.6143350 <https://doi.org/10.5281/zenodo.6143350>`__

**Breaking change**:

* Version datasets individually instead of using the entire data bundle and
  versioning all datasets based on the module name. This means that functions
  won't have to be repeated and updating one dataset doesn't mean copying all
  of the others along with it (since the collection would be new). Versions are
  now specified as a required ``version`` argument in all ``fetch_*``
  functions. (`#18 <https://github.com/fatiando/ensaio/pull/18>`__)

Maintenance:

* Replace Google Analytics for Plausible so our docs have a more privacy-friendly analytics solution (`#17 <https://github.com/fatiando/ensaio/pull/17>`__)
* Use `Dependente <https://github.com/fatiando/dependente>`__ to capture dependencies on CI (`#16 <https://github.com/fatiando/ensaio/pull/16>`__)
* Use `build <https://github.com/pypa/build/>`__ instead of ``setup.py`` (`#15 <https://github.com/fatiando/ensaio/pull/15>`__)
* Remove unused files from the source distributions (`#14 <https://github.com/fatiando/ensaio/pull/14>`__)

This release contains contributions from:

* Santiago Soler
* Leonardo Uieda

Version 0.1.0
-------------

Released on: 2021/12/23

doi:`10.5281/zenodo.5784203 <https://doi.org/10.5281/zenodo.5784203>`__

First trial release of Ensaio. Used for testing our systems and implementation.

This release contains contributions from:

* Leonardo Uieda

..
    Version 1.0.0
    -------------

    *Released on: 2021/12/17*

    doi:`10.5281/zenodo.5784203 <https://doi.org/10.5281/zenodo.5784203>`__

    **First major release of Ensaio** (Portuguese for "rehearsal"), a Python
    package for downloading open-access sample datasets for Geoscience. It taps
    into the curated data collection in
    `github.com/fatiando/data <https://github.com/fatiando/data>`__ and uses
    `Pooch <https://www.fatiando.org/pooch>`__ to manage downloading and caching
    the data files.

    Data version: `fatiando/data v1.0.0 <https://github.com/fatiando/data/releases/tag/v1.0.0>`__

    Data archive: `10.5281/zenodo.5167357 <https://doi.org/10.5281/zenodo.5167357>`__

    Includes:

    * GPS velocities for the Alpine region
    * Single-beam bathymetry of the Caribbean
    * Airborne magnetic survey of Britain
    * Global gravity, geoid height, and topography grids
    * LiDAR point cloud of the Trail Islands in British Columbia, Canada
    * Ground gravity of Southern Africa

    **This is the only release that will be compatible with Python 3.6.**
    Later releases will require Python >= 3.7.

    This release contains contributions from:

    * Leonardo Uieda
