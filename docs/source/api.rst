API
===

The yaml file consists of 3 key parameters and 4 default parameters:

1. Key Parameters
----------------
These parameters can be changed for different scenarios.

.. code-block:: console

    | Parameters  |  Explanation|
    ------------------------------------------------------------------------------------------------------------
    1) lanes_ids  :  the index of lanes in a road whose direction is from left to right, such as [0, 1, 2];
    ------------------------------------------------------------------------------------------------------------
    2) lws        :  the width of these lanes, its values are ranged from 2.7m to 3.9m, such as [3.5, 3.5, 3.7];
    ------------------------------------------------------------------------------------------------------------
    3) ratios_HDV :  the ratio of human-driven vehicles in the road, which are ranged from 0.~1, such as [.7, .2, .5]
    ------------------------------------------------------------------------------------------------------------


2. Default Parameters
----------------
These parameters should not be changed.

.. code-block:: console

    | Parameters  |  Explanation|
    ------------------------------------------------------------------------------------------------------------
    1) selected_marginal_ts   :
    ------------------------------------------------------------------------------------------------------------
    2) selected_marginal_ts   :
    ------------------------------------------------------------------------------------------------------------
    3) two_dim_paras          : 
    ------------------------------------------------------------------------------------------------------------
    4) two_dim_paras_AV       :
    ------------------------------------------------------------------------------------------------------------


.. autosummary::
   :toctree: generated
   lumache
