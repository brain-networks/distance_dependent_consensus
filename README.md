# distance_dependent_consensus
generate distance dependent consensus networks from structural connectivity data

This code is similar to the approach used in [this paper](https://www.mitpressjournals.org/doi/abs/10.1162/netn_a_00075) to construct group-averaged networks from single-subject sparse structural connectivity data.

Specifically, we impose a distance-dependent consistency threshold on structural networks. The net effect is that group-averaged networks generated using this approach will tend to have many more long-distance connections than networks generated using uniform consistency thresholds.

If you use this code please cite:
> Betzel, R. F., Griffa, A., Hagmann, P., & Mišić, B. (2019). Distance-dependent consensus thresholds for generating group-representative structural brain networks. Network neuroscience, 3(2), 475-496.
