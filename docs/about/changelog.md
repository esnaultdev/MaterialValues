
# Dev branch

- Change package name from `blue.aodev.materialvalues` to `material.values`

**Typography**

- Add text color values for disabled and hint text
- Rename `@color/material_typography_black_high_contrast` to `@color/material_typography_primary_text_color_dark`
- Rename `@color/material_typography_black_low_contrast` to `@color/material_typography_secondary_text_color_dark`
- Rename `@color/material_typography_white_high_contrast` to `@color/material_typography_primary_text_color_light`
- Rename `@color/material_typography_white_low_contrast` to `@color/material_typography_secondary_text_color_light`

**Icons**

- Add size values.

**Metrics & keylines**

- Add baseline grid multiples 21 to 25
- Add half increments from 0.5 to 4.5
- Delete specific baseline grid multiples 28, 30 and 35

**Responsive UI**

- Add number of content hierarchy levels


**Bottom navigation**

- Rename `@dimen/material_bottom_nav_bar_shifting_action_active_icon_padding_vertical` to `@dimen/material_bottom_nav_bar_shifting_action_inactive_icon_padding_vertical`

**Buttons**

- Delete `@dimen/material_button_persistent_footer_height`, use `@dimen/material_button_touch_target_height_minimum` instead
- Rename `@dimen/material_button_raised_corner_radius` to `@dimen/material_button_corner_radius`

**Buttons: FAB**

- Delete `@dimen/material_button_fab_mini_icon_size`, use `@dimen/material_button_fab_icon_size` instead
- Rename `@dimen/material_button_fab_edge_margin_horizontal` to `@dimen/material_button_fab_edge_margin`
- Rename `@dimen/material_button_fab_edge_margin_vertical` to `@dimen/material_button_fab_edge_margin`

**Cards**

- Add corner radius value
- Rename `@dimen/material_card_title_block_small_padding_top` to `@dimen/material_card_title_block_small_padding_vertical`
- Rename `@dimen/material_card_title_block_small_padding_bottom` to `@dimen/material_card_title_block_small_padding_vertical`
- Delete `@dimen/material_card_title_block_small_padding_bottom_last_block`, use the vertical padding value
- Fix large title block's bottom padding value
- Rename "shrunk" media area values to "framed"
- Rename "in_title" media area sizes to "framed"

----

# 1.0.1 (2016-10-24)

- Change package name from `blue.aodev.materialspecs` to `blue.aodev.materialvalues`

----

# 1.0 (2016-10-19)

- Initial release

