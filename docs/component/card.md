# Card

## Elevation

| Name | Resource |
| ---- | -------- |
| Elevation (resting) | `@dimen/material_card_elevation_resting` |
| Elevation (raised)  | `@dimen/material_card_elevation_raised`  |


## Layout

<img src="/MaterialValues/images/components_card_layout.png" alt="Card layout" style="width: 360px;"/>

1. `@dimen/material_card_edge_margin`
2. `@dimen/material_card_gutter`
3. *Missing value, it will be included in the future*

*Note that the gutter and the edge margin have the same value behind the scenes, if you want to use only one.*

## Title

### Small

<img src="/MaterialValues/images/components_card_title_small.png" alt="Card small title" style="width: 360px;"/>

1. `@dimen/material_card_title_block_padding_horizontal`
2. <del>`@dimen/material_card_title_block_small_padding_top`</del> *Naming issue*
   <del>`@dimen/material_card_title_block_small_padding_bottom`</del> *Naming issue*
3. `@dimen/material_card_title_block_small_height`

| Text  | Resource |
| ----- | -------- |
| Title    | `@dimen/material_card_title_block_small_text_size`    |
| Subtitle | `@dimen/material_card_title_block_subtitle_text_size` |


### Large

<img src="/MaterialValues/images/components_card_title_large.png" alt="Card large title" style="width: 360px;"/>

1. `@dimen/material_card_title_block_padding_horizontal`
2. `@dimen/material_card_title_block_large_padding_top`
3. `@dimen/material_card_title_block_large_subtitle_margin_top`
4. `@dimen/material_card_title_block_large_padding_bottom`
5. *Missing value, it will be included in the future*

| Text  | Resource |
| ----- | -------- |
| Title    | `@dimen/material_card_title_block_large_title_text_size` |
| Subtitle | `@dimen/material_card_title_block_subtitle_text_size`    |


## Supporting text

<img src="/MaterialValues/images/components_card_supporting_text.png" alt="Card supporting text" style="width: 360px;"/>

1. `@dimen/material_card_supporting_text_padding_horizontal`
2. `@dimen/material_card_supporting_text_padding_top`
3. `@dimen/material_card_supporting_text_padding_bottom_last_block`
4. `@dimen/material_card_supporting_text_padding_bottom`

Text size: `@dimen/material_card_supporting_text_text_size`.


## Actions

<img src="/MaterialValues/images/components_card_actions_horizontal.png" alt="Card actions horizontal" style="width: 360px;"/>

1. `@dimen/material_card_actions_row_padding`
2. `@dimen/material_card_actions_action_gutter_horizontal`

<img src="/MaterialValues/images/components_card_actions_vertical.png" alt="Card actions vertical" style="width: 360px;"/>

1. `@dimen/material_card_actions_row_padding`
2. `@dimen/material_card_actions_action_gutter_vertical`

<img src="/MaterialValues/images/components_card_actions_icons.png" alt="Card actions icons" style="width: 360px;"/>

1. `@dimen/material_card_actions_row_padding`
2. *Missing value, it will be included in the future*
3. *Missing value, it will be included in the future*


## Media area

### In title

<img src="/MaterialValues/images/components_card_media_in_title.png" alt="Card media in title" style="width: 360px;"/>

1. See following `size` table.
2. `@dimen/material_card_media_area_in_title_padding_top`
3. `@dimen/material_card_media_area_in_title_padding_end`
4. Following block

| Size | Resource |
| ---- | -------- |
| Small (80dp)   | `@dimen/material_card_media_area_in_title_size_small`  |
| Medium (120dp) | `@dimen/material_card_media_area_in_title_size_medium` |
| Large (160dp)  | `@dimen/material_card_media_area_in_title_size_large`  |
| xLarge (240dp) | `@dimen/material_card_media_area_in_title_size_xlarge` |

### Shrunk

<img src="/MaterialValues/images/components_card_media_shrunk.png" alt="Card media shrunk" style="width: 360px;"/>

1. See "Media area in title" sizes (*Naming issue*)
2. `@dimen/material_card_media_area_shrunk_padding_horizontal`
3. `@dimen/material_card_media_area_shrunk_padding_vertical`
4. Action block


## Inset divider

| Name | Resource |
| ---- | -------- |
| Height             | `@dimen/material_divider_height`                        |
| Horizontal padding | `@dimen/material_card_divider_inset_padding_horizontal` |


---

#### See also

- [Raw values](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/card.xml)

- [Cards (Material design)](https://material.google.com/components/cards.html)

