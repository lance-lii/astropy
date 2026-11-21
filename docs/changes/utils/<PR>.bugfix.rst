Rounding ``Masked`` arrays with ``decimals`` other than zero now works and
propagates the mask. Previously, the ``round()`` method raised a ``TypeError``,
while ``np.round()`` and ``np.around()``, as well as ``round()`` on a
``MaskedQuantity``, silently dropped the mask. Zero-dimensional masked arrays
also no longer lose their mask when rounded.
