# BO_plus_TMM
This is a notebook uses Bayesian optimization to design antireflective thin film stacks based on the transfer matrix method (TMM).

The TMM package and the tutorial code are from this [repo](https://github.com/sbyrnes321/tmm). The optimization code comes from facebook's [Ax](https://ax.dev/tutorials/gpei_hartmann_service.html) with the service API. The refractive index data are from the [refractive index info](https://refractiveindex.info/?shelf=main&book=ZrO2&page=Wood) database.

To avoid local minimum, the thin film sequence and materials are pre-selected to be high/low index stacks, and the optimization is only done on the layer thickness.

A free reference AR thin film optimization website: https://lightmachinery.com/optical-design-center/thin-film-designer/.
