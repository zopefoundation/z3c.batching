=======
CHANGES
=======

4.1 (unreleased)
----------------

- Nothing changed yet.


4.0 (2025-04-14)
----------------

- Drop support for ``pkg_resources`` namespace and replace it with PEP 420
  native namespace.


3.1 (2025-04-02)
----------------

- Add support for Python 3.12, 3.13.

- Drop support for Python 3.7, 3.8.


3.0 (2023-02-24)
----------------

- Add support for Python 3.10, 3.11.

- Drop support for Python 2.7, 3.5, 3.6.

- Add support for Python 3.8 and 3.9.

- Drop support for Python 3.4.


2.2 (2018-10-20)
----------------

- Add support for Python 3.6, 3.7 and PyPy3.

- Drop support for Python 2.6 and 3.3.


2.1.0 (2016-06-05)
------------------

- Support Python 3.3 through 3.5.


2.0.1 (2015-11-09)
------------------

- Standardize namespace __init__

2.0.0 (2013-02-25)
------------------

- New feature: Subset batch.
  Sometimes (for performance reasons), even though the user needs
  a batched UI, we want to limit the computation to the
  subset of values actually shown to the user.

- Register `batch.Batch` as named (``"z3c.batching.batch"``) factory.

1.1.0 (2008-11-12)
------------------

- Added a function to build a small neighbourhood list of the current batch,
  from a large batch list. (extracted from z3c.table)

- Really fixed the bug with batches slicing

1.0.1 (2008-09-09)
------------------

- Fixed bug with batches slicing.


1.0.0 (2008-02-18)
------------------

- Initial release.
