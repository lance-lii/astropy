The ``var`` and ``std`` methods of ``Quantity``, as well as ``np.var``,
``np.std``, ``np.nanvar`` and ``np.nanstd`` applied to quantities, now
support the ``mean`` argument added in NumPy 2.0. The mean can be given
in any unit compatible with that of the quantity.
