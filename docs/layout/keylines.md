#Metrics & Keylines

## Baseline grid 

<img class="figure" src="../../images/layout_metrics_baseline.png" alt="Baseline grid"/>

Baseline grid values are provided as multiples:

- `@dimen/material_baseline_grid_1x`
- `@dimen/material_baseline_grid_2x`
- ...
- `@dimen/material_baseline_grid_19x`
- `@dimen/material_baseline_grid_20x`

Half-increments are also available for centering elements:

- `@dimen/material_baseline_grid_0.5x`
- `@dimen/material_baseline_grid_1.5x`
- ...
- `@dimen/material_baseline_grid_8.5x`
- `@dimen/material_baseline_grid_9.5x`

It is recommended to use the baseline grid to specify component dimensions.


## Increments

<img class="figure-large" src="../../images/layout_metrics_incremental.png" alt="Increments"/>

Increment values are provided as multiples:

- `@dimen/material_increment_1x`
- `@dimen/material_increment_2x`
- ...
- `@dimen/material_increment_9x`
- `@dimen/material_increment_10x` 

A default value of 56dp for increments is used to specify increment values.
Every dimension relying on increments is provided alongside an `@integer` value so that a custom increment size can be used.



## Content keylines

<img class="figure" src="../../images/layout_metrics_keyline_list.png" alt="Increments"/>

1. `@dimen/material_content_edge_margin_horizontal`
2. `@dimen/material_content_secondary_edge_margin_start`


---

#### See also

- [Raw values](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-layout/values/keylines.xml)

- [Metrics & keylines (Material design)](https://material.google.com/layout/metrics-keylines.html)

