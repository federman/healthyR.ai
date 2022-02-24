# healthyR.ai 0.0.6

## New Features
1. Fix #132 - Add functions:
-  `hai_kurtosis_vec()`
-  `hai_skewness_vec()`
2. Fix #133 - Add function `hai_distribution_comparison_tbl()`
3. Fix #138 - Add function `hai_get_dist_data_tbl()`
4. Fix #140 - Add function `hai_get_density_data_tbl()`
5. Fix #146 - Add function `hai_density_plot()`
6. Fix #141 - Add function `hai_density_qq_plot()`
7. Fix #139 - Add function `hai_density_hist_plot()`
8. Fix #56 - Add function `hai_histogram_facet_plot()`
9. Fix #178 - Add loadings plots to `pca_your_recipe()` output. Added a parameter
of `.top_n` to get how many vairable loadings you want returned.

## Minor Fixes and Improvements
1. Fix #180 - Move `cli` and `crayon` to Imports from Suggest due to `pillar` 
not importing anymore.
2. Fix #182 - Drop need for `cli`, `crayon`, and `rstudioapi`

## Breaking Changes
None

# healthyR.ai 0.0.5

## New Features
1. Fix #118 - Add functions:
-  `hai_scale_zero_one_vec()`
-  `hai_scale_zero_one_augment()`
-  `step_hai_scale_zero_one()`
2. Fix #119 - Add function: `hai_range_statistic()`

## Minor Fixes and Improvements
None

# healthyR.ai 0.0.4

## Breaking Changes
None

## New Features
1. Fix #108 - Add functions:
-  `hai_winsorized_move_vec()`
-  `hai_winsorized_move_augment()`
-  `step_hai_winsorized_move()`
2. Fix #107 - Add functions:
-  `hai_winsorized_truncate_vec()`
-  `hai_winsorized_truncate_augment()`
-  `step_hai_winsorized_truncate()`

## Minor Fixes and Improvements
None

# healthyR.ai 0.0.3

## Breaking Changes
None

## New Features
1. Fix #61 - Add internal function `hai_data_scale()`
2. Fix #63 - Add internal function `hai_data_impute()`
3. Fix #58 - Add internal function `hai_data_trig()`, Exported Func `step_hai_hyperbolic()`
4. Fix #68 - Add `hai_hyperbolic_vec()` function.
5. Fix #70 - Add `hai_hyperbolic_augment()` function.
6. Fix #75 - Add `hai_fourier_vec()`,`hai_fourier_augment()`,`step_hai_fourier()` functions.
7. Fix #89 - Add `hai_fourier_discrete_vec()`, `hai_fourier_discrete_augment()`, `step_hai_fourier_discrete()`
8. Fix #57 - Add `hai_polynomial_augment()`
9. Fix #60 - Add internal function `hai_data_transform()`
10. Fix #93 - Add internal function `hai_data_poly()`

## Minor Fixes and Improvments
1. Fix #81 - Add process to register s3 methods to work with `tune` objects.

# healthyR.ai 0.0.2

## Breaking Changes
None

## New Features
1. Fix #22 - Add functions:
  +  `hai_kmeans_mapped_tbl()`
  +  `hai_kmeans_obj()`
  +  `hai_kmeans_scree_data_tbl()`
  +  `hai_kmeans_scree_plt()`
  +  `hai_kmeans_tidy_tbl()`
  +  `hai_kmeans_user_item_tbl()`
2. Fix #29 - Add function `pca_your_recipe()`
3. Fix #32 - Add function `hai_kmeans_automl()`
4. Fix #49 - Add function `hai_kmeans_automl_predict()`

## Minor Fixes and Improvements
None

# healthyR.ai 0.0.1

## Breaking Changes
None

## New Features
1. Fix #9 - Add function `hai_control_chart`

## Minor Fixes and Improvments
None

# healthyR.ai 0.0.0.9000

* Added a `NEWS.md` file to track changes to the package.
