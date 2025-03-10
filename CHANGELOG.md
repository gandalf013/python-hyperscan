# Changelog

## [0.1.1] - 2019-05-01

### Fixed

- Fixed segfault ([#10])

## [0.1.0] - 2019-04-13

### Changed

- ``match_event_handler`` will now halt scanning if a truthy (and
  not **None**) value is returned.
- The C extension module is now accessible with
  ``import hyperscan._hyperscan``, and ``hyperscan.version.__version__``
  now returns the Hyperscan library version as opposed to the Python
  package version. ``hyperscan.__version__`` will, however, return the
  Python package version.
- Major packaging update, now using [Poetry] rather than ``setup.py``.
- Replaced [Sphinx] documentation with [MkDocs] and added an initial
  usage guide.
- Replaced [Travis CI] configuration with [Semaphore].


## [0.0.2] - 2018-05-26

Initial release


[#10]: https://github.com/darvid/python-hyperscan/issues/10
[MkDocs]: https://www.mkdocs.org/
[Poetry]: https://poetry.eustace.io/
[Semaphore]: https://semaphoreci.com/
[Sphinx]: http://www.sphinx-doc.org/en/master/
[Travis CI]: https://travis-ci.org/
[0.1.1]: https://github.com/darvid/python-hyperscan/releases/tag/v0.1.1
[0.1.0]: https://github.com/darvid/python-hyperscan/releases/tag/v0.1.0
[0.0.2]: https://github.com/darvid/python-hyperscan/releases/tag/v0.0.2
