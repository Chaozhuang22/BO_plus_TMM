# BO_plus_TMM
This is a notebook uses Bayesian optimization to design antireflective thin film stacks based on the transfer matrix method (TMM).

The TMM package and the tutorial code are from this [repo](https://github.com/sbyrnes321/tmm). The refractive index data are from the [refractive index info](https://refractiveindex.info/?shelf=main&book=ZrO2&page=Wood) database.

To avoid local minimum, the thin film sequence and materials are pre-selected to be high/low index stacks, and the optimization is only done on the layer thickness.
