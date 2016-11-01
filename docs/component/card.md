# Card

## Elevation

| Name | Resource |
| ---- | -------- |
| Elevation (resting) | `@dimen/material_card_elevation_resting` |
| Elevation (raised)  | `@dimen/material_card_elevation_raised`  |


## Layout

<img class="figure" src="../../images/components_card_layout.png" alt="Card layout"/>

1. `@dimen/material_card_edge_margin`
2. `@dimen/material_card_gutter`
3. `@dimen/material_card_corner_radius`

*Note that the gutter and the edge margin have the same value behind the scenes, if you want to use only one.*

## Title

### Small

<img class="figure" src="../../images/components_card_title_small.png" alt="Card small title"/>

1. `@dimen/material_card_title_block_padding_horizontal`
2. `@dimen/material_card_title_block_small_padding_vertical`
3. `@dimen/material_card_title_block_small_height`

| Text  | Resource |
| ----- | -------- |
| Title    | `@dimen/material_card_title_block_small_text_size`    |
| Subtitle | `@dimen/material_card_title_block_subtitle_text_size` |


### Large

<img class="figure" src="../../images/components_card_title_large.png" alt="Card large title"/>

1. `@dimen/material_card_title_block_padding_horizontal`
2. `@dimen/material_card_title_block_large_padding_top`
3. `@dimen/material_card_title_block_large_subtitle_margin_top`
4. `@dimen/material_card_title_block_large_padding_bottom`
5. `@dimen/material_card_title_block_large_padding_bottom_last_block`

| Text  | Resource |
| ----- | -------- |
| Title    | `@dimen/material_card_title_block_large_title_text_size` |
| Subtitle | `@dimen/material_card_title_block_subtitle_text_size`    |


## Supporting text

<img class="figure" src="../../images/components_card_supporting_text.png" alt="Card supporting text"/>

1. `@dimen/material_card_supporting_text_padding_horizontal`
2. `@dimen/material_card_supporting_text_padding_top`
3. `@dimen/material_card_supporting_text_padding_bottom_last_block`
4. `@dimen/material_card_supporting_text_padding_bottom`

Text size: `@dimen/material_card_supporting_text_text_size`.


## Actions

<img class="figure" src="../../images/components_card_actions_horizontal.png" alt="Card actions horizontal"/>

1. `@dimen/material_card_actions_row_padding`
2. `@dimen/material_card_actions_action_gutter_horizontal`

<img class="figure" src="../../images/components_card_actions_vertical.png" alt="Card actions vertical"/>

1. `@dimen/material_card_actions_row_padding`
2. `@dimen/material_card_actions_action_gutter_vertical`

<img class="figure" src="../../images/components_card_actions_icons.png" alt="Card actions icons"/>

1. `@dimen/material_card_actions_row_padding`
2. `@dimen/material_card_actions_icon_action_size`
3. `@dimen/material_card_actions_icon_action_gutter`


## Media area

### Basic

The basic media area uses keyline ratios for its dimension, which are not provided in this library.

Check the Material design guidelines for more information.

### In title

<img class="figure" src="../../images/components_card_media_in_title.png" alt="Card media in title"/>

1. See following `size` table.
2. `@dimen/material_card_media_area_in_title_padding_top`
3. `@dimen/material_card_media_area_in_title_padding_end`
4. Following block

| Size | Resource |
| ---- | -------- |
| Small (80dp)   | `@dimen/material_card_media_area_framed_size_small`  |
| Medium (120dp) | `@dimen/material_card_media_area_framed_size_medium` |
| Large (160dp)  | `@dimen/material_card_media_area_framed_size_large`  |
| xLarge (240dp) | `@dimen/material_card_media_area_framed_size_xlarge` |

### Framed

<img class="figure" src="../../images/components_card_media_shrunk.png" alt="Card media framed"/>

1. See following `size` table.
2. `@dimen/material_card_media_area_framed_padding_horizontal`
3. `@dimen/material_card_media_area_framed_padding_vertical`
4. Action block

| Size | Resource |
| ---- | -------- |
| Small (80dp)   | `@dimen/material_card_media_area_framed_size_small`  |
| Medium (120dp) | `@dimen/material_card_media_area_framed_size_medium` |
| Large (160dp)  | `@dimen/material_card_media_area_framed_size_large`  |
| xLarge (240dp) | `@dimen/material_card_media_area_framed_size_xlarge` |


## Inset divider

| Name | Resource |
| ---- | -------- |
| Height             | `@dimen/material_divider_height`                        |
| Horizontal padding | `@dimen/material_card_divider_inset_padding_horizontal` |


---

#### See also

- [Raw values](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/card.xml)

- [Cards (Material design)](https://material.google.com/components/cards.html)

