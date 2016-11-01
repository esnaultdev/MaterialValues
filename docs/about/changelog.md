
# Dev branch

- Change package name from `blue.aodev.materialvalues` to `material.values`

**Typography**

- Add text color values for disabled and hint text
- Rename typography colors

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
- Rename `@dimen/material_button_fab_edge_margin_*` to `@dimen/material_button_fab_edge_margin`

**Cards**

- Add corner radius value
- Rename `@dimen/material_card_title_block_small_padding_[top|bottom]` to `@dimen/material_card_title_block_small_padding_vertical`
- Delete `@dimen/material_card_title_block_small_padding_bottom_last_block`, use the vertical padding value
- Fix large title block's bottom padding value
- Rename `@dimen/material_card_media_area_shrunk_*` to `@dimen/material_card_media_area_framed_*`
- Rename `@dimen/material_card_media_area_in_title_size_*` to `@dimen/material_card_media_area_framed_size_*`

**Chips**

- Rename `@dimen/material_chip_simple_remove_icon_*` to `@dimen/@dimen/material_chip_deletable_remove_icon_*`
- Split `@dimen/material_chip_simple_label_horizontal_padding` into start and end padding
- Add simple chip padding after icon

**Dialogs**

- Delete some content values (duplicate of list specs)
- Fix `@dimen/material_dialog_actions_side_by_side_padding_*` values

**Grid lists**

- Delete `@dimen/material_grid_list_header_footer_text_area_margin_end_before_icon`

**Menus**

- Add missing vertical padding and font values

**Steppers**

- Remove desktop-only values
- Almost every remaining value has been renamed
- Add missing button and overview margin values


----

# 1.0.1 (2016-10-24)

- Change package name from `blue.aodev.materialspecs` to `blue.aodev.materialvalues`

----

# 1.0 (2016-10-19)

- Initial release

