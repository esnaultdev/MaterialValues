#Metrics & Keylines

## Baseline grid 

Baseline grid values are provided from `@dimen/material_baseline_grid_1x` to `@dimen/material_baseline_grid_20x`.

Half-increments are also available for centering elements, from `@dimen/material_baseline_grid_0.5x` to `@dimen/material_baseline_grid_9.5x`.

It is recommended to use the baseline grid to specify component dimensions.


## Increments

A default value of 56dp for increments is used to specify increment values.
This is specific to this library and not a material design specification, even though it's a common value.
Every dimension relying on increments is provided alongside an `@integer` value so that a custom increment size can be used.

Increment values are provided from `@dimen/material_increment_1x` to `@dimen/material_increment_10x`. 


## Content keylines

| Edge margin | Resource |
| ----------- | -------- |
| Default           | `@dimen/material_content_edge_margin_horizontal`      |
| Secondary content | `@dimen/material_content_secondary_edge_margin_start` |


Secondary content is content placed after some primary content. For example, the text after an avatar in a list.

---

#### See also

- [Raw values](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-layout/values/keylines.xml)

- [Metrics & keylines (Material design)](https://material.google.com/layout/metrics-keylines.html)

